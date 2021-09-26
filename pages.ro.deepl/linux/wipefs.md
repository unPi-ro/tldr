# wipefs

> Ștergeți semnăturile sistemului de fișiere, raid sau ale tabelei de partiții de pe un dispozitiv.

- Afișează semnăturile pentru dispozitivul specificat:

`sudo wipefs {{/dev/sdX}}`

- Șterge toate semnăturile disponibile pentru dispozitivul specificat:

`sudo wipefs --all {{/dev/sdX}}`

- Efectuați o funcționare în regim de probă:

`sudo wipefs --all --no-act {{/dev/sdX}}`

- Forțează ștergerea, chiar dacă sistemul de fișiere este montat:

`sudo wipefs --all --force {{/dev/sdX}}`
