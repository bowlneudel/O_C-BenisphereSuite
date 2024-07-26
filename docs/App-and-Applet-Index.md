Jump to the lists of [[Full Screen Apps|App-and-Applet-Index#full-screen-apps]] or [[Hemisphere Applets|App-and-Applet-Index#hemisphere-applets]], also organized [[by function|App-and-Applet-Index#apps-and-applets-by-function]]

## Full Screen Apps
Full screen apps in Phazerville are mostly from the original Ornament and Crime firmware, with a few notable additions ([[Calibr8or]], [[Scenes]], and [Passencore](https://llllllll.co/t/passencore-chord-ornament-music-theory-crime/45925)). Each of the full screen apps takes advantage of all inputs and outputs in their own way, which is usually configurable.

Not all the apps can fit at once on Teensy 3.2 hardware, but you can use the [default set](https://github.com/djphazer/O_C-Phazerville/releases) or [choose your own selection](https://github.com/djphazer/O_C-Phazerville/discussions/38) with a custom build.

* Hemisphere - 2 [Applets](#applets) at a time
* [[Calibr8or]] - Quad performance quantizer with pitch tracking calibration
* [[Scenes|Scenes]] - Macro CV switch / crossfader
* [[Captain MIDI]] - Configurable CV-to-MIDI and MIDI-to-CV interface
* [[Pong]] - It's Pong!
* [[Enigma]] – Sequencer of shift registers (Turing Machines)
* [The Darkest Timeline](https://github.com/Chysn/O_C-HemisphereSuite/wiki/The-Darkest-Timeline-2.0) - Parallel universe sequencer
* [Neural Net](https://github.com/Chysn/O_C-HemisphereSuite/wiki/Neural-Net) - 6 Neuron logic processor
* [Scale Editor](https://github.com/Chysn/O_C-HemisphereSuite/wiki/Scale-Editor) - Edit and save microtonal scales
* [Waveform Editor](https://github.com/Chysn/O_C-HemisphereSuite/wiki/Waveform-Editor) - Edit and save vector waveforms (for [[LFOs|VectorLFO]], [[envelopes|VectorEG]], [[one-shots|VectorMod]], and [[phase scrubbing|VectorMorph]])
* [CopierMaschine](https://ornament-and-cri.me/user-manual-v1_3/#anchor-copiermaschine) - Quantizing Analogue Shift Register
* [Harrington 1200](https://ornament-and-cri.me/user-manual-v1_3/#anchor-harrington-1200) - Neo-Riemannian transformations for triad chord progressions
* [Automatonnetz](https://ornament-and-cri.me/user-manual-v1_3/#anchor-automatonnetz) - Neo-Riemannian transformations on a 5x5 matrix sequence!
* [Quantermain](https://ornament-and-cri.me/user-manual-v1_3/#anchor-quantermain) - Quad quantizer
* [Meta-Q](https://ornament-and-cri.me/user-manual-v1_3/#anchor-meta-q) - Dual sequenced quantizer
* [Quadraturia](https://ornament-and-cri.me/user-manual-v1_3/#anchor-quadraturia) - Quadrature wavetable LFO
* [Low-rents](https://ornament-and-cri.me/user-manual-v1_3/#anchor-low-rents) - Lorenz attractor
* [Piqued](https://ornament-and-cri.me/user-manual-v1_3/#anchor-piqued) - Quad envelope generator
* [Sequins](https://ornament-and-cri.me/user-manual-v1_3/#anchor-sequins) - Basic dual-channel sequancer
* [Dialectic Ping Pong](https://ornament-and-cri.me/user-manual-v1_3/#anchor-dialectic-ping-pong) - Quad bouncing ball envelopes
* [Viznutcracker, sweet!](https://ornament-and-cri.me/user-manual-v1_3/#anchor-viznutcracker-sweet) - Quad Bytebeat generator
* [Acid Curds](https://ornament-and-cri.me/user-manual-v1_3/#anchor-acid-curds) - Quad 8-step chord progression sequencer
* [References](https://ornament-and-cri.me/user-manual-v1_3/#anchor-references) - Tuning utility
* [Passencore](https://llllllll.co/t/passencore-chord-ornament-music-theory-crime/45925) - Generate a chord progression from LFOs
* [Backup / Restore](https://github.com/Chysn/O_C-HemisphereSuite/wiki/Backup-and-Restore) - Transfer app and calibration data as SysEx
* [[Setup / About|Setup-About]] - Check your version, change encoder directions, adjust display/DAC/ADC, screen off time

***

## Hemisphere Applets
Hemisphere splits the screen into two halves: each side available to load any one of a long list of applets. On o_C hardware with inputs and outputs arranged in 3 rows of 4 columns (i.e. most 8hp units), the I/O corresponding to an applet should be in line with that half of the display (i.e. paired into 1+2/A+B and 3+4/C+D).

If you're coming from any of the other Hemisphere forks, note that many of the applets have been upgraded for additional flexibility and functionality, and several are brand new.

* [[ADSR|ADSR-EG]] - Dual attack / decay / sustain / release envelope
* [[AD EG|AD-EG]] - Attack / decay envelope
* [[ASR]] - Analog Shift Register
* [[AttenOff]] - Attenu-vert, Offset, and Mix inputs (now with +/-200% range, mix control)
* [[Binary Counter|Binary-Counter]] - 1 bit per input, output as voltage
* [[BootsNCat]] - Noisy percussion
* [[Brancher]] - Bernoulli gate
* [[BugCrack]] - Sick drums, don't bug out
* [[Burst]] - Rapid trigger / ratchet generator
* [[Button2]] - 2 simple triggers or latching gates. Press the button!
* [[Calculate]] - Dual Min, Max, Sum, Diff, Mean, Random, S&H
* [[Calibr8]] - 2-channel, mini Calibr8or for v/Oct correction
* [[Carpeggio]] - X-Y table of pitches from a scale/chord
* [[Chordinate]] - Quantizer with scale mask, outputs root + scale degree (from qiemem)
* [[ClockDivider]] - Dual complex clock pulse multiplier / divider.
* [[ClockSkip|Clock-Skipper]] - Randomly skip pulses
* [[Compare]] - Basic comparator
* [[Cumulus]] - Bit accumulator, inspired by Schlappi Nibbler
* [[CVRec|CV-Recorder]] - Record / smooth / playback CV up to 384 steps on 2 tracks
* [[DivSeq]] - Two sequences of clock dividers
* [[DrumMap]] - Clone of Mutable Instruments Grids
* [[DualQuant|Dual-Quantizer]] - Basic 2-channel quantizer with sample and hold
* [[DualTM]] - Highly configurable pair of Turing Machine shift registers (replacement for ShiftReg/TM)
* [[Ebb & LFO|Ebb-&-LFO]] - clone of Mutable Instruments Tides; oscillator / LFO with CV-controllable waveshape, slope, V/Oct, folding
* [[EnigmaJr|Enigma-Jr.]] - compact player of curated shift registers
* [[EnvFollow|Envelope-Follower]] - follows or ducks based on incoming audio
  - added Speed control
* [[EuclidX]] - Euclidean pattern generator (replacement for [AnnularFusion](https://github.com/Chysn/O_C-HemisphereSuite/wiki/Annular-Fusion-Euclidean-Drummer))
* [[GameOfLife]] - experimental cellular automaton modulation source
* [[GateDelay|Gate-Delay]] - simple gate delay
* [[GatedVCA|Gated-VCA]] - simple VCA
* [[Dr. LoFi|Dr.-LoFi]] - super crunchy PCM delay line with bitcrushing and rate reduction
  - based on [LoFi Tape](https://github.com/Chysn/O_C-HemisphereSuite/wiki/LoFi-Tape) and Dr. Crusher
* [[Logic]] - AND / OR / XOR / NAND / NOR / XNOR
* [[LowerRenz]] - orbiting particles, chaotic modulation source
* [[Metronome]] - internal clock tempo control + multiplier output
* [[MIDI In|MIDI-Input]] - from USB to CV
* [[MIDI Out|MIDI-Out]] - from CV to USB
* [[MixerBal|Mixer-Balance]] - basic CV mixer
* [[MultiScale]] - like ScaleDuet, but with 4 scale masks
* [[Palimpsest|Palimpsest-Accent-Sequencer]] - accent sequencer
* [[Pigeons]] - dual Fibonacci-style melody generator
* [[PolyDiv]] - four concurrent clock dividers with assignable outputs
* [[ProbDiv]] - stochastic trigger generator
* [[ProbMeloD]] - stochastic melody generator
* [[ResetClk|Reset-Clock]] - rapidly advance a sequencer to the desired step (from [pkyme](https://github.com/pkyme/O_C-HemisphereSuite/tree/reset-additions))
* [[RndWalk|Random-Walk]] - clocked random walk CV generator (from [adegani](https://github.com/adegani/O_C-HemisphereSuite))
* [[RunglBook]] - chaotic shift-register modulation
* [[ScaleDuet|Scale-Duet-Quantizer]] - 2 quantizers with independent scale masks
* [[Schmitt|Schmitt-Trigger]] - Dual comparator with low and high threshold
* [[Scope]] - tiny CV scope / voltmeter / BPM counter
  - expanded with X-Y view
* [[Seq32]] - compact 32-step sequencer using Sequins pattern storage
* [[SequenceX]] - up to 8 steps of CV, quantized to semitones
* [[ShiftGate]] - dual shift register-based gate/trigger sequencer
* [[Shredder]] - clone of Mimetic Digitalis
* [[Shuffle]] - it don't mean a thing if it ain't got that swing
  - triplets added on 2nd output
* [[Slew]] - Dual channel slew: one linear, the other exponential
* [[Squanch]] - advanced quantizer with transpose
* [[Stairs]] - stepped CV
* [[Strum]] - the ultimate arpeggiator (pairs well with Rings)
* [[Switch]] - CV switch & toggle
* [[SwitchSeq|Switch-Seq]] - multiple Seq32 patterns running in parallel
* [[TB-3PO]] - a brilliant 303-style sequencer
* [[TL Neuron|Threshold-Logic-Neuron]] - clever logic gate
* [[Trending]] - rising / falling / moving / steady / state change / value change
* [[TrigSeq|Trigger-Sequencer]] - two 8-step trigger sequences
* [[TrigSeq16|Trigger-Sequencer-16]] - one 16-step trigger sequence
* [[Tuner]] - oscillator frequency detector
* [[VectorEG]] - Dual envelopes from a library of bipolar and unipolar shapes (customizable with the [Waveform Editor](https://github.com/Chysn/O_C-HemisphereSuite/wiki/Waveform-Editor))
* [[VectorLFO]] - Dual LFOs from a library of bipolar and unipolar shapes
* [[VectorMod]] - Dual One-shots from a library of bipolar and unipolar shapes
* [[VectorMorph]] - Dual (or linked) phase scrubbing along a library of bipolar and unipolar shapes
* [[Voltage]] - static output CV

***

## Apps and Applets by Function

| Function                 | Hemisphere Applets                                                                                                                                                      | Full Screen Apps                                                                         |
| ------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
|**Accent Sequencer**       | [[Palimpsest\|Palimpsest-Accent-Sequencer]]                                                                                                                                                        |                                                                                          |
| **Analog Logic**            | [[Calculate]]                                                                                                                                                         |                                                                                          |
| **Clock Modulator**          | [[ClockDivider]], [[ClockSkip\|Clock-Skipper]], [[DivSeq]], [[Metronome]], [[PolyDiv]], [[ProbDiv]], [[ResetClk\|Reset-Clock]], [[Shuffle]]                                         |                                                                                          |
| **CV Recorder**              | [[ASR]], [[CVRec\|CV-Recorder]]                                                                                                                                                 |                                                                                          |
| **Digital Logic**            | [[Binary Counter]], [[Compare]], [[Cumulus]], [[Logic]], [[Schmitt\|Schmitt-Trigger]], [[TL Neuron\|Threshold-Logic-Neuron]], [[Trending]]                                                         | [Neural Net](https://github.com/Chysn/O_C-HemisphereSuite/wiki/Neural-Net)                                                                             |
| **Delay**                    | [[GateDelay\|Gate-Delay]]                                                                                                                                                         |                                                                                          |
| **Drums / Synth Voice**                    | [[BootsNCat]], [[BugCrack]]                                                                                                                                         | [Viznutcracker, sweet!](https://ornament-and-cri.me/user-manual-v1_3/#anchor-viznutcracker-sweet)                                                                  |
| **Effect**                   | [[Dr. LoFi]]                                                                                                                                                          |                                                                                          |
| **Envelope Follower**        | [[EnvFollow\|Envelope-Follower]], [[Slew]]                                                                                                                                             |                                                                                          |
| **Envelope Generator**       | [[ADSR\|ADSR-EG]], [[AD EG]], [[VectorEG]]                                                                                                                                 | [Piqued](https://ornament-and-cri.me/user-manual-v1_3/#anchor-piqued), [Dialectic Ping Pong](https://ornament-and-cri.me/user-manual-v1_3/#anchor-dialectic-ping-pong)                                                          |
| **LFO**                      | [[Ebb & LFO]], [[LowerRenz]], [[VectorLFO]]                                                                                                                       | [Quadraturia](https://ornament-and-cri.me/user-manual-v1_3/#anchor-quadraturia)                                                                            |
| **MIDI**                     | [[MIDI In\|MIDI-Input]], [[MIDI Out]] _(See also: [[Auto MIDI Output\|Hemisphere-General-Settings#auto-midi-output]])_                                                                                                                                           | [[Captain MIDI]]                                                                           |
| **Mixer**                    | [[MixerBal\|Mixer-Balance]]                                                                                                                                                          |                                                                                          |
| **Modulation Source**        | [[GameOfLife]], [[Stairs]], [[VectorMod]], [[VectorMorph]]                                                                                                                          | [Low-rents](https://ornament-and-cri.me/user-manual-v1_3/#anchor-low-rents), [[Pong]]                                                                                   |
| **Performance Utility**      | [[Button2]]                                                                                                                                                           |  [[Scenes]]                                                                                        |
| **Pitch Sequencer**          | [[Carpeggio]], [[DualTM]], [[EnigmaJr\|Enigma-Jr.]], [[Pigeons]], [[ProbMeloD]], [[Seq32]], [[SequenceX]], [[Shredder]], [[Strum]], [[SwitchSeq\|Switch-Seq]], [[TB-3PO]] | [[Enigma]], [The Darkest Timeline](https://github.com/Chysn/O_C-HemisphereSuite/wiki/The-Darkest-Timeline-2.0), [Automatonnetz](https://ornament-and-cri.me/user-manual-v1_3/#anchor-automatonnetz), [Sequins](https://ornament-and-cri.me/user-manual-v1_3/#anchor-sequins), [Acid Curds](https://ornament-and-cri.me/user-manual-v1_3/#anchor-acid-curds), [Passencore](https://llllllll.co/t/passencore-chord-ornament-music-theory-crime/45925) | 
| **Quantizer**               | [[Calibr8]], [[Chordinate]], [[DualQuant\|Dual-Quantizer]], [[MultiScale]], [[ScaleDuet\|Scale-Duet-Quantizer]], [[Squanch]]                                                                      | [[Calibr8or]], [Harrington 1200](https://ornament-and-cri.me/user-manual-v1_3/#anchor-harrington-1200), [Quantermain](https://ornament-and-cri.me/user-manual-v1_3/#anchor-quantermain), [Meta-Q](https://ornament-and-cri.me/user-manual-v1_3/#anchor-meta-q)                                  |
| **Random / Chaos**           | [[Brancher]], [[LowerRenz]], [[ProbDiv]], [[ProbMeloD]], [[RndWalk\|Random-Walk]], [[Shredder]]                                                        | [Low-rents](https://ornament-and-cri.me/user-manual-v1_3/#anchor-low-rents)                                                                              |
| **Shift Register**           | [[ASR]], [[DualTM]], [[EnigmaJr\|Enigma-Jr.]], [[RunglBook]], [[ShiftGate]]                                                                                               | [[Enigma]], [CopierMaschine](https://ornament-and-cri.me/user-manual-v1_3/#anchor-copiermaschine)                                                               |
| **Switch**                   | [[Switch]], [[SwitchSeq\|Switch-Seq]]                                                                                                                                         | [[Scenes]]                                                                                    |
| **Trigger / Gate Sequencer** | [[DivSeq]], [[DrumMap]], [[EuclidX]], [[PolyDiv]], [[ProbDiv]], [[Seq32]], [[ShiftGate]], [[TrigSeq\|Trigger-Sequencer]], [[TrigSeq16\|Trigger-Sequencer-16]]                                 |                                                                                  |
| **VCA**                      | [[GatedVCA\|Gated-VCA]]                                                                                                                                                          |                                                                                          |
| **Voltage Utility**          | [[AttenOff]], [[Calculate]], [[Calibr8]], [[Scope]], [[Slew]], [[Stairs]], [[Switch]], [[Tuner]], [[Trending]], [[Voltage]]                         | [[Calibr8or]], [References](https://ornament-and-cri.me/user-manual-v1_3/#anchor-references)                