# FlexDrummer

Demo Video - https://youtu.be/o9RlugdTjzQ


The FlexDrummer is a wearable glove created with using an Arduino Uno and Max (v7). Each finger is assigned to one prominent part of the drum kit. The hi-hat, known for keeping faster moving rhythms (e.g. sixteenth notes), is assigned to the thumb, due to its faster tapping rates (C.V. Jackson,1953). Similarly, the bass drum is assigned to the index finger, the snare drum is assigned to the middle finger, the tom-tom drum is assigned to the ring finger and the crash cymbal is assigned to the little finger (pinky), by the order of the tapping rates of the finger and the correlation of the instruments comprising the drum kit. Multiple fingers can be periodically tapped to obtain a rhythm pattern. 

Design
The FlexDrummer is built with: - Hand Glove x 1
- Arduino x 1
- Half Breadboard x 1
- Flex Sensors x 5 - 10kΩ Resistor x 5

The tapping of the fingers is monitored using a series of flex/bend sensors taped in line with the phalanges. Flex sensors measure the amount of bending by varying the resistance of the sensor element. The Flex sensors, attached to the gloves, are connected between the GND and the +5V supply. The voltage being passed is controlled by the help of the 10kΩ resistor which is connected in series with the flex sensor and the power supply. The sensor value is read via the Analog Pins ( A0, A1, etc) of the Arduino by connecting it between the resistor and the positive terminal of the flex sensor.

