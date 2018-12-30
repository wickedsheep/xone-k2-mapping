# a&h xone:k2 traktor mapping

opinionated (no effects) 4-channel traktor midi mapping for allen & heath xone:k2.

## xone-k2-solo.tsi

use when no external mixer.

decks:

```
deck a - 1 (the leftmost)
deck b - 2
deck c - 3
deck d - 4 (the rightmost)
```

latching layers:

```
layer 1 - loop, eq, volume and deck controls
layer 2 - tbd
layer 3 - hotcue control
```

### layer 1 (red)

```
  a    b    c    d
+---------------------+
|                     |
| +oo+ +oo+ +oo+ +oo+ | select loop size (turn)
| +oo+ +oo+ +oo+ +oo+ | toggle loop on/off (press)
|                     |
| +--+ +--+ +--+ +--+ |
| |OO| |OO| |OO| |OO| | high frequency adjust
| +--+ +--+ +--+ +--+ |
|                     |
| +--+ +--+ +--+ +--+ | 
| +--+ +--+ +--+ +--+ | toggle high frequency on/off
|                     |
| +--+ +--+ +--+ +--+ |
| |OO| |OO| |OO| |OO| | mid frequency adjust
| +--+ +--+ +--+ +--+ |
|                     |
| +--+ +--+ +--+ +--+ |
| +--+ +--+ +--+ +--+ | toggle mid frequency on/off
|                     |
| +--+ +--+ +--+ +--+ |
| |OO| |OO| |OO| |OO| | low frequency adjust
| +--+ +--+ +--+ +--+ |
|                     |
| +--+ +--+ +--+ +--+ | 
| +--+ +--+ +--+ +--+ | toggle low frequency on/off
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
| +--+ +--+ +--+ +--+ | volume inc/dec
|                     |
| +--+ +--+ +--+ +--+ |
| +--+ +--+ +--+ +--+ | toggle monitor cue on/off
|                     |
| +--+ +--+ +--+ +--+ |
| +--+ +--+ +--+ +--+ | toggle sync on/off
|                     |
| +--+ +--+ +--+ +--+ |
| +--+ +--+ +--+ +--+ | toggle play/pause
|                     |
| +--+ +--+ +--+ +--+ |
| +--+ +--+ +--+ +--+ | load selected track
|                     |
| +--+ +oo+ +oo+ +--+ |
| |  | +oo+ +oo+ |  | |
| +--+           +--+ |
|  l1   r1   r2       |
+---------------------+

l1 - toggle between layers
r1 - navigate tree (turn)
r1 - expand collapse tree (press)
r2 - navigate files (turn)
r2 - toggle browser only mode on/off (press)
```

### layer 3 (green)

```
+---------------------+
|                     |
| +--+ +--+ +--+ +--+ |
| +--+ +--+ +--+ +--+ | 
| f1   f2   f3   f4   |
| +--+ +--+ +--+ +--+ |
| +--+ +--+ +--+ +--+ | select hotcue (1-4)
| c1   c2   c3   c4   |
| +--+ +--+ +--+ +--+ |
| +--+ +--+ +--+ +--+ | select hotcue (5-8)
| c5   c6   c7   c8   |
| +--+ +--+ +--+ +--+ |
| +--+ +--+ +--+ +--+ |
|                     |
+---------------------+

f1 - focus deck A
f2 - focus deck B
f3 - focus deck C
f4 - focus deck D
```

