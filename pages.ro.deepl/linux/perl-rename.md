# rename

> Redenumiți mai multe fișiere.
> NOTĂ: această pagină se referă la comanda din pachetul `perl-rename` Arch Linux.

- Redenumirea fișierelor utilizând o expresie regulată comună Perl (înlocuiți "foo" cu "bar" oriunde se găsește):

`rename {{'s/foo/bar/'}} {{*}}`

- Dry-run - afișează ce redenumiri ar avea loc fără a le efectua:

`rename -n {{'s/foo/bar/'}} {{*}}`

- Forțați redenumirea chiar dacă operațiunea ar elimina fișierele de destinație existente:

`rename -f {{'s/foo/bar/'}} {{*}}`

- Conversia numelor de fișiere în minuscule (utilizați `-f` în sistemele de fișiere care nu țin cont de majuscule pentru a preveni erorile "există deja"):

`rename 'y/A-Z/a-z/' {{*}}`

- Înlocuiți spațiile albe cu caractere de subliniere:

`rename 's/\s+/_/g' {{*}}`
