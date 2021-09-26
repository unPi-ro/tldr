# rename

> Redenumiți mai multe fișiere.
> NOTĂ: această pagină se referă la comanda din pachetul `util-linux`.
> Pentru versiunea Perl, consultați `file-rename` sau `perl-rename`.
> Atenție: Această comandă nu are nicio protecție și va suprascrie fișierele fără a fi solicitată.

- Redenumirea fișierelor folosind substituții simple (înlocuiți "foo" cu "bar" ori de câte ori găsiți):

`rename {{foo}} {{bar}} {{*}}`

- Dry-run - afișează ce redenumiri ar avea loc fără a le efectua:

`rename -vn {{foo}} {{bar}} {{*}}`

- Nu suprascrieți fișierele existente:

`rename -o {{foo}} {{bar}} {{*}}`

- Modificați extensiile de fișiere:

`rename {{.ext}} {{.bak}} {{*.ext}}`

- Adaugă "foo" la toate numele de fișiere din directorul curent:

`rename {{''}} {{'foo'}} {{*}}`

- Redenumiți un grup de fișiere din ce în ce mai numerotate, adăugând zero la numerele de până la 3 cifre:

`rename {{foo}} {{foo00}} {{foo?}} && rename {{foo}} {{foo0}} {{foo??}}`
