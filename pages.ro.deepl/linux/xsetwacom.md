# xsetwacom

> Instrument în linie de comandă pentru a modifica setările pentru tabletele cu stilou Wacom în timpul execuției.

- Enumeră toate dispozitivele Wacom disponibile. Numele dispozitivului se află în prima coloană:

`xsetwacom list`

- Setați zona Wacom pe un anumit ecran. Obțineți numele ecranului cu `xrandr`:

`xsetwacom set "{{device_name}}" MapToOutput {{screen}}`

- Setați modul la modul relativ (ca un mouse) sau absolut (ca un stilou):

`xsetwacom set "{{device_name}}" Mode "{{Relative|Absolute}}"`

- Rotește intrarea (util pentru Tablet-PC atunci când se rotește ecranul) cu 0|90|180|270 grade față de rotația "naturală":

`xsetwacom set "{{device_name}}" Rotate {{none|half|cw|ccw}}`

- Setați butonul să funcționeze numai atunci când vârful stiloului atinge tableta:

`xsetwacom set "{{device_name}}" TabletPCButton "on"`
