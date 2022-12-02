# 8051-microcontrollers.-

Our main target was to create a better environment for plants and trees. What the circuits do, is measure
different data from the environment and send them to the peripheries. So we can measure the liquid level
in the ground and find out if plants and trees need more or less water, for this part I used an analogic
sensor SEN0114. The sensor is connected to ADC, which converts the analogic data from the sensor to
digital data and sends it to a microcontroller.
The other sensor is a digital sensor BMP180 in which case we need to use an I2C protocol to receive and
send data, it was also connected later to the microcontroller.
In the end, we read the collected data on an LCD. The code that was used for this project is Assembly, and
the programs are Keil uVision 5 and Proteus
