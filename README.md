# A&H Xone:K2 Traktor mapping

Opinionated (no effects) 4-channel Traktor MIDI mapping for Allen & Heath Xone:K2.

## xone-k2-solo.tsi

Use this when no external mixer.

Decks:

```
Deck A - 1 (the leftmost)
Deck B - 2
Deck C - 3
Deck D - 4 (the rightmost)
```

Latching layers:

```
Layer 1 - Loop, EQ, volume and deck controls
Layer 2 - TBD
Layer 3 - Hotcue control
```

```
  A    B    C    D
+---------------------+
|                     |
| +oo+ +oo+ +oo+ +oo+ | Select loop size (turn)
| +oo+ +oo+ +oo+ +oo+ | Toggle loop on/off (press)
|                     |
| +--+ +--+ +--+ +--+ |
| |OO| |OO| |OO| |OO| | High frequency adjust
| +--+ +--+ +--+ +--+ |
|                     |
| +--+ +--+ +--+ +--+ | 
| +--+ +--+ +--+ +--+ | Toggle high frequency on/off
|                     |
| +--+ +--+ +--+ +--+ |
| |OO| |OO| |OO| |OO| | Mid frequency adjust
| +--+ +--+ +--+ +--+ |
|                     |
| +--+ +--+ +--+ +--+ |
| +--+ +--+ +--+ +--+ | Toggle mid frequency on/off
|                     |
| +--+ +--+ +--+ +--+ |
| |OO| |OO| |OO| |OO| | Low frequency adjust
| +--+ +--+ +--+ +--+ |
|                     |
| +--+ +--+ +--+ +--+ | 
| +--+ +--+ +--+ +--+ | Toggle low frequency on/off
|                     |
| +--+ +--+ +--+ +--+ |
| |  | |  | |  | |  | |
| |  | |  | |  | |  | |
| |++| |  | |  | |  | |
| |++| |  | |  | |  | |
| |++| |  | |  | |  | |
| |  | |  | |  | |++| |
| |  | |  | |  | |++| |
| |  | |  | |  | |++| |
| |  | |  | |  | |  | |
| |  | |  | |  | |  | |
| |  | |++| |++| |  | |
| |  | |++| |++| |  | |
| |  | |++| |++| |  | |
| |  | |  | |  | |  | |
| +--+ +--+ +--+ +--+ | Volume inc/dec
|                     |
| +--+ +--+ +--+ +--+ |
| +--+ +--+ +--+ +--+ | Toggle monitor cue on/off
|                     |
| +--+ +--+ +--+ +--+ |
| +--+ +--+ +--+ +--+ | Toggle sync on/off
|                     |
| +--+ +--+ +--+ +--+ |
| +--+ +--+ +--+ +--+ | Toggle play/pause
|                     |
| +--+ +--+ +--+ +--+ |
| +--+ +--+ +--+ +--+ | Load selected track
|                     |
| +--+ +oo+ +oo+ +--+ |
| |L1| +oo+ +oo+ |E1| |
| +--+  R1   R2  +--+ |
|                     |
+---------------------+

L1 - Toggle between layers
R1 - Navigate tree (turn)
R1 - Expand collapse tree (press)
R2 - Navigate files (turn)
R2 - Toggle browser only mode on/off (press)
```

