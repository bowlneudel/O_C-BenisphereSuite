Jump to the lists of [Full Screen Apps](App-and-Applet-Index#full-screen-apps) or [Hemisphere Applets](App-and-Applet-Index#hemisphere-applets), also organized [by function](App-and-Applet-Index#apps-and-applets-by-function)

## Full Screen Apps
Full screen apps in Phazerville are mostly from the original Ornament and Crime firmware, with a few notable additions ([Calibr8or](Calibr8or), [Scenes](Scenes), and [Passencore](https://llllllll.co/t/passencore-chord-ornament-music-theory-crime/45925)). Each of the full screen apps takes advantage of all inputs and outputs in their own way, which is usually configurable.

Not all the apps can fit at once on Teensy 3.2 hardware, but you can use the [default set](https://github.com/djphazer/O_C-Phazerville/releases) or [choose your own selection](https://github.com/djphazer/O_C-Phazerville/discussions/38) with a custom build.

* Hemisphere - 2 [Applets](#applets) at a time
* [Calibr8or](Calibr8or) - Quad performance quantizer with pitch tracking calibration
* [Scenes](Scenes) - Macro CV switch / crossfader
* [Captain MIDI](Captain-MIDI) - Configurable CV-to-MIDI and MIDI-to-CV interface
* [Pong](Pong) - It's Pong!
* [Enigma](Enigma) – Sequencer of shift registers (Turing Machines)
* [The Darkest Timeline](https://github.com/Chysn/O_C-HemisphereSuite/wiki/The-Darkest-Timeline-2.0) - Parallel universe sequencer
* [Neural Net](https://github.com/Chysn/O_C-HemisphereSuite/wiki/Neural-Net) - 6 Neuron logic processor
* [Scale Editor](https://github.com/Chysn/O_C-HemisphereSuite/wiki/Scale-Editor) - Edit and save microtonal scales
* [Waveform Editor](https://github.com/Chysn/O_C-HemisphereSuite/wiki/Waveform-Editor) - Edit and save vector waveforms (for [LFOs](VectorLFO), [envelopes](VectorEG), [one-shots](VectorMod), and [phase scrubbing](VectorMorph))
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
* [Setup / About](Setup-About) - Check your version, change encoder directions, adjust display/DAC/ADC, screen off time

***

## Hemisphere Applets
Hemisphere splits the screen into two halves: each side available to load any one of a long list of applets. On o_C hardware with inputs and outputs arranged in 3 rows of 4 columns (i.e. most 8hp units), the I/O corresponding to an applet should be in line with that half of the display (i.e. paired into 1+2/A+B and 3+4/C+D).

If you're coming from any of the other Hemisphere forks, note that many of the applets have been upgraded for additional flexibility and functionality, and several are brand new.

* [ADSR](ADSR-EG) - Dual attack / decay / sustain / release envelope
* [AD EG](AD-EG) - Attack / decay envelope
* [ASR](ASR) - Analog Shift Register
* [AttenOff](AttenOff) - Attenu-vert, Offset, and Mix inputs (now with +/-200% range, mix control)
* [Binary Counter](Binary-Counter) - 1 bit per input, output as voltage
* [BootsNCat](BootsNCat) - Noisy percussion
* [Brancher](Brancher) - Bernoulli gate
* [BugCrack](BugCrack) - Sick drums, don't bug out
* [Burst](Burst) - Rapid trigger / ratchet generator
* [Button2](Button2) - 2 simple triggers or latching gates. Press the button!
* [Calculate](Calculate) - Dual Min, Max, Sum, Diff, Mean, Random, S&H
* [Calibr8](Calibr8) - 2-channel, mini Calibr8or for v/Oct correction
* [Carpeggio](Carpeggio) - X-Y table of pitches from a scale/chord
* [Chordinate](Chordinate) - Quantizer with scale mask, outputs root + scale degree (from qiemem)
* [ClockDivider](ClockDivider) - Dual complex clock pulse multiplier / divider.
* [ClockSkip](Clock-Skipper) - Randomly skip pulses
* [Compare](Compare) - Basic comparator
* [Cumulus](Cumulus) - Bit accumulator, inspired by Schlappi Nibbler
* [CVRec](CV-Recorder) - Record / smooth / playback CV up to 384 steps on 2 tracks
* [DivSeq](DivSeq) - Two sequences of clock dividers
* [DrumMap](DrumMap) - Clone of Mutable Instruments Grids
* [DualQuant](Dual-Quantizer) - Basic 2-channel quantizer with sample and hold
* [DualTM](DualTM) - Highly configurable pair of Turing Machine shift registers (replacement for ShiftReg/TM)
* [Ebb & LFO](Ebb-&-LFO) - clone of Mutable Instruments Tides; oscillator / LFO with CV-controllable waveshape, slope, V/Oct, folding
* [EnigmaJr](Enigma-Jr.) - compact player of curated shift registers
* [EnvFollow](Envelope-Follower) - follows or ducks based on incoming audio
  - added Speed control
* [EuclidX](EuclidX) - Euclidean pattern generator (replacement for [AnnularFusion](https://github.com/Chysn/O_C-HemisphereSuite/wiki/Annular-Fusion-Euclidean-Drummer))
* [GameOfLife](GameOfLife) - experimental cellular automaton modulation source
* [GateDelay](Gate-Delay) - simple gate delay
* [GatedVCA](Gated-VCA) - simple VCA
* [Dr. LoFi](Dr.-LoFi) - super crunchy PCM delay line with bitcrushing and rate reduction
  - based on [LoFi Tape](https://github.com/Chysn/O_C-HemisphereSuite/wiki/LoFi-Tape) and Dr. Crusher
* [Logic](Logic) - AND / OR / XOR / NAND / NOR / XNOR
* [LowerRenz](LowerRenz) - orbiting particles, chaotic modulation source
* [Metronome](Metronome) - internal clock tempo control + multiplier output
* [MIDI In](MIDI-Input) - from USB to CV
* [MIDI Out](MIDI-Out) - from CV to USB
* [MixerBal](Mixer-Balance) - basic CV mixer
* [MultiScale](MultiScale) - like ScaleDuet, but with 4 scale masks
* [Palimpsest](Palimpsest-Accent-Sequencer) - accent sequencer
* [Pigeons](Pigeons) - dual Fibonacci-style melody generator
* [PolyDiv](PolyDiv) - four concurrent clock dividers with assignable outputs
* [ProbDiv](ProbDiv) - stochastic trigger generator
* [ProbMeloD](ProbMeloD) - stochastic melody generator
* [ResetClk](Reset-Clock) - rapidly advance a sequencer to the desired step (from [pkyme](https://github.com/pkyme/O_C-HemisphereSuite/tree/reset-additions))
* [RndWalk](Random-Walk) - clocked random walk CV generator (from [adegani](https://github.com/adegani/O_C-HemisphereSuite))
* [RunglBook](RunglBook) - chaotic shift-register modulation
* [ScaleDuet](Scale-Duet-Quantizer) - 2 quantizers with independent scale masks
* [Schmitt](Schmitt-Trigger) - Dual comparator with low and high threshold
* [Scope](Scope) - tiny CV scope / voltmeter / BPM counter
  - expanded with X-Y view
* [Seq32](Seq32) - compact 32-step sequencer using Sequins pattern storage
* [SequenceX](SequenceX) - up to 8 steps of CV, quantized to semitones
* [ShiftGate](ShiftGate) - dual shift register-based gate/trigger sequencer
* [Shredder](Shredder) - clone of Mimetic Digitalis
* [Shuffle](Shuffle) - it don't mean a thing if it ain't got that swing
  - triplets added on 2nd output
* [Slew](Slew) - Dual channel slew: one linear, the other exponential
* [Squanch](Squanch) - advanced quantizer with transpose
* [Stairs](Stairs) - stepped CV
* [Strum](Strum) - the ultimate arpeggiator (pairs well with Rings)
* [Switch](Switch) - CV switch & toggle
* [SwitchSeq](Switch-Seq) - multiple Seq32 patterns running in parallel
* [TB-3PO) - a brilliant 303-style sequencer
* [TL Neuron](Threshold-Logic-Neuron) - clever logic gate
* [Trending](Trending) - rising / falling / moving / steady / state change / value change
* [TrigSeq](Trigger-Sequencer) - two 8-step trigger sequences
* [TrigSeq16](Trigger-Sequencer-16) - one 16-step trigger sequence
* [Tuner](Tuner) - oscillator frequency detector
* [VectorEG](VectorEG) - Dual envelopes from a library of bipolar and unipolar shapes (customizable with the [Waveform Editor](https://github.com/Chysn/O_C-HemisphereSuite/wiki/Waveform-Editor))
* [VectorLFO](VectorLFO) - Dual LFOs from a library of bipolar and unipolar shapes
* [VectorMod](VectorMod) - Dual One-shots from a library of bipolar and unipolar shapes
* [VectorMorph](VectorMorph) - Dual (or linked) phase scrubbing along a library of bipolar and unipolar shapes
* [Voltage](Voltage) - static output CV

***

## Apps and Applets by Function

| Function                 | Hemisphere Applets                                                                                                                                                      | Full Screen Apps                                                                         |
| ------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
|**Accent Sequencer**       | [Palimpsest](Palimpsest-Accent-Sequencer)                                                                                                                                                        |                                                                                          |
| **Analog Logic**            | [Calculate](Calculate)                                                                                                                                                         |                                                                                          |
| **Clock Modulator**          | [ClockDivider](ClockDivider), [ClockSkip](Clock-Skipper), [DivSeq](DivSeq), [Metronome](Metronome), [PolyDiv](PolyDiv), [ProbDiv](ProbDiv), [ResetClk](Reset-Clock), [Shuffle](Shuffle)                                         |                                                                                          |
| **CV Recorder**              | [ASR](ASR), [CVRec](CV-Recorder)                                                                                                                                                 |                                                                                          |
| **Digital Logic**            | [Binary Counter](Binary-Counter), [Compare](Compare), [Cumulus](Cumulus), [Logic](Logic), [Schmitt](Schmitt-Trigger), [TL Neuron](Threshold-Logic-Neuron), [Trending](Trending)                                                         | [Neural Net](https://github.com/Chysn/O_C-HemisphereSuite/wiki/Neural-Net)                                                                             |
| **Delay**                    | [GateDelay](Gate-Delay)                                                                                                                                                         |                                                                                          |
| **Drums / Synth Voice**                    | [BootsNCat](BootsNCat), [BugCrack](BugCrack)                                                                                                                                         | [Viznutcracker, sweet!](https://ornament-and-cri.me/user-manual-v1_3/#anchor-viznutcracker-sweet)                                                                  |
| **Effect**                   | [Dr. LoFi](Dr. LoFi)                                                                                                                                                          |                                                                                          |
| **Envelope Follower**        | [EnvFollow](Envelope-Follower), [Slew](Slew)                                                                                                                                             |                                                                                          |
| **Envelope Generator**       | [ADSR](ADSR-EG), [AD EG](AD-EG), [VectorEG](VectorEG)                                                                                                                                 | [Piqued](https://ornament-and-cri.me/user-manual-v1_3/#anchor-piqued), [Dialectic Ping Pong](https://ornament-and-cri.me/user-manual-v1_3/#anchor-dialectic-ping-pong)                                                          |
| **LFO**                      | [Ebb & LFO](Ebb-&-LFO), [LowerRenz](LowerRenz), [VectorLFO](VectorLFO)                                                                                                                       | [Quadraturia](https://ornament-and-cri.me/user-manual-v1_3/#anchor-quadraturia)                                                                            |
| **MIDI**                     | [MIDI In](MIDI-Input), [MIDI Out](MIDI-Out) _(See also: [Auto MIDI Output](Hemisphere-General-Settings#auto-midi-output))_                                                                                                                                           | [Captain MIDI](Captain MIDI)                                                                           |
| **Mixer**                    | [MixerBal](Mixer-Balance)                                                                                                                                                          |                                                                                          |
| **Modulation Source**        | [GameOfLife](GameOfLife), [Stairs](Stairs), [VectorMod](VectorMod), [VectorMorph](VectorMorph)                                                                                                                          | [Low-rents](https://ornament-and-cri.me/user-manual-v1_3/#anchor-low-rents), [Pong](Pong)                                                                                   |
| **Performance Utility**      | [Button2](Button2)                                                                                                                                                           |  [Scenes](Scenes)                                                                                        |
| **Pitch Sequencer**          | [Carpeggio](Carpeggio), [DualTM](DualTM), [EnigmaJr](Enigma-Jr.), [Pigeons](Pigeons), [ProbMeloD](ProbMeloD), [Seq32](Seq32), [SequenceX](SequenceX), [Shredder](Shredder), [Strum](Strum), [SwitchSeq](Switch-Seq), [TB-3PO) | [Enigma](Enigma), [The Darkest Timeline](https://github.com/Chysn/O_C-HemisphereSuite/wiki/The-Darkest-Timeline-2.0), [Automatonnetz](https://ornament-and-cri.me/user-manual-v1_3/#anchor-automatonnetz), [Sequins](https://ornament-and-cri.me/user-manual-v1_3/#anchor-sequins), [Acid Curds](https://ornament-and-cri.me/user-manual-v1_3/#anchor-acid-curds), [Passencore](https://llllllll.co/t/passencore-chord-ornament-music-theory-crime/45925) | 
| **Quantizer**               | [Calibr8](Calibr8), [Chordinate](Chordinate), [DualQuant](Dual-Quantizer), [MultiScale](MultiScale), [ScaleDuet](Scale-Duet-Quantizer), [Squanch](Squanch)                                                                      | [Calibr8or](Calibr8or), [Harrington 1200](https://ornament-and-cri.me/user-manual-v1_3/#anchor-harrington-1200), [Quantermain](https://ornament-and-cri.me/user-manual-v1_3/#anchor-quantermain), [Meta-Q](https://ornament-and-cri.me/user-manual-v1_3/#anchor-meta-q)                                  |
| **Random / Chaos**           | [Brancher](Brancher), [LowerRenz](LowerRenz), [ProbDiv](ProbDiv), [ProbMeloD](ProbMeloD), [RndWalk](Random-Walk), [Shredder](Shredder)                                                        | [Low-rents](https://ornament-and-cri.me/user-manual-v1_3/#anchor-low-rents)                                                                              |
| **Shift Register**           | [ASR](ASR), [DualTM](DualTM), [EnigmaJr](Enigma-Jr.), [RunglBook](RunglBook), [ShiftGate](ShiftGate)                                                                                               | [Enigma](Enigma), [CopierMaschine](https://ornament-and-cri.me/user-manual-v1_3/#anchor-copiermaschine)                                                               |
| **Switch**                   | [Switch](Switch), [SwitchSeq](Switch-Seq)                                                                                                                                         | [Scenes](Scenes)                                                                                    |
| **Trigger / Gate Sequencer** | [DivSeq](DivSeq), [DrumMap](DrumMap), [EuclidX](EuclidX), [PolyDiv](PolyDiv), [ProbDiv](ProbDiv), [Seq32](Seq32), [ShiftGate](ShiftGate), [TrigSeq](Trigger-Sequencer), [TrigSeq16](Trigger-Sequencer-16)                                 |                                                                                  |
| **VCA**                      | [GatedVCA](Gated-VCA)                                                                                                                                                          |                                                                                          |
| **Voltage Utility**          | [AttenOff](AttenOff), [Calculate](Calculate), [Calibr8](Calibr8), [Scope](Scope), [Slew](Slew), [Stairs](Stairs), [Switch](Switch), [Tuner](Tuner), [Trending](Trending), [Voltage](Voltage)                         | [Calibr8or](Calibr8or), [References](https://ornament-and-cri.me/user-manual-v1_3/#anchor-references)                
