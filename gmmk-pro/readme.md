# GMMK Pro Layout

## To Do:
- UCIEA
- UCIEA (GCSV)
- Hands Down

## Shortcuts

### Switch Keyboard Layouts

| Shortcut   | Layout             | Layer |
|------------|--------------------|-------|
| Fn + Space | QWERTY             | 0     |
| Fn + 1     | Engram             | 1     |
| Fn + 2     | UCIEA              | 3     |
| Fn + 3     | UCIEA (GCSV)       | 4     |
| Fn + 4     | Hands Down Nue Sym | 5     |

### Misc. Functions

| Shortcut   | Function                   |
|------------|----------------------------|
| Fn + \     | Reset (flash)              |
| Fn + Home  | Insert                     |
| Fn + Esc   | Sleep                      |
| Fn + F1    | My Computer                |
| Fn + F2    | Browser Home               |
| Fn + F3    | Calculator                 |
| Fn + F4    | Media Player               |
| Fn + F10   | Previous Track             |
| Fn + F11   | Play / Pause               |
| Fn + F12   | Next Track                 |
| Fn + Del   | Print Screen               |
| Fn + `     | Toggle RGB                 |
| Fn + w     | Increase Brightness        |
| Fn + s     | Reduce Brightness          |
| Fn + n     | Toggle N-Key Rollover      |
| Fn + Up    | Next RGB Mode              |
| Fn + Down  | Previous RGB Mode          |
| Fn + Left  | Increase RGB Effect Speed  |
| Fn + Right | Decreasse RGB Effect Speed |

## Layers

### Layer 0: QWERTY

Contains a default QWERTY layout.
Ideally a separate layout would be the base layer, so I don't have a duplicate QWERTY layer for keyboard shortcuts.

```text
Esc   F1 F2 F3 F4 F5  F6 F7 F8 F9 F12   Del    Mute
`     1  2  3  4  5   6  7  8  9  0 - = Bspc   Home
Tab   q  w  e  r  t   y  u  i  o  p [ ] \      End
Caps  a  s  d  f  g   h  j  k  l  ; '   Enter  PgUp
Shift    z  x  c  v   b  n  m  ,  . / Shift Up PgDn
Ctrl  Gui Alt   Space   Alt Fn Ctrl  Left Down Right
```

#### Special Keys

The left Ctrl & left Gui keys will always ensure that the QWERTY overlay layer is activated, at the same time as activating their appropriate key.
This ensures that shortcuts won't change with layout.

The Fn key will always activate the Function layer.

### Layer 3: UCIEA
### Layer 4: UCIEA (GCSV)
### Layer 5: Hands Down Nue Sym
### Layer 6: QWERTY Overlay

This layer is used in combination with the left Ctrl & Gui keys in order to overlay QWERTY

### Layer 7: Functions

This layer is used to overlay standard function keys over all layouts.
 

## Misc.

### Keys Layer
Copy & paste the following to add a new keys-only layout:
```json

```

### Keys & Numbers Layer

Copy & paste the following to add a new keys layout:

```json
[
    "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS",  "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS",
    "KC_TRNS", "KC_1",    "KC_2",    "KC_3",    "KC_4",    "KC_5",    "KC_6",    "KC_7",     "KC_8",    "KC_9",    "KC_0",    "KC_MINS", "KC_EQL",  "KC_TRNS", "KC_TRNS",
    "KC_TRNS", "KC_Q",    "KC_W",    "KC_E",    "KC_R",    "KC_T",    "KC_Y",    "KC_U",     "KC_I",    "KC_O",    "KC_P",    "KC_LBRC", "KC_RBRC", "KC_TRNS", "KC_TRNS",
    "KC_TRNS", "KC_A",    "KC_S",    "KC_D",    "KC_F",    "KC_G",    "KC_H",    "KC_J",     "KC_K",    "KC_L",    "KC_SCLN", "KC_QUOT",            "KC_TRNS", "KC_TRNS",
    "KC_TRNS", "KC_Z",    "KC_X",    "KC_C",    "KC_V",    "KC_B",    "KC_N",    "KC_M",     "KC_COMM", "KC_DOT",  "KC_SLSH", "KC_TRNS",            "KC_TRNS", "KC_TRNS",
    "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS",                                                         "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS"
],
```

### Transparent Layer

Copy and paste the following block for a new transparent layer:

```json
[
	"KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS",
	"KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS",
	"KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS",
	"KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS",            "KC_TRNS", "KC_TRNS",
	"KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS",            "KC_TRNS", "KC_TRNS",
	"KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS",                                                        "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS"
],
```


### Engram

Once I have a better solution for the custom symbol keys + sshift problem, think about adding this back in.
Could add some custom macros etc. as seen [here](https://github.com/qmk/qmk_firmware/pull/16545/files): 

```json
[
    "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS",
    "KC_LBRC", "KC_1",    "KC_2",    "KC_3",    "KC_4",    "KC_5",    "KC_6",    "KC_7",    "KC_8",    "KC_9",    "KC_0",    "KC_RBRC", "KC_SLSH", "KC_TRNS", "KC_TRNS",
    "KC_TRNS", "KC_B",    "KC_Y",    "KC_O",    "KC_U",    "KC_QUOT", "KC_DQUO", "KC_L",    "KC_D",    "KC_W",    "KC_V",    "KC_Z",    "KC_HASH", "KC_AT",   "KC_TRNS",
    "KC_TRNS", "KC_C",    "KC_I",    "KC_E",    "KC_A",    "KC_COMM", "KC_DOT",  "KC_H",    "KC_T",    "KC_S",    "KC_N",    "KC_Q",               "KC_TRNS", "KC_TRNS",
    "LM(2, MOD_LSFT)",   "KC_G",    "KC_X",    "KC_J",    "KC_K",    "KC_MINS", "KC_QUES", "KC_R",    "KC_M",    "KC_F",    "KC_P",    "KC_TRNS",            "KC_TRNS", "KC_TRNS",
    "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS",                                                        "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS"
],
[
    "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS",
    "KC_TRNS", "KC_PIPE", "KC_EQL",  "KC_TILD", "KC_PLUS", "KC_LT",   "KC_GT",   "KC_CIRC", "KC_AMPR", "KC_PERC", "KC_ASTR", "KC_TRNS", "KC_BSLS", "KC_TRNS", "KC_TRNS",
    "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_LPRN", "KC_RPRN", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS",
    "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_SCLN", "KC_COLN", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS",            "KC_TRNS", "KC_TRNS",
    "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_UNDS", "KC_EXLM", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS",            "KC_TRNS", "KC_TRNS",
    "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS",                                                        "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS", "KC_TRNS"
],
```
