# Location-Awareness-System
Location Awareness System Using NODE MCU

In this project, we will use GPS Module connected with NODE MCU (ESP8266). A simple local web server is created using
NodeMCU and the location details are updated in that server webpage. NodeMCU is an open source IoT platform. It includes 
firmware which runs on the ESP8266 module and hardware which is based on the ESP-12 module. ESP8266 can be used for 
Geolocation by firstly obtaining nearby AP properties, and then using Google Geolocation API to locate the user-device. 
To be able to obtain a fix on the location of the device that integrates the ESP8266 chip, we assume that the host 
controller first could obtain data from nearby Wi-Fi network cellular sub-systems. The data is consolidated into a data 
block that must be sent to an online Geolocation API or service that will estimate the device location in terms of latitude,
longitude, and accuracy.

Geolocation is defined as the process of finding, determining and providing the exact location of a computer, 
networking device or equipment. It enables us to view the device location based on geographical coordinates and 
measurements.
Geolocation commonly uses Global Positioning System (GPS) and other related technologies to assess and specify 
geographical locations. It provides the location of a device but is generally used in a variety of applications to help
locate human users.
Geolocation is a technology that works through a pre-built GPS in a device that propagates the device's longitudinal 
and latitudinal coordinates. The coordinates are identified on a map to provide a complete address that usually includes
a country, city, town/colony, building name and street address. 
In this project, we will be using Breadboard, Node MCU, GPS Module, Google location API in order to track down the 
most precise geographical location of the entity. The Node MCU component makes the system extremely efficient and 
user-friendly to work with and implement.

---------------------------------------------------------------------------------------------------------------------------
METHODOLOGY
The primary goal of this project is to be able to locate the object in its most precise geographical location using 
the NodeMCU along with its compatible GPS Module. We will need the Blynk App which is available on both Android and 
iOS platform to help us send the location to the mobile via email. The Module will transmit data in multiple strings 
at a Baud Rate. GPS module takes some time to capture location details once it is powered on as it detects the coordinates.
NodeMCU starts webserver and waits for the client to get connected. Once the client is connected to the web server, 
NodeMCU sends location details to the connected client via email using the BLYNK application. The location details 
are displayed on the app. We can track down the location using the displayed coordinates of latitude and longitude on 
the map.

-----------------------------------------------------------------------------------------------------------------------------

Hardware Specification

1) NodeMCU
NodeMCU is an open source based firmware designed for the ESP8266 WiFi SOC from Espressif and uses an on-module 
flash-based SPIFFS file system. It is implemented in C and is layered on the Espressif NON-OS SDK. The firmware 
was initially developed as a companion project to the popular ESP8266-based NodeMCU development modules, but the 
project is now community-supported, and the firmware can now run on any kind of ESP module.
2) GPS Module
The NEO-6 module series is a family of stand-alone GPS receivers featuring high-performance u-blox 6 positioning engine. 
These flexible and cost-effective receivers offer multiple connectivity options in a miniature 16 x 12.2 x 2.4 mm package.
The compact architecture, power and memory options make the NEO-6 modules ideal for battery operated mobile devices with
limited cost and space constraints. Innovative design and technology suppresses jamming sources and mitigates multipath 
effects which give NEO6 GPS receivers excellent navigation performance even in the most challenging environments.   
3) Blynk app:
Blynk is a platform for iOS and Android apps to control Arduino, Raspberry Pi, and other IoT components. 
It's majorly a digital dashboard where you can build a graphical interface for your project by simply dragging 
and dropping widgets. Blynk is not interfaced to some specific board or shield. Instead, it supports the hardware 
of your choice. Whether your Arduino or Raspberry Pi is linked to the Internet over Wi-Fi, Ethernet or ESP8266 chip,
Blynk will get you online and ready for execution. Major IOT projects have been made using this app as it provides a
user-friendly environment.


