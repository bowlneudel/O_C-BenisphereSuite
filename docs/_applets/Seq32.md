# Seq32

![Screenshot 2024-06-13 15-33-26](https://github.com/djphazer/O_C-Phazerville/assets/109086194/3801854c-017b-4c87-87c3-613b872401cd)

The **Seq32** applet reinterprets the 8 pattern storage slots from the original **Sequins** app as 32-step note sequences. (This will corrupt your Sequins patterns, if you have any!)

Each step has a bipolar range of -32 to +31 (scale degrees) and can be Muted or Accented. Accent currently means a longer gate + glide. Mute means no gate is sent and the Pitch output doesn't change.

_**Important:**_ In addition to storing applet settings in a Preset, a manual [EEPROM Save](Saving-State) is necessary to save changes to the global patterns!

### I/O

|        |         1/3        |        2/4          |
| ------ | :----------------: | :-----------------: |
| TRIG   |        Clock       |       Reset         |
| CV INs |   Sequence Select  |     Transpose       |
| OUTs   |        Pitch       |    Gate/Trigger     |

### UI Parameters
* Pattern select #1-8
* Length, per pattern
* Record mode
* Quantizer scale settings (popup editor)
* Transpose
* Edit notes

### AuxButton Actions
With certain parameters highlighted for editing, the select button will execute a secondary action:
* Pattern# - Clear pattern
* Length - Randomize current pattern completely
* Transpose - Randomize pitches of current pattern, using transpose as the range

### Step Editing
![Screenshot 2024-06-13 15-34-27](https://github.com/djphazer/O_C-Phazerville/assets/109086194/4581ae5d-541a-46ba-857e-bc54101c317a)

Use the encoder to move the cursor to a step, and push to toggle editing the note value. While editing, use the AuxButton to toggle Mute. Double-click to toggle Accent, indicated by a solid square.

### Record mode
When the small record icon is engaged, the cursor is locked and a crude CV recording mechanism is active. When a clock is received, the sequencer advances, CV1 is captured as pitch, and CV2 is measured as Mute/Unmute/Accent (threshold at 0.5v for Unmute, and 2v for Accent).

It works, but it's a little clumsy because recording pitch/gate with the inputs conflicts with normal operation. This might get reworked in the future.
