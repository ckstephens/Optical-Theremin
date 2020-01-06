# Optical-Theremin
Theremin using Arduino and ultrasonic sensors.

A theremin implemented using two Arduino boards: one for computing the audio, and one for processing the inputs.

Two ultrasonic sensors are used to detect hand movements. One hand controls the the note within a scale, the other hand controls the octave of that scale.

The audio signal is produced by mapping the distance read from the ultrasonic sensor and mapping those distances to a lookup table that contains specific note frequencies.
Different lookup tables are used to mimic the sounds of different instruments.

A 4x4 keypad is used to select different instruments.

The pdf contains demonstrations and documentation.

My responsibilities included processing inputs and building the apparatus.
