# electric dharma wheels

version 0.41  
matthew davidson  
April 04, 2011  

## four encoders

each encoder is a FM 'voice'

all voices share the same basic synthesis parameters

each encoder primarily determines when a note will be triggered
a note is triggered when LED passes 12 o'clock
what note is triggered is determined by the probabilities in the note pool
clockwise and counterclockwise rotation have separate pools.

each encoder stores four states - the values can be seen on right hand side
the current state is indicated by a bank name on the left hand side
state can be changed one of two ways, the default method uses the button on encoder 0
if the buttons menu is set to individual, each encoder button advances the state for that encoder
if the buttons menu is set to grouped, encoder 0 button changes all states, this frees up the
other buttons to do other things, like encoder button 1 enters edit mode which allows you to edit
FM index, etc button 3 advances a programmed score.
