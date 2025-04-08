# RC Car Energy Capture
Authers: Mason Ciari, Trey Gohlmann, Shawn Laikupu, and Roman West

Abstract:
This is an engineering capstone project which is a proof of concept for capturing and storinng the turbulant flow of air around an electric car.

# Componants

Raspberry Pi:
- We used a raspberry pi 3b+ to read, compute, and store power readings from rc motor and turbine generator.

INA219 Voltage Sensors (quantity: 2):
- The INA219 voltage sensors read the voltage drop across a 0.1 ohm. Then sends the voltage data via the i2c bus to the raspberry pi.
- One was positioned to read the current from rc controller to the rc motor, and another was used to read the power output from the turbine generator.

RC Car:
- An rc car was bought online and deconstructed to incoorperate different componates of the project.

Generator:
- A standard electric motor DC motor was used.

Turbine:
-A toridal turbine design was used based on it's efficency when compaired to other designs.

A-Frame Turbine Mount:
- An a-frame mounting bracket was used to elevate the turbine+generator away from the base of the rc car.
