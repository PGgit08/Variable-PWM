# Variable-PWM
A Printed Circuit Board designed and built by Peter Gutkovich.

## Description
### How It Works
The Variable PWM PCB is a PCB designed and built by me. It produces a Pulse Width Modulation (PWM) square-wave signal. 
This signal can be modified with potentiometers **VR1** and **VR2**. **VR1** changes the signal's *frequency*, which can either range from around **0.7 HZ - 7 HZ (SLOW MODE)** or **19.7 HZ - 216.7 HZ (FAST MODE)**. Switch **S1** sets the board to **FAST MODE** if it is switched to the *left*, and it sets the board to **SLOW MODE** if it is switched to the *right*. Potentiometer **VR2** controls the signal's *duty cycle* which ranges from **0% - 100%**. LED D1 indicates the signal produced by the board by flashing on and off depending on the signal. **[Click here for in-depth explanation.](/Docs/Explanation.md)**

### Board Images
![Board Front](/Simulation/Board_Front.jpg)
![Board Back](/Simulation/Board_Back.jpg)

## How To Use the Board
**The board should be powered with a 9V Battery.** Use the **+** and **-** pins to power the board. Use the **OUT** pin for the output signal, and the **GND** pin for connecting to the *board's* ground. Click **[here](/Simulation/SimVideos.md)** to see this board in action. 


## Design and Parts
### Design Hardware
The schematic and board files can be found in **[the Hardware folder](/Hardware)**. An image of the schematic can also be seen right **[here](/Hardware/Variable_PWM.pdf)**.

### Parts Required
- LM358P Dual Operational Amplifier DIP-8 **(x1)** -> [Amazon Link](https://www.amazon.com/gp/product/B07WQWPLSP/)
- NE555 Timer DIP-8 **(x1)** -> [Amazon Link](https://www.amazon.com/gp/product/B07WR9B4JT)
- 10 uF Electrolytic Capacitor @50V (Generic) **(x4)**
- 100 uF Electrolytic Capacitor @50V (Generic) **(x1)**
- 0.1 uF Ceramic Capacitor @>9V (Generic) **(x1)**
- 10K Potentiometer **(x2)** -> [SparkFun Link](https://www.sparkfun.com/products/9806)
- DIP-8 IC Socket **(x2)** -> [SparkFun Link](https://www.sparkfun.com/products/7937)
- 10K Resistor (Generic) **(x4)** 
- 1K Resistor (Generic) **(x4)** 
- 3 Pin Slideswitch **(x1)** -> [Amazon Link](https://www.amazon.com/gp/product/B09R42XQTB)
- Male Header Pin (Generic) **(x4)**
- NPN Transistor @200mA/40V (Generic) **(x1)**
- LED @3V (Generic) **(x1)**

### **SCHEMATIC BASED ON SPARKFUN LIBRARIES -> [HERE](https://github.com/sparkfun/SparkFun-Eagle-Libraries)**
