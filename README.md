# Laird Connectivity BL654 BME280 Sensor Application

## About

This is the smartBASIC source code for the application used on Laird Connectivity's Pinnacle 100 out of box demo (running on the small sensor board included with the development kit).

![Front of sensor board](http://uwterminalx.lairdconnect.com/Github/BL654SB/BL654SB_Front.png)
![Back of sensor board](http://uwterminalx.lairdconnect.com/Github/BL654SB/BL654SB_Back.png)

## Application

This application acts as peripheral environmental sensor allowing central devices to connect and monitor temperature, humidity, pressure and dew point. Please note that this is supplied as a test application for the Pinnacle 100 development kit and is for evaluation use only, it has not been tested through PTS for confirming that it adheres to the ESS service specification.

## Dew point calculation

The formula for calculating the dew point was adapted from [http://irtfweb.ifa.hawaii.edu/~tcs3/tcs3/Misc/Dewpoint_Calculation_Humidity_Sensor_E.pdf](http://irtfweb.ifa.hawaii.edu/~tcs3/tcs3/Misc/Dewpoint_Calculation_Humidity_Sensor_E.pdf)

## License

This code is released under the [ISC license](https://github.com/LairdCP/BL654_BME280/blob/master/LICENSE).
