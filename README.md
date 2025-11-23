# 🔧 Components Used

•	2 × NE555 Timer IC

•	Red, Yellow, Green LEDs

•	100KΩ, 47KΩ, 330Ω, 180Ω resistors

•	100µF electrolytic capacitors

•	Jumper wires

•	Breadboard

•	5–9V power supply

# ⚡ Working Principle

The circuit uses two 555 timers:
 
Timer 1 – Red to Yellow transition
-	Controls the ON duration of the Red LED
-	When Timer 1 output falls, the Yellow LED is triggered

Timer 2 – Yellow to Green transition
- Controls Yellow and Green timings
- Completes the cycle and repeats continuously

Timing is defined by:
              T=0.693(R1+2R2)C

By changing resistor or capacitor values, you can adjust how long each LED stays ON.

# 🧩 Schematic
![schematic](https://github.com/Karthikeyanmac/Traffic-Light-Controller-Using-NE555-Timer-IC/blob/main/schematic_traffic_light_555.jpeg)\

# 🛠️ Breadboard Implementation
![Breadboard}(https://github.com/Karthikeyanmac/Traffic-Light-Controller-Using-NE555-Timer-IC/blob/main/breadboard_image.jpg)\

