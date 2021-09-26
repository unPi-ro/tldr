# conky

> Monitor de sistem ușor pentru X.
> Mai multe informații: <https://github.com/brndnmtthws/conky>.

- Lansare cu configurația implicită, încorporată:

`conky`

- Creați o nouă configurație implicită:

`conky -C > ~/.conkyrc`

- Lansează Conky cu un fișier de configurare dat:

`conky -c {{path/to/config}}`

- Pornește în fundal (daemonizare):

`conky -d`

- Aliniați Conky pe desktop:

`conky -a {{{top,bottom,middle}_{left,right,middle}}}`

- Faceți o pauză de 5 secunde la pornire înainte de lansare:

`conky -p {{5}}`
