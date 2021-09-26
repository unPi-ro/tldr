# setxkbmap

> Setați tastatura utilizând extensia X Keyboard Extension.

- Setați tastatura în franceză AZERTY:

`setxkbmap {{fr}}`

- Setați mai multe modele de tastatură, variantele acestora și opțiunea de comutare:

`setxkbmap -layout {{us,de}} -variant {{,qwerty}} -option {{'grp:alt_caps_toggle'}}`

- Cereți ajutor:

`setxkbmap -help`

- Lista tuturor machetelor:

`localectl list-x11-keymap-layouts`

- Lista variantelor pentru machetă:

`localectl list-x11-keymap-variants {{de}}`

- Enumeră opțiunile de comutare disponibile:

`localectl list-x11-keymap-options | grep grp:`
