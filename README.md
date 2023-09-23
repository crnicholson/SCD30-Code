# scd30Code
This is adapted code based on code from Adafruit that's easier to paste into a spreadsheet. It is used for my carbon capture project. Click here to learn more about that: https://nicholsonlabs.gitbook.io/labs/carbon-capture.

To use this code, first install Adafruit's SCD30 library on your Arduino IDE. Then, connect the SCD30 to a 3.3v tolerant Arduino/MCU (another option is to use a level converter), by connecting the SDA and SCL pins of the Arduino, A4 and A5 respectively. After that, upload the code. Finally, open up the serial monitor, and make sure you have the "Timestamp" button clicked. You can now see the results from your sensor. To calibrate your sensor, follow Adafruit's guide.

To use this in a spreadsheet, make sure you have the "Timestamp" button clicked. Then, copy and paste everything into a spreadsheet. Once in a spreadsheet, select the column where you pasted the data, and go to Data > Split text to columns. This is pictured below:

<img width="639" alt="Screenshot 2023-09-22 at 7 32 49 PM" src="https://github.com/charlienicholson3/scd30Code/assets/83499056/8134be9d-b50c-4334-8e48-10451ed9d581">

Note: In this picture, the data had already been split into columns, but you get the point.

After you're done with that, label your columns to make a graph. I chose the titles Temp, Time, CO2 ppm, and Humidity. Then, select all your columns, and press the chart button to create a graph, like pictured below. Feel free to change your graph style, but in my opinion, the default one is the best.

<img width="1242" alt="Screenshot 2023-09-22 at 7 37 53 PM" src="https://github.com/charlienicholson3/scd30Code/assets/83499056/10e10939-8838-4c5b-a179-1cf996967b2d">

Note: I already made the graph, but you get the idea.

Now you can visualize your data from your CO2 sensor!
Thanks again to Adafruit for the majority of the work.
