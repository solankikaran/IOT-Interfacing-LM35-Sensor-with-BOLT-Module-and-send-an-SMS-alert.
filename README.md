# IOT-Interfacing-LM35-Sensor-with-BOLT-Module-and-send-an-SMS-alert.
The Project consisted of interfacing an LM35 sensor with BOLT Module to send an SMS alert using Twilio when a temperature crosses a threshold value.

Hardware required
The Bolt Wifi module
3 female to male wire
Temperature Sensor: LM35 sensor
Connecting the LM35 sensor to the Bolt

Step 1: Hold the sensor in a manner such that you can read LM35 written on it.

Step 2: In this position, identify the pins of the sensor as VCC, Output and Gnd from your left to right.

Hardware Connections as follows: 
--VCC pin of the LM35 connects to 5v of the Bolt Wifi module.
--Output pin of the LM35 connects to A0 (Analog input pin) of the Bolt Wifi module.
--Gnd pin of the LM35 connects to the Gnd.

Step 3: Create an account on Twilio. After the setup a number will be assigned to you. This number will be used in the conf.py file when you will code.

Step 4: After the HW connections and the setup, run the TempSms.py file. VPS, Linux, Windows command prompt can be used to run the TempSMS python file.
