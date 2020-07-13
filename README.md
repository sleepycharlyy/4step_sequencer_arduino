# 4 Step Sequencer Arduino

## About

my first little arduino nano project! uwu

its a 4 step sequencer for my arduino that uses 7 potentiometers.
four for every step (to manipulate the pitch of each step) and three to manipulate the bpm, waveform and pitch.
i used four leds (corresponding to each step) that blink to every beat. 
and one button to turn it on and off.

my code is a bit janky and its my first time programming with an arduino so don't expect to much.
but it seems to work haha.

## Circuit

![Circuit Schematic](circuit_schematic.png?raw=true)

### Pins

 *  connect led1 to pin d2, led2 to pin d3, led3 to pin d4, led4 to pin d5
 *  connect on off button to pin d6
 *  connect speaker to pin d9
 *  connect pitch potentometers to a0 to a3
 *  connect octave potentometer to a4
 *  connect bpm potentometer to a5
 *  connect pattern potentometer to a6
 *  connect waveform potentometer to a7

## Libraries

 * [cmasenas/SineWave](https://github.com/cmasenas/SineWave) 
 * [PaulStoffregen/TimerOne](https://github.com/PaulStoffregen/TimerOne)
 
 ## Credits
 
 I took [constantinorizzuti/step-sequencer](https://create.arduino.cc/projecthub/costantinorizzuti/step-sequencer-19a9d7) source code as a starting point and 
 moved forward from there.
