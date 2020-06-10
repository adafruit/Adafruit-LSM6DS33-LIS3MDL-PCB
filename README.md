## Adafruit LSM6DS33 + LIS3MDL 9-DoF IMU with Accel/Gyro/Mag PCB

<a href="http://www.adafruit.com/products/4485"><img src="assets/4485.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit LSM6DS33 + LIS3MDL 9-DoF IMU with Accel/Gyro/Mag.

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/4485

### Description

Add motion, direction and orientation sensing to your Arduino project with this all-in-one 9 Degree of Freedom (9-DoF) sensor with sensors from ST. This little breakout contains two chips that sit side-by-side to provide 9 degrees of full motion data.

The board includes an LSM6DS33, a 6-DoF IMU accelerometer + gyro. The 3-axis accelerometer, can tell you which direction is down towards the Earth (by measuring gravity) or how fast the board is accelerating in 3D space. The 3-axis gyroscope that can measure spin and twist. The three triple-axis sensors add up to 9 degrees of freedom.

It also includes a LIS3MDL 3-axis magnetometer that can sense where the strongest magnetic force is coming from, generally used to detect magnetic north. By combining this data you can orient the board.

These chips are not the newest motion sensors, but they are well-established and come at a great price. Together you have a nice 9 DoF IMU setup that is affordable for any project. Design your own activity or motion tracker with all the data...

To make getting started fast and easy, we placed the sensors on a compact breakout board with voltage regulation and level-shifted inputs. That way you can use them with 3V or 5V power/logic devices without worry. To make usage simple, we expose only the I2C interface and some interrupt pins from each chip. The breakout comes fully assembled and tested, with some extra header so you can use it on a breadboard. Four mounting holes make for a secure connection.

Additionally since it speaks I2C you can easily connect it up with two wires (plus power and ground!).  We've even included SparkFun qwiic compatible STEMMA QT connectors for the I2C bus so you don't even need to solder! Just wire up to your favorite micro like the STM32F405 Feather with a plug-and-play cable to get 9 DoF data ASAP. You can change the I2C addresses on the back using the solder jumpers, to have two of these sensor boards on one bus.

We also wrote libraries to help you get these sensors integrated with your Arduino/C++. This library covers the accel/gyro and this library is for the magnetometer. For advanced Arduino usage, ST has their own fully-featured library that includes extras such as FIFO management and tap detection for the LSM6DS3 and also for the LIS3MDL magnetometer

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution.
See license.txt for additional details.
