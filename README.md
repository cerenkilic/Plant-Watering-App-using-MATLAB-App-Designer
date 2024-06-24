# Plant-Watering-App-using-MATLAB-App-Designer
The aim of this project was to develop an application to check the soil moisture status and water the plants based on the data received. This application helps to monitor soil moisture and makes plant care easier. All of the GUI design and coding process is done through MATLAB. 
## GUI Design

![image](https://github.com/cerenkilic/Plant-Watering-App-using-MATLAB-App-Designer/assets/74498810/e062da64-9fc1-4d22-bc8d-2bdf73e292f1)


In my GUI design I used axes element to display the graph of soil humidity level with respect to time, I used buttons for plot, exit, save as fig, save as png,save data (save as .xlsx) and print operations. Selecting the threshold level is done by a slider element since it is easier to use, and the user can select any threshold level between 0-100.

## Circuit Setup

I used a small water pump to water my plant. Also, a soil humidity sensor is used. Arduino Mega is used only for to make the communication between the sensor, water pump and the computer. The soil humidity sensor is 5V when the soil is dry and 0V when soil is in %100 humidity.

![image](https://github.com/cerenkilic/Plant-Watering-App-using-MATLAB-App-Designer/assets/74498810/7e0e5714-970f-4354-9777-348f2f53ce35)

