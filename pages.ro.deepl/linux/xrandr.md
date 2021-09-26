# xrandr

> Stabiliți dimensiunea, orientarea și/sau reflectarea ieșirilor pentru un ecran.

- Afișează starea actuală a sistemului (ecrane cunoscute, rezoluții, ...):

`xrandr --query`

- Dezactivați ieșirile deconectate și activați-le pe cele conectate cu setările implicite:

`xrandr --auto`

- Modificați rezoluția și frecvența de actualizare a DisplayPort 1 la 1920x1080, 60Hz:

`xrandr --output {{DP1}} --mode {{1920x1080}} --rate {{60}}`

- Setați rezoluția HDMI2 la 1280x1024 și plasați-o în dreapta lui DP1:

`xrandr --output {{HDMI2}} --mode {{1280x1024}} --right-of {{DP1}}`

- Dezactivați ieșirea VGA1:

`xrandr --output {{VGA1}} --off`

- Setați luminozitatea pentru LVDS1 la 50%:

`xrandr --output {{LVDS1}} --brightness {{0.5}}`

- A se vedea afișarea informațiilor hardware:

`xrandr -q`
