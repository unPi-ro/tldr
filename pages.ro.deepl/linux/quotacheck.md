# quotacheck

> Scanarea unui sistem de fișiere pentru utilizarea discului; crearea, verificarea și repararea fișierelor de cote.
> Cel mai bine este să rulați verificarea cotelor cu cotele dezactivate pentru a preveni deteriorarea sau pierderea fișierelor de cote.

- Verificați cotele pe toate sistemele de fișiere non-NFS montate:

`sudo quotacheck --all`

- Forțați verificarea chiar dacă sunt activate cotele (acest lucru poate cauza deteriorarea sau pierderea fișierelor de cote):

`sudo quotacheck --force {{mountpoint}}`

- Verifică cotele pe un anumit sistem de fișiere în modul de depanare:

`sudo quotacheck --debug {{mountpoint}}`

- Verifică cotele pe un anumit sistem de fișiere, afișând progresul:

`sudo quotacheck --verbose {{mountpoint}}`

- Verificați cotele de utilizatori:

`sudo quotacheck --user {{user}} {{mountpoint}}`

- Verificați cotele de grup:

`sudo quotacheck --group {{group}} {{mountpoint}}`
