Source code used for our old avionics stack.

The source code (very) loosely follows NASA Power of 10 (https://en.wikipedia.org/wiki/The_Power_of_10:_Rules_for_Developing_Safety-Critical_Code)

The code uses arduino specific constructs and the following libraries:
    - TinyGPS++.h
    - HardwareSerial.h
    - Adafruit_Sensor.h
    - Adafruit_ADXL345_U.h
    - Adafruit_BMP280.h
    
The code in example.cpp was used in our first testflight for Affinity mk2 (now decomissioned) that was unsuccessful due to a multitude of smaller failiures.

We are currently slowly moving to a new avionics platform and a new vehicle. The new platform will be build on top of STM32 with a very different architecture
compared to this one, so the code here will probably not see much more use other than as a reference.
