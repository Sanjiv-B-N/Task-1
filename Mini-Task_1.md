# Task 1
# Project 1: Contactless Sanitizer dispenser

This project is very relevant right now. This can be an alternative to the foot based mechanical ones deployed currently. The basic concept is it has a proximity sensor(could be IR or ultrasonic as well) which is the input device. Once it reads that a hand is in close proximity to the nozzle it signals the servo motors to proceed with the rotation to pump out sanitizer. This is all done with an Arduino UNO. Use two servo motors for a balance motion.

![](https://media.giphy.com/media/QBXUyajWSaxWNOE7qw/giphy.gif)


Source:https://www.hackster.io/utkarsh5679077/touchless-soap-sanitizer-dispenser-7261ae

# Project 2: IoT based Thermal Alarm

This project sends a SMS to your mobile phone if the temperature of the device or room you're monitoring crosses a set threshold. As expected this has a wide ranging applications in mmany fields and industries as temperature is a key factor for anything. Here this is achieved by using the Bolt IoT Bolt WiFi module to read the data and relay it to the Twilio Messaging. The sensor used is LM35(Temperature sensor). We can add more output devices like buzzers and LEDs to show the current state apart from the SMS alerts. This can be improved using a better temperature sensor and has a lot of scope in industries as by adding in more sensors we can remotely monitor the parameters of equipment.

![image](https://user-images.githubusercontent.com/84587485/122561870-fcff6a80-d05f-11eb-8902-b555f61a9a67.png)


Source:https://www.hackster.io/srinjit35/iot-based-thermal-alarm-fa729d

# Project 3: Controlling 2 motors using a JoyStick

This project uses a Joystick, few pushbuttons and 2 servo motors. The basic working is that when the joystick is moved the respective push buttons are pressed leading to them activating the servo motors. This requires minimal material to do and the motors can be connected to different things to alter their orientation in 2 dimensions.

Source: https://www.instructables.com/2-motor-control-joystick/

# Project 4: Biometric Student Attendance

This project is used to mark the attendance of students and teachers with their fingerprints. So for this we use a fingerprint sensor module, an Arduino UNO and create GUI apps using visual basic 2010 express edition. We use a 433 MHz wireless module for transmission Since this is outdated we can use the latest version as well to create the app. This is the basic set up of the project where it shows a tick mark for people who logged in after registering their fingerprint. We can also use the Xampp server to maintain and record all this data in a MySQL database for future reference. This has multiple applications as well as we can store other forms of biometric data as and use this same basic concept as a security device. We could also recored the temperatures of people when they check in especially in the post covid world.

![image](https://user-images.githubusercontent.com/84587485/122560510-4ea6f580-d05e-11eb-88c3-edbaa02654a9.png)


Source: https://www.electroniclinic.com/biometric-student-attendance-system-with-database-using-vb-net-arduino/

# Project 5: Water level controller using 8051 microcontroller

This project is an extension on the water level monitor. Here this is based on the principle that water conducts electricity. So it has 3 wires to check the water levels and the wires immersed in the water will conduct. After determining the water level the motor turns on if it is low and turns off once reaches to the high point. For this we use an 8051 based microcontroller(AT89C51), transistors and servo motors for demonstrating the motor for the water pump. Here we use the Keil uvision IDE for programming.

![](https://media.giphy.com/media/3o6MbrBnzHFQpNDzlC/giphy.gif)

Source: https://www.electronicshub.org/water-level-controller-using-8051-microcontroller/

# Project 6: Homemade Pulse Oximetry Display

Another project w.r.t the pandemic thats going on currently. This is an Arduino UNO based project using an integrated pulse oximeter and heart rate sensor(MAX30102) and an I2C 16x2 LCD display. So here this device can be made at home to measure your oxygen saturation levels as the display contains your pulse O2 saturation.

Source: https://www.hackster.io/furqanahsan/the-h-p-o-d-homemade-pulse-oximetry-display-4b39ce

# Project 7: Realtime Earthquake detection system

This very interesting project involves Machine learning using SensiML and Quickfeather to process the data and deploy it. So this takes in seismic data from the past and prepares a deployable ML model to be used for future detection. For this we use the QuickFeather Dev kit with Sensi ML and a ESP32 with WIFI and bluetooh with a Quickfeather module. We use the Thinger.io as the cloud to connect to our mobile app to recieve data as to if theres an earthquake detected at the sensor or not.

![](https://media.giphy.com/media/2cca3c7hwNx1C/giphy.gif)

Source: https://www.hackster.io/salahuddin/realtime-earthquake-detection-system-fe4cd3

# Project 8: Density based Traffic Signal System

So in this project we have assumed a 4 way crossing where traffic signals are required. To automate this we use IR sensors to represent obstacles(traffic). This is based on the ATmega8 controller. So here if there is no traffic then there is a present time delay which all signals will follow. When traffic is detected the that particular signal will turn green while the others turn red and once the traffic is cleared this will revert back to the time delay loop. For the sake of simulation 4 sets of colored leds(or 4 multi color leds) for the traffic signals. This could be made better by using better sensors to monitor the traffic density as there might be cars on all roads. We need to strengthen our algorithms to account for all possible basic test cases, like multiple roads having traffic at the same time or how long one particular lane has been waiting.

![image](https://user-images.githubusercontent.com/84587485/122560816-b52c1380-d05e-11eb-8ac9-98a2490ad5d1.png)


Source: https://www.electronicshub.org/density-based-traffic-signal-system-using-microcontroller/

# Project 9: Automatic Washroom light switch

This project uses the Reed switch with magnet to identify the state of the door and uses a LM741 Op-Amp IC and a CD4017 Decade counter to control the lights. This set up will turn on the lights if you open the door and close it once. And it'll reset everything back to off when you opwn and close the door again while leaving the room. This could be made better by using a IR sensor and reciever pair to be more sensitive to the door movements. This prevents accidental power wastage if people forget to turn off the lights while leaving the room.

![](https://media.giphy.com/media/3o7TKO91XVqB383RN6/giphy.gif)

Source: https://www.electronicshub.org/automatic-washroom-light-switch/

# Project 10: Unbiased Electronic Dice LEDs

This is based on the principle that the time interval between is very fast and imperceptible to the human eye. Here we use 6 LEDs to denote the 6 numbers on a die and 4017 Decade counter to count to through the numbers. Here the 7th instance is connected to reset to begin the counting from 1 again. Here we use the NE555 in astable mode and use it to generate square pulses which act as the clock for the counter. The push button is connected to the NE555 to stop generating pulses when it is not pressed. This creates a nearly unbiased electronic dice as normal ones maybe biased due to deformations caused by physical impact.

Source: https://www.electronicshub.org/unbiased-electronic-dice-with-leds/

# Project 11: Arduino Car Speed Detector

The present speed require manual interaction to point at a vehicle to read its speed. But this project uses 2 IR sensors with recievers placed say 10m to figure out the speed of an obstacle. The IR sensor with a reciever, recieves a signal when it encounters an obstacle it records the time. When the 2nd reciever encouters the object it records the time and calculates the speed using the time difference. An aruduino Uno is used for this project. There  is a lot of scope for this project and it can be improved by accounting for multiple vehicles passing a sensor before it reaches the other one. And we can make use of another IR distance sensor to measure the distance between the IR sensor and alter the code accordingly so that the the sensors need noe be placed exactly at 10m apart.

![](https://media.giphy.com/media/zCzrh9mEOULVm/giphy.gif)

Source: https://www.electronicshub.org/arduino-car-speed-detector/

# Project 12: Electronic Letter Box

This project is based on the LED and the LDR and that a letter is opaque and will block the light coming from the LED to the LDR. To identify this we use 741 Op-Amp and CD4001 (Quad NOR Gate IC) and an LED is used to indicate the presence of a letter. So the light will indicate whether the box is empty or has at least one letter.

![image](https://user-images.githubusercontent.com/84587485/122561382-6a5ecb80-d05f-11eb-89b4-996a1774fcdb.png)


Source: https://www.electronicshub.org/electronic-letter-box-project-circuit/

# Project 13: Smart Irrigation System

This system tracks the moisture level of the soil and activates the pump accordingly to maintain moisture level in the given range. Here we can measure the moisture using a capacitive soil moisture sensor and turn on the pump using the Wesmos D1 Mini board. We can also use a telegram bot for controlling the pump and getting the readings from the sensor. Here we also use a SD module to store the moisture data to use it in the future.

![image](https://user-images.githubusercontent.com/84587485/122561449-7fd3f580-d05f-11eb-89b5-4a7edb47d72d.png)


Source: https://www.hackster.io/407032/smart-irrigation-capacitive-soil-moisture-sensor-vallauri-2bbf98

# Project 14: Interfacing GPS with a 8051 micro controller

The Global Positioning System(GPS) is a set of 24-32 satellittes that continuosly provide data to recievers across the globe. Here we use a GPS module to recieve the raw data and decipher the Latitude and Longitude to display them on them on a LCD display. Here we use an 8051 Micro cotroller and a Max232 IC for level conversion. The GPS module transmits the data using the RS232 protocol as per NMEA standards. And we need to extract the Latitude and Longitude from the recieved messages.

![Alt Text](https://media.giphy.com/media/co6DjYwuhG17ITs6VB/giphy.gif)

Source: https://www.electronicshub.org/interfacing-gps-8051-microcontroller/

# Project 15: Battery level indicator

This project is based on the LM3914 IC. This IC takes input analog voltage and drives 10 LED’s linearly according to the input analog voltage. So here we can alter the volage range we measure by using resitors and callibrating them to suit the battery. This same principle can be used for measuring the lead acid batteries in your car at home to measure its health. But you may need to switch the components as the voltage range for this test project is very low.


Source: https://www.electronicshub.org/battery-level-indicator/

