<img width="500" alt="SCD30" src="https://github.com/charlienicholson3/scd30Code/assets/83499056/22551355-9cc2-4589-adc3-8d7794dba94b">

# SCD30 Code
This is adapted code based on code from Adafruit that's easier to paste into a spreadsheet. It is used for my carbon capture project. Click here to learn more about that: https://nicholsonlabs.gitbook.io/labs/carbon-capture.

# Prerequisites:
This mini tutorial assumes you have some exposure to electronics. Knowledge of Arduino would greatly improve your time doing this.

# Setup:
To use this code, first install Adafruit's SCD30 library (https://github.com/adafruit/Adafruit_SCD30) on your Arduino IDE (this is free software you can find online). Then, connect the SCD30 to a 3.3v tolerant Arduino/MCU (another option is to use a level converter) by connecting the SDA and SCL pins of SCD30 to the Arduino pins A4 and A5, respectively. After that, upload the code. To calibrate your sensor, follow Adafruit's guide: https://github.com/adafruit/Adafruit_SCD30.

# Usage:
First, open up the serial monitor in Arduino IDE by pressing the little magnifying glass. Then, press the little timestamp button to make sure you know when you got your data. Run your sensor ten minutes before your test to properly warm it up. Then, copy the data from the serial monitor. After that, paste the copied data into a spreadsheet. Once in a spreadsheet, select the column where you pasted the data, and go to ```Data > Split text to columns```. This is pictured below:

<img width="639" alt="Screenshot 2023-09-22 at 7 32 49 PM" src="https://github.com/charlienicholson3/scd30Code/assets/83499056/8134be9d-b50c-4334-8e48-10451ed9d581">

Note: In this picture, the data had already been split into columns, but you get the point.

# Anaylsis
To visualize your data, choose some titles for your columns. I chose the titles Temp, Time, CO2 ppm, and Humidity. Then, select all your columns, and press the chart button to create a graph, like pictured below. Feel free to change your graph style, but in my opinion, the default one is the best.

<img width="1242" alt="Screenshot 2023-09-22 at 7 37 53 PM" src="https://github.com/charlienicholson3/scd30Code/assets/83499056/10e10939-8838-4c5b-a179-1cf996967b2d">

Note: I already made the graph, but you get the idea.

Now you can visualize your data from your CO2 sensor!
Thanks again to Adafruit for the majority of the work.
