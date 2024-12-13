# cars-anti-cats
Developed a system based on Raspberry Pi 4 that detects the presence of a cat near a vehicle using infrared (IR) sensors, and triggers an ultrasonic sound emitter to deter the cat. The system should increase the sound intensity if multiple sensors detect the cat simultaneously.
Raspberry Pi 4:
The central control unit that processes inputs from the infrared sensors and controls the ultrasonic emitter.
Infrared Sensors (7 units):
Positioned around the vehicle  to detect motion. Each sensor outputs a HIGH signal when a cat is detected and LOW when not.
Ultrasonic Sound Emitter:
Emits ultrasonic sound when activated. The intensity of the sound increases based on the number of sensors detecting the cat.
Battery supply:
The system draws power from the vehicle’s 12V battery though a step-down module (DC-DC converter)  to convert the voltage to 5v
back-up supply
lithium battery is required if vehicle battery is not supplying.
