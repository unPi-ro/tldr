# dmenu

> Meniu dinamic.
> Creează un meniu dintr-o intrare de text cu fiecare element pe o linie nouă.
> Mai multe informații: <https://manned.org/dmenu>.

- Afișează un meniu cu ieșirea comenzii `ls`:

`{{ls}} | dmenu`

- Afișează un meniu cu elemente personalizate separate de o linie nouă (`\n`):

`echo -e "{{red}}\n{{green}}\n{{blue}}" | dmenu`

- Permiteți utilizatorului să aleagă între mai multe elemente și să îl salveze pe cel selectat într-un fișier:

`echo -e "{{red}}\n{{green}}\n{{blue}}" | dmenu > {{color.txt}}`

- Lansarea dmenu pe un anumit monitor:

`ls | dmenu -m {{1}}`

- Afișează dmenu în partea de jos a ecranului:

`ls | dmenu -b`
