  HOME AUTOMATION 
In today's era, technology can enhance human life. Technology is evolving decade by decade.
Automation was a science fiction earlier but not today. By combining latest technology with home, we can build an awesome home. With the Arduino uno and Windows 10, we can build a home automation system that is capable of operating home devices automatically.

REQUIREMENTS
1.ARDUINO UNO![WhatsApp Image 2022-03-07 at 8 44 59 PM](https://user-images.githubusercontent.com/98831387/157061982-1f369881-867f-4af2-8742-13ffe6650ffa.jpeg)

Arduino Uno is a microcontroller board based on the ATmega328P (datasheet). It has 14 digital input/output pins (of which 6 can be used as PWM outputs), 6 analog inputs, a 16 MHz ceramic resonator (CSTCE16M0V53-R0), a USB connection, a power jack, an ICSP header and a reset button. It contains everything needed to support the microcontroller; simply connect it to a computer with a USB cable or power it with a AC-to-DC adapter or battery to get started.. You can tinker with your Uno without worrying too much about doing something wrong, worst case scenario you can replace the chip for a few dollars and start over again.
"Uno" means one in Italian and was chosen to mark the release of Arduino Software (IDE) 1.0. The Uno board and version 1.0 of Arduino Software (IDE) were the reference versions of Arduino, now evolved to newer releases. The Uno board is the first in a series of USB Arduino boards, and the reference model for the Arduino platform; for an extensive list of current, past or outdated boards see the Arduino index of boards

2.PIR SENSOR![WhatsApp Image 2022-03-07 at 8 46 31 PM](https://user-images.githubusercontent.com/98831387/157062208-f7210ad3-8865-4e74-8f59-41f632f25685.jpeg)

This is a simple to use motion sensor. Power it up and wait 1-2 seconds for the sensor to get a snapshot of the still room. If anything moves after that period, the 'alarm' pin will go low.
This unit works great from 5 to 12V.
The alarm pin is an open collector meaning we will need a pull up resistor on the alarm pin. The open drain setup allows multiple motion sensors to be connected on a single input pin. If any of the motion sensors go off, the input pin will be pulled low.
now  wel find a common 3-pin,This makes the PIR Sensor much more accessible for whatever your project may need.
Red = Power
White = Ground
Black = Alarm

3.LM35(TEMPERATURE SENSOR) ![WhatsApp Image 2022-03-07 at 8 47 30 PM](https://user-images.githubusercontent.com/98831387/157062390-48c4cfec-9db2-4124-99a9-f2c0554e734c.jpeg)

A precision IC temperature sensor with its output proportional to the temperature (in oC). The sensor circuitry is sealed and therefore it is not subjected to oxidation and other processes.

4.SERVO MOTORS![WhatsApp Image 2022-03-07 at 8 48 16 PM](https://user-images.githubusercontent.com/98831387/157062553-837282a7-61b1-424e-89ce-d3d3a6bf3a1f.jpeg)

Servo motors are geared DC motors with the closed-loop circuitry incorporated within them. The basic configuration of a servo motor composed of a DC motor, gearbox, potentiometer and control circuit.DC motor is used to move a gearbox with a large reduction ratio. The final shaft imposes a force on the external load and simultaneously acts on the axis of the feedback potentiometer. So, the potentiometer senses the position of the axis and sends a corresponding voltage to an operational amplifier. This voltage compared to the input voltage, that determines the desired position of the shaft, producing a voltage in the output of the comparator. This voltage powers the motor such that the shaft moves in the necessary direction to align with the angle that corresponds to the voltage applied to the input.

5.HC-05 BLUETOOTH![WhatsApp Image 2022-03-07 at 8 49 02 PM](https://user-images.githubusercontent.com/98831387/157062666-fafd743d-cf1b-4542-a06c-2717f1e794ae.jpeg)

HC-05 is a Bluetooth module which is designed for wireless comunication. This module can be used in a master or slave configuration.

HIGH LEVEL REQUIREMENT
It is very convenient to use. 

LOW LEVEL REQUIREMENT
Stay at home be connected to the internet.
Always be on.

ADVANTAGE
Energy saving.
It is very convenient to use.





