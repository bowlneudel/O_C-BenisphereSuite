# SequenceX

![Screenshot 2024-06-13 15-35-12](https://github.com/djphazer/O_C-Phazerville/assets/109086194/ee475e5b-1e4b-4e65-8da5-157fd4206858)

[Video demo](https://youtu.be/zsqAbNRgHJI)

**SequenceX** is an 8-step semitone-quantized sequencer, adapted from the original Sequence5 applet. It now features bipolar output values and CV-triggered randomization.

### I/O

|        | 1/3 | 2/4 |
| ------ | :-: | :-: |
| TRIG   | Clock | Reset |
| CV INs | Transpose | >1V = Randomize sequence |
| OUTs   | Pitch | BOC Trigger |


### UI Controls
* Encoder: select/edit each step; scroll further for mute toggles
* AuxButton: mute/unmute selected step

Each step is a semitone increment over a bipolar 5-octave (60-note) range. To change the length of the sequence, you can mute one or more steps by moving the slider all the way down until the slider handle disappears, or using the mute toggles. The clock will skip muted steps.

### Credits
Adapted from [Sequence5](https://github.com/Chysn/O_C-HemisphereSuite/wiki/Sequence5) by Chysn
