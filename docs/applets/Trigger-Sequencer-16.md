![Screenshot 2024-06-13 15-48-15](https://github.com/djphazer/O_C-Phazerville/assets/109086194/e34a515b-1855-4d6f-8021-12e0ed2ffc5a)

**TrigSeq16** is a 16-step trigger sequencer. It's visually and functionally similar to [Trigger Sequencer](Trigger-Sequencer), except it's 1x16 instead of 2x8. Solid steps send triggers on Out A/C; empty steps send triggers on Out B/D.

## I/O

|        | 1/3 | 2/4 |
| ------ | :-: | :-: |
| TRIG   | Clock    | Reset    |
| CV INs | Swap channels if > 3v    | Offset position for Reset (square outline)    |
| OUTs   | Trigger output    | NOT Trigger output    |


## UI Parameters
* Edit sequence (cursor selects 4 steps)
- Length

### Step Editing

The cursor appears over four steps at a time. Turning the encoder selects a binary representation of the bit pattern. Each quarter of the sequence has sixteen possible values. That is, turning the encoder clockwise will cycle through

* (silence)
* ---X
* --X-
* --XX
* -X--
* -X-X
* -XX-
* -XXX
* X---
* X--X
* X-X-
* X-XX
* XX--
* XX-X
* XXX-
* XXXX
