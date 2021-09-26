# swapoff

> Dezactivează dispozitivul sau fișierul pentru schimb.

- Dezactivează o anumită partiție swap:

`swapoff {{/dev/sdb7}}`

- Dezactivează un anumit fișier swap:

`swapoff {{path/to/file}}`

- Dezactivați toate zonele swap:

`swapoff -a`

- Dezactivează swap-ul în funcție de eticheta unui dispozitiv sau a unui fișier:

`swapoff -L {{swap1}}`
