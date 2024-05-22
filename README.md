# 8x8x8-Led-Decorative-Cube-Using-Arduino-Uno
Sure, here's a concise summary:  The 8x8x8 LED Cube is a decorative piece controlled by an Arduino Uno, capable of displaying various light patterns. It uses a 93dn8wy (SN74HC595N) IC, PN2222A transistor, TS-1109 switch, resistors, and LEDs. The cube offers different display modes, making it a versatile and interactive decoration or learning tool.



**Title:** 8x8x8 LED Decorative Cube using Arduino Uno

**Introduction:**

This project is an 8x8x8 LED Cube that serves as a decorative piece, capable of displaying mesmerizing light patterns in three dimensions. 
It is built using an Arduino Uno, a 93dn8wy (SN74HC595N) IC, a PN2222A transistor, a TS-1109 tactile switch, resistors, and LEDs.

**Components:**

1. **Arduino Uno:** The brain of the project, controlling the LED patterns and handling user input.
2. **93dn8wy (SN74HC595N) IC:** A shift register used to expand the number of outputs from the Arduino, allowing it to control the large
3. number of LEDs in the cube.
4. **PN2222A Transistor:** Used to switch the LEDs on and off.
5. **TS-1109 Tactile Switch:** Allows the user to switch between different display modes.
6. **Resistors:** Used to limit the current to the LEDs, preventing them from burning out.
7. **LEDs:** The main visual component of the project, arranged in an 8x8x8 grid to form a cube.

**Working Principle:**

The Arduino Uno controls the state of each LED in the cube. It does this by sending signals to the SN74HC595N IC, which in turn controls the 
PN2222A transistors. These transistors act as switches, turning the LEDs on and off. The Arduino can control which LEDs are on at any given time,
allowing it to create complex light patterns.

The TS-1109 tactile switch is connected to the Arduino and allows the user to switch between different display modes. Each mode is a different 
light pattern, providing variety and user interactivity.

**Applications:**

This LED cube can serve as a decorative piece in a living room, a cool desk gadget, or even a night lamp. The different modes provide variety and
keep the display interesting. As an open-source project, it can also be a great learning tool for those interested in electronics, hardware
programming, and DIY projects.

