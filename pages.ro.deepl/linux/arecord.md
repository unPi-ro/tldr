# arecord

> Înregistrator de sunet pentru driverul plăcii de sunet ALSA.
> Mai multe informații: <https://manned.org/arecord>.

- Înregistrați un fragment la calitate "CD" (terminați cu Ctrl-C când ați terminat):

`arecord -vv --format=cd {{path/to/file.wav}}`

- Înregistrați un fragment la calitate "CD", cu o durată fixă de 10 secunde:

`arecord -vv --format=cd --duration={{10}} {{path/to/file.wav}}`

- Înregistrați un fragment și salvați-l ca MP3 (terminați cu Ctrl-C când ați terminat):

`arecord -vv --format=cd --file-type raw | lame -r - {{path/to/file.mp3}}`

- Enumerați toate plăcile de sunet și dispozitivele audio digitale:

`arecord --list-devices`

- Permiteți o interfață interactivă (de exemplu, utilizați bara de spațiu sau tasta Enter pentru a reda sau a pune pauză):

`arecord --interactive`
