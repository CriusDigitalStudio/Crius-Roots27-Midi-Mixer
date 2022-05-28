# Crius-Roots27-Midi-Mixer
This is a USB MIDI controller that consists of 27 linear Potentiometers(18 rotary Pots + 9 Slide Pots) and can be used as a MIDI Mixer for your DAW.
![Untitled_1 1 6](https://user-images.githubusercontent.com/63908995/170828311-2a7bc07a-d649-43da-9e15-8424e77300e2.png)
To connect all the 27 Potentiometers with the Arduino Pro Micro , I used the HC4067 Analog multiplexer.
You can edit the code and hook up , up to 32 Potentiometers with th 2 x HC4067 multiplexers.

![27 POTS 2xMUX HC4067 MIDI MIXER](https://user-images.githubusercontent.com/63908995/170824971-54c1601a-421f-4807-9b33-d28498aa016c.png)

Here I connected all the Ground Pins together and also all the 5V Pins together so the circuit uses less cables on the breadboard.

![27 POTS 2xMUX MIDI MIXER GND TO GND 5V to 5V](https://user-images.githubusercontent.com/63908995/170824980-58286f10-5172-47fc-bb8b-289e9db08d15.png)

