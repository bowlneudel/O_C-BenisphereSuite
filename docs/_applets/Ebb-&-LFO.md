---
layout: default
---
# Ebb & LFO

![Screenshot 2024-06-13 14-46-32](https://github.com/djphazer/O_C-Phazerville/assets/109086194/608edfcd-3f89-4fc4-82f1-d46b90b65c19)

This is a single Tides-like oscillator with two outputs. Both inputs and outputs are configurable. The outputs are visualized on the screen.

It can function like a looping envelope generator or an audio-rate oscillator, with modulatable parameters for morphing the contour. Triggers to input 1/3 may function as tap tempo. "One Shot" mode will output a single waveform cycle and stop, much like the AD envelope mode on Tides (use Reset to retrigger).

### I/O

|        |                          1/3                          |    2/4     |
| ------ | :---------------------------------------------------: | :--------: |
| TRIG   |                         Clock                         |   Reset    |
| CV INs | Assignable<br>(Freq / Slope / Shape / Fold) | Assignable<br>(Amp / Slope / Shape / Fold) |
| OUTs   |                      Waveform A                       | Waveform B |

### CV Inputs & UI Parameters
These are also the corresponding on-screen parameters.
Each input is assigned to one of:
* Level / **Am**plitude (CV2 only)
* Frequency (**Hz**) (CV1 only) - tracks V/Oct for audio-rate operation
* **Sl**ope - skews the waveform (much like the deprecated [SkewedLFO](https://github.com/Chysn/O_C-HemisphereSuite/wiki/Skewed-LFO) applet)
* **Sh**ape - morphs between various curved segment combos
* **Fo**ld - wavefolder!

Lastly, there is a UI toggle for _One Shot_ mode.

### Outputs
Each output can be one of:
* **Un**ipolar
* **Bi**polar
* Gate **Hi**gh - starts low, goes high at the end of the Attack phase
* Gate **Lo**w - starts high, goes low at the end of the Attack phase

# Credits
The original applet and backend _tideslite_ algorithm were written by **qiemem** (Bryan Head). In Phazerville from v1.6
