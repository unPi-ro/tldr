# findmnt

> Găsiți sistemul de fișiere.
> Mai multe informații: <https://manned.org/findmnt>.

- Listează toate sistemele de fișiere montate:

`findmnt`

- Căutați un dispozitiv:

`findmnt {{/dev/sdb1}}`

- Căutați un punct de montare:

`findmnt {{/}}`

- Găsiți sisteme de fișiere de un anumit tip:

`findmnt -t {{ext4}}`

- Găsește sisteme de fișiere cu o anumită etichetă:

`findmnt LABEL={{BigStorage}}`
