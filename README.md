# Variable-PWM
A Printed Circuit Board designed and built by Peter Gutkovich.

## Description
### How It Works
The Variable PWM PCB is a PCB designed and built by me. It produces a Pulse Width Modulation (PWM) square-wave signal. 
This signal can be modified with potentiometers **VR1** and **VR2**. **VR1** changes the signal's *frequency*, which can either range from around **0.7 HZ - 7 HZ (SLOW MODE)** or **19.7 HZ - 216.7 HZ (FAST MODE)**. Switch **S1** sets the board to **FAST MODE** if it is switched to the *left*, and it sets the board to **SLOW MODE** if it is switched to the *right*. Potentiometer **VR2** controls the signal's *duty cycle* which ranges from **0% - 100%**. LED D1 indicates the signal produced by the board by flashing on and off depending on the signal. Use the **+** and **-** pins to power the board. Use the **OUT** pin for the output signal, and the **GND** pin for connecting to the *board's* ground. **[Click here for in-depth explanation.](/Docs/Explanation.md)**

## Design and Build Parts
### **POWER SUPPLY** -> **9V Battery**
### **BASED ON SPARKFUN LIBRARIES** -> **[HERE](https://github.com/sparkfun/SparkFun-Eagle-Libraries)**