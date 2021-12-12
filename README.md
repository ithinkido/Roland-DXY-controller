# Roland-DXY-controller
 A modern ESP32 based controller for Roland DXY plotter with i2c shift regisers for button mapping, OLED dispay, solenoid drivers and on board TMC2209 silent stepper drivers that allow full use of the TMC UART features such as stallgurad etc.  

 This Design uses standard STEP/DIR controll only. This is a two board design with a maon controller and a daughter board that handles the USB-C serial connection and SD card. This allows for perfect placement of the connectors and the use of the exsisting opening in the plotter case.

The board is designed to be a a plug in replacemnt with NO modifications to the existing plotter hardware. 
<p align="center"><img src="https://raw.githubusercontent.com/ithinkido/Roland-DXY-controller/TMC-2209/images/plotter_board_front.jpg?sanitize=true" width=80%></p>


