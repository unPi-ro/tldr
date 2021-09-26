# i3lock

> Un locker de ecran simplu construit pentru managerul de ferestre i3.
> Mai multe informații: <https://i3wm.org/i3lock>.

- Ecran de blocare cu un fundal de culoare simplă (format rrggbb):

`i3lock -c {{0000ff}}`

- Blocarea ecranului pe un fundal PNG:

`i3lock -i {{path/to/picture.png}}`

- Dezactivați indicatorul de deblocare (elimină feedback-ul la apăsarea tastei):

`i3lock -u`

- Afișează indicatorul mouse-ului în loc să-l ascundă ("default" pentru indicatorul implicit, "win" pentru un indicator MS Windows):

`i3lock -p {{default|win}}`

- Blocați ecranul pe un fundal PNG afișat pe mai multe monitoare, cu pointerul mouse-ului activat:

`i3lock -i {{path/to/picture.png}} -p {{default|win}} -t`
