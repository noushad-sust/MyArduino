# MyArduino
arduino code

Arduino as a hardware control server.
Send command from software to configure arduino to do analog, digital pin control, servo control.

Version: 1
	Digital,Analog,Servo

Command Fromat: 

	header=pin:value,pin:value...

	pin=arduino pin number.	
	value=anyvalue for read and config

Usage:
	
	sc=0:7,1:6,2:5,3:4
	sw=0:120,3:90
	key is always a pin number.
	val is any number.
	Response:
	Success or Failed
	Option Data
	\n
