# xbacklight

> Utilitar pentru a regla luminozitatea luminii de fundal cu ajutorul extensiei RandR.
> Mai multe informații: <https://gitlab.freedesktop.org/xorg/app/xbacklight>.

- Obține luminozitatea curentă a ecranului sub formă de procent:

`xbacklight`

- Setați luminozitatea ecranului la 40%:

`xbacklight -set {{40}}`

- Creșteți luminozitatea curentă cu 25%:

`xbacklight -inc {{25}}`

- Reduceți luminozitatea actuală cu 75%:

`xbacklight -dec {{75}}`

- Creșteți iluminarea de fundal la 100%, în 60 de secunde (valoarea este exprimată în ms), folosind 60 de pași:

`xbacklight -set {{100}} -time {{60000}} -steps {{60}}`
