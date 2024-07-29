# Master-Slave-RP2040-RX-TX
Master-Slave RP2040 RX TX


This project uses a master-slave model to facilitate communication between a master module and slave modules. The microcontroller used for this project is an Adafruit Feather RP2040 Scorpio, which features 8 channels.

The master module sends commands to the slave modules and measures to ensure the commands are received correctly. The IDE used for this project is Arduino.

To get started, open the Arduino IDE and copy the code provided for the master module. Install the code on the master device using the Arduino IDE. In the upper right corner of the IDE, you will see an icon labeled "Serial Monitor." Open the Serial Monitor and select "Adafruit Scorpio" as your board. A window will appear for you to enter commands.

If you input "1", the Scorpio will send a command to the slaves to turn on the LED. If you input "0", it will send a command to turn off the LED.
