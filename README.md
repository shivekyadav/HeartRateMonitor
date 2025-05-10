# **Heart Rate Monitoring System using Internet**

Heart rate monitoring using the Internet is an Internet of Things-based device used to monitor the heart rate or pulse of a person without being remotely present with them.

## Table of Contents
    1. Description
    2. Hardware Requirement
    3. Software Requirement
    4. Working of the Pulse Sensor
    5. Result
    
## Description
A heart rate is the number of times the heart beats per minute. It is a crucial health parameter that indicates the soundness of human health. Heart patients are required to be monitored with the utmost care, but every time it is not possible for a doctor to be present physically near the patient. So, the plan was to make a “Heart Rate Monitoring System” where the doctor and the assisting family members can access the patient’s data over the Internet from any part of the world.

## Hardware Requirement
### 1. NodeMCU ESP8266 module

 ![NoduMCU](https://components101.com/sites/default/files/components/ESP8266-NodeMCU.jpg)
 
 
### 2. Pulse Sensor

![Pulse-sensor](https://components101.com/sites/default/files/component_pin/Pulse-Sensor-Pinout.png)

### 3. Liquid Crystal Display (LCD)
![LCD](https://cdn11.bigcommerce.com/s-am5zt8xfow/images/stencil/1280x1280/products/211/555/apicwxnfg__12344.1554984177.jpg?c=2)
### 4. I2C LCD Module
![i2c](https://www.pcboard.ca/image/cache/catalog/products/lcd-products/iic-i2c-interface/iic-i2c_serial_interface_board_lcd1602_lcd2004_1-800x800.jpg)
## Software Requirement
### 1. Arudino IDE
It is a free IDE that can be downloaded from https://www.arduino.cc/en/software
### 2. ThingSpeak
ThingSpea is an IoT analytics service that allows you to aggregate, visualize, and analyze live data streams in the cloud. ThingSpeak provides instant visualizations of data posted by your devices to ThingSpeak. With the ability to execute MATLAB code in ThingSpeak, you can perform online analysis and process data as it comes in. ThingSpeak is often used for prototyping and proof-of-concept IoT systems that require analytics.
It is available at https://thingspeak.com/
## Working of the Pulse Sensor
The pulse sensor has two sides. On one side the LED is placed along with an ambient light sensor and on the other side we have some circuitry. This circuitry is responsible for the amplification and noise cancellation work. The LED on the front side of the sensor is placed over a vein in our human body. This can either be your Fingertip or your ear tips, but it should be placed directly on top of a vein.
Now the LED emits light which will fall on the vein directly. The veins will have blood flow inside them only when the heart is pumping, so if we monitor the flow of blood, we can monitor the heartbeats as well. If the flow of blood is detected then the ambient light sensor will pick up more light since it will be reflected by the blood, this minor change in received light is analyzed over time to determine our heartbeats.

# Result
![graph](https://i.imgur.com/H8jOpSP.png)







