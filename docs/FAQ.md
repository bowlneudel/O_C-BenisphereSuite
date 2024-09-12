# Frequently Asked Questions

1. [Input & output mapping](#io)
2. [Clock sync](#clock)
3. [Quantizer engines](#quantizers)
4. [Calibration](#calibration)
5. [Encoder direction](#encoders)

## Q: How do the physical input and output jacks relate to the apps / applets? <a id='io'>

A: Within Hemisphere, any of the physical input jacks (trigger/gate and CV) may be flexibly [mapped](Hemisphere-Input-Mapping) to any of 4 virtual (software) inputs of each applet. The output jacks of each applet are hardcoded to A/B (Left Hemisphere) & C/D (Right Hemisphere), and these outputs may also be routed to the virtual inputs.

Using the [Input mapping screen](Hemisphere-Input-Mapping), you can configure applets to share Triggers or CV sources, directly route the output of one applet as the input of another, or disable (mute) a physical input jack.

**NOTE: Some full screen apps (those other than the original stock apps) will respect the current input mapping saved within Hemisphere. Within full screen apps, the name displayed for a given input corresponds to its _software_ destination (i.e. its position within the Input Mapping Config)**

<img src="images/Default_Map.png" alt="Default Input Mapping">

The input mapping above reflects the traditional default behaviour of O_C: Left and Right Hemispheres with independent digital and CV inputs, corresponding to their physical jack locations on most 8hp hardware.

<img src="images/Alt_Map.png" alt="Alternative Input Mapping">

In the example above, the input mapping reflects an alternative behaviour:
- Both Left and Right Hemispheres map TR2 to their 1st virtual digital input (which in many cases will be used for clock)
- The 2nd virtual digital input is disabled for the Left Hemisphere, whereas the Right Hemisphere is using the 1st output of the Left Hemisphere (Output A)
- Both Hemispheres share control voltage inputs CV1 and CV2.

You may map physical Digital inputs to virtual CV inputs and vice versa.

<img src="images/Help_Screen.png" alt="Help Screen">

Within Hemisphere, each applet's help screen will dynamically label the physical input and output jacks currently mapped to each parameter. Trigger inputs may also be remapped via the [Clock Setup screen](Clock-Setup)


## Q: How does clock sync work? <a id='clock'>

A: See the [Clock Setup screen](Clock-Setup)

An external clock may be used to set tempo in Hemisphere, either from:
- Triggers sent to TR1 (hardcoded to the physical input)
- MIDI input clock

When the clock is armed, the next trigger at TR1 will start the clock. MIDI run/stop messages will be respected.

While playing, Hemisphere will automatically detect the incoming tempo, and stop automatically when pulses cease.

The `Sync` parameter is PPQN (pulses per quarter note), or how many ticks of an external clock tick correspond to an internal clock tick.

After BPM detection, triggers are passed to applets according to their corresponding clock multiplication or division, with `Swing` (if enabled – % parameter is editable under `BPM`)

To disable external clock sync, set `Sync` to 0

**NOTE: when clock pulses are recieved at both TR1 and MIDI, the result is simply mixed, potentially resulting in an unstable BPM detection**