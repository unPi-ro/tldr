# playerctl

> Utilitar pentru a controla diferite playere media.
> Mai multe informații: <https://github.com/altdesktop/playerctl>.

- Comutați redarea:

`playerctl play-pause`

- Următoarea media:

`playerctl next`

- Media anterioare:

`playerctl previous`

- Enumerați toți jucătorii:

`playerctl --list-all`

- Trimiteți o comandă unui anumit jucător:

`playerctl --player={{player_name}} {{command}}`

- Trimiteți o comandă tuturor jucătorilor:

`playerctl --all-players {{command}}`

- Spectacolul se joacă acum:

`playerctl metadata --format "Now playing: {{artist}} - {{album}} - {{title}}"`
