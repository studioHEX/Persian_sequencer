# Persian_sequencer

A Max4Live device that does MIDI-sequencing according to 13th century Persian rythms based on Euclidean patterns. The engine of the device is based on Philip Meyer his awesome video on Euclidean Patterns in MAX. This is the first M4L device that I produced and probably has some bugs or hickups.

The engine, as said, is based on Philip Meyer his work: https://www.youtube.com/watch?v=G3uaqN7Glx8&pp=ygUXZXVjbGlkZWFuIHJ5dGhtIG1heCBtc3A%3D
The euclidean patterns are derived from the paper written by Godfried Toussaint: http://cgm.cs.mcgill.ca/~godfried/publications/banff.pdf 
The use of notes and other details are derived from the paper written by Arash Pandi: Persian Music Scalator 

#**bug and workaround**
The device won't record MIDI-notes on the track it is loaded on, which I cannot find out why. The workaround would be to load it onto a MIDI-track and import the MIDI onto another MIDI-track with your plug-in or instrument loaded onto. 

#**Future developments**
13th Century Persian music has a very intricate system of transitions and movements into different segments of the musical piece. I aim to build in a system that will guide you through all these transitions so you can let the sequencer run and it will automate the structure of the song for you.
