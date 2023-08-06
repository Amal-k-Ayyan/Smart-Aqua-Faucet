# Smart-Aqua-Faucet

In our daily life a great amount of water is being wasted either knowingly or unknowingly especially in
our households. Our smart aqua faucet aims to rectify these problems systematically.
There are certain situations where water is lost due to overflow from buckets. Our device can control
the flow of water and prevent overflow. A VL53LOX TOF sensor measures the distance from the faucet
to the surface of water. With a Potentiometer, we can manually set the distance up to which the water
is to be filled. It also consists of a normally opened 12V solenoid valve that closes when the preset
distance is reached.
For normal use, when the device is turned OFF, the solenoid valve will be opened. So faucet can be
used as a normal one.
The module has an OLED display through which water level, temperature and turbidity of water
in the reservoir is continuously monitored. JSN SR - 40T Waterproof Ultrasonic Sensor, DS18B20
Temperature sensor, AZDM01 Turbidity Sensors are used. Data from these are sent and received using
ESP8266 WIFI modules.
The ESP8266 boards communicate using ESP NOW protocol through data link layer. Data is sent
and received every 2 seconds. Each board operates in STA mode. This saves power and reduces possible
transmission delays.
