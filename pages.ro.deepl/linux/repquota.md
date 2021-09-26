# repquota

> Afișează un rezumat al cotelor de fișiere existente pentru un sistem de fișiere.

- Raportează statisticile pentru toate cotele utilizate:

`sudo repquota -all`

- Raportați statisticile privind cotele pentru toți utilizatorii, chiar și pentru cei care nu utilizează nici o cotă:

`sudo repquota -v {{filesystem}}`

- Raportați cotele numai pentru utilizatori:

`repquota --user {{filesystem}}`

- Raport privind cotele numai pentru grupuri:

`sudo repquota --group {{filesystem}}`

- Raportați cotele și limitele utilizate într-un format care poate fi citit de către om:

`sudo repquota --human-readable {{filesystem}}`

- Raportați toate cotele pentru utilizatori și grupuri într-un format ușor de citit:

`sudo repquota -augs`
