# swapon

> Activează dispozitivul sau fișierul pentru schimb.

- Obțineți informații despre swap:

`swapon -s`

- Activează o anumită partiție swap:

`swapon {{/dev/sdb7}}`

- Activează un anumit fișier swap:

`swapon {{path/to/file}}`

- Activați toate zonele swap:

`swapon -a`

- Activați schimbul după eticheta unui dispozitiv sau fișier:

`swapon -L {{swap1}}`
