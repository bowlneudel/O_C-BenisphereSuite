# Strum

![Screenshot 2024-06-13 15-42-30](https://github.com/djphazer/O_C-Phazerville/assets/109086194/7ea4f903-3781-4eb6-a241-edd6b426f2ed)

Strum is an arpeggiator. It generates fast sequences of up to six pitches from a selected scale, along with trigger pulses. This is ideal for achieving chord tones with voices with round-robin polyphony, like Rings, but also nice for slower arp sequences - spacing goes up to 500ms.

Incoming triggers intuitively run through the sequence either forward or backward. If retriggered in the middle of the sequence, it will immediately jump to the next step, allowing unique grooves to emerge from tempo-synced pulses.

### I/O

|        | 1/3 | 2/4 |
| ------ | :-: | :-: |
| TRIG   | Strum Up | Strum Down |
| CV INs | Chord Root Transpose | Spacing (default) /<br>Quantizer select |
| OUTs   | Pitch CV | Trigger Pulse |

### UI Parameters
* Quantizer select - AuxButton to edit
* Spacing - AuxButton to switch CV2 modulation destination
* Length
* Edit Intervals 1-6

### Credits
Authored by qiemem, with mods by djphazer
