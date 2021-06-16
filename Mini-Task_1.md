# Task 1
# Project 1: Contactless Sanitizer dispenser

This project is very relevant right now. This can be an alternative to the foot based mechanical ones deployed currently. The basic concept is it has a proximity sensor(could be IR or ultrasonic as well) which is the input device. Once it reads that a hand is in close proximity to the nozzle it signals the servo motors to proceed with the rotation to pump out sanitizer. This is all done with an Arduino UNO. Use two servo motors for a balance motion.

Source:https://www.hackster.io/utkarsh5679077/touchless-soap-sanitizer-dispenser-7261ae

# Project 2: IoT based Thermal Alarm

This project sends a SMS to your mobile phone if the temperature of the device or room you're monitoring crosses a set threshold. As expected this has a wide ranging applications in mmany fields and industries as temperature is a key factor for anything. Here this is achieved by using the Bolt IoT Bolt WiFi module to read the data and relay it to the Twilio Messaging. The sensor used is LM35(Temperature sensor). We can add more output devices like buzzers and LEDs to show the current state apart from the SMS alerts. This can be improved using a better temperature sensor and has a lot of scope in industries as by adding in more sensors we can remotely monitor the parameters of equipment.

Source:https://www.hackster.io/srinjit35/iot-based-thermal-alarm-fa729d

# Project 3: Controlling 2 motors using a JoyStick

This project uses a Joystick, few pushbuttons and 2 servo motors. The basic working is that when the joystick is moved the respective push buttons are pressed leading to them activating the servo motors. This requires minimal material to do and the motors can be connected to different things to alter their orientation in 2 dimensions

Source: https://www.instructables.com/2-motor-control-joystick/

# Project 4: Biometric Student Attendance

This project is used to mark the attendance of students and teachers with their fingerprints. So for this we use a fingerprint sensor module, an Arduino UNO and create GUI apps using visual basic 2010 express edition. We use a 433 MHz wireless module for transmission Since this is outdated we can use the latest version as well to create the app. This is the basic set up of the project where it shows a tick mark for people who logged in after registering their fingerprint. We can also use the Xampp server to maintain and record all this data in a MySQL database for future reference. This has multiple applications as well as we can store other forms of biometric data as and use this same basic concept as a security device. We could also recored the temperatures of people when they check in especially in the post covid world.

Source: https://www.electroniclinic.com/biometric-student-attendance-system-with-database-using-vb-net-arduino/

# Project 5: Water level controller using 8051 microcontroller

This project is an extension on the water level monitor. Here this is based on the principle that water conducts electricity. So it has 3 wires to check the water levels and the wires immersed in the water will conduct. After determining the water level the motor turns on if it is low and turns off once reaches to the high point. For this we use an 8051 based microcontroller(AT89C51), transistors and servo motors for demonstrating the motor for the water pump. Here we use the Keil uvision IDE for programming.

Source: https://www.electronicshub.org/water-level-controller-using-8051-microcontroller/

# Project 6: Homemade Pulse Oximetry Display

Another project w.r.t the pandemic thats going on currently. This is an Arduino UNO based project using an integrated pulse oximeter and heart rate sensor(MAX30102) and an I2C 16x2 LCD display. So here this device can be made at home to measure your oxygen saturation levels as the display contains your pulse O2 saturation.

Source: https://www.hackster.io/furqanahsan/the-h-p-o-d-homemade-pulse-oximetry-display-4b39ce

# Project 7: Realtime Earthquake detection system

This very interesting project involves Machine learning using SensiML and Quickfeather to process the data and deploy it. So this takes in seismic data from the past and prepares a deployable ML model to be used for future detection. For this we use the QuickFeather Dev kit with Sensi ML and a ESP32 with WIFI and bluetooh with a Quickfeather module. We use the Thinger.io as the cloud to connect to our mobile app to recieve data as to if theres an earthquake detected at the sensor or not.

Source: https://www.hackster.io/salahuddin/realtime-earthquake-detection-system-fe4cd3

# Project 8: Density based Traffic Signal System

So in this project we have assumed a 4 way crossing where traffic signals are required. To automate this we use IR sensors to represent obstacles(traffic). This is based on the ATmega8 controller. So here if there is no traffic then there is a present time delay which all signals will follow. When traffic is detected the that particular signal will turn green while the others turn red and once the traffic is cleared this will revert back to the time delay loop. For the sake of simulation 4 sets of colored leds(or 4 multi color leds) for the traffic signals. This could be made better by using better sensors to monitor the traffic density as there might be cars on all roads. We need to strengthen our algorithms to account for all possible basic test cases, like multiple roads having traffic at the same time or how long one particular lane has been waiting.

Source: https://www.electronicshub.org/density-based-traffic-signal-system-using-microcontroller/

# Project 9: 



