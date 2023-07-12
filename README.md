# Voice-Transmission
In this project, Voice Transmission (Voice Manipulation), the focus is using data input/output and
processing which includes reading in data from a microphone, processing that data, and writing
the processed data out to an amplifier and subsequently to a speaker.

OBJECTIVE: Without changing sample rate, Implement a DSP based player and recorder using the STM32CubeIDE 1.7.0 and
breadboard setup involving push buttons, LEDs, resistors, and H743ZI2 board (32-bit microcontroller). Data processing
in this lab includes adding reverb and changing the playback speed.
The specifications implemented in the lab includes a sampling rate of 8 kilo samples per second
(Ksps), the first button following a protocol for recording and erasing audio, the second button
creating a reverb of the data, the third button speeding up and delaying the data, and the fourth
button slowing down the data.

Reverb was achieved by coding FIFO shift register logic to create the 70ms delay desired in the spec.
SpeedUp was achieved by 

https://www.youtube.com/watch?v=_gPnLU-jgM4&ab_channel=stock
