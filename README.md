# 4step-sequencer-arduino
my first little arduino nano project

its a 4 step sequencer for my arduino with 7 potentiometers 
4 for every step (pitch) and 3 to manipulate the overall bpm, waveform and pitch.
i used 4 leds that blink over the 4 pots every time a step is played.
and one button to turn it on and off.

my code is a bit janky and its my first time programming with an arduino so dont expect to much.
but it seems to work haha.

# circuit
 *  circuit:
 *  
 *  connect led1 to pin d2, led2 to pin d3, led3 to pin d4, led4 to pin d5
 *  connect speaker to pin d9
 *  connect pitch potentometers to a0 to a3
 *  connect octave potentometer to a4
 *  connect bpm potentometer to a5
 *  connect pattern potentometer to a6
 *  connect wave potentometer to a7
 *  connect on off button to pin 6
