# arduino-blinking-led

Arduino Blinking LED Project

I built a blinking LED using Arduino. As a novice, the goal here was to get hands-on experience with electronics and electricity. The goal was to understand the role electricity plays in electronics and to learn basic electricity concepts such as: voltage, current, conventional current, resistance, and circuits. 

Components Used:

x1 Arduino UNO (microcontroller)    

x1 LED (Red)                           

x1 220 Ohm Resistor

x1 Breadboard 

x2 Jumper Wires

x1 USB Cable 

Takeaways: 

A circuit is a closed loop that carries electricity. For current to flow through a circuit, there must be a closed electrical path. In order to have a circuit, current must come back to where it started from. 

Current is the flow of charge. Conventional current is the direction positive charge would flow in. When drawing and analyzing schematics, we use conventional current.

Voltage is the difference in electric potential between two points. Voltage is comparable to pressure in a water pipe. Just like more pressure in a water pipe allows for more water to flow--more voltage in a circuit allows for more current to flow. 

Resistance acts like friction for electricity. It impedes the flow of current in a circuit. Components known as resistors allow us to create resistance in a circuit. Resistance is measured in Ohm's. 




---FURTHER CIRCUIT ANALYSIS--- (done days later):

Concepts/Terms learned: Ohm's Law (V=IR), forward voltage, series circuit, voltage drop, LED anode, LED cathode 

Circuit Analysis: 

The circuit is powered by a 5 V supply from the Arduino UNO. The LED has a forward voltage of approximately 2 V. Therefore, there is approximately a 3 V voltage drop across the 220 ohm resistor. 

Using Ohm's Law:

V = IR --> I = V/R --> I = 3 V / 220 Ohms = 0.0136 A = 13.6 mA 

Therefore, the current through the resistor is approximately 13.6 mA. Because the resistor and LED are connected in series, the same 13.6 mA of current flows through the LED. 




