# add-apt-repository

> Gestionează definițiile depozitului apt.
> Mai multe informații: <https://manned.org/apt-add-repository>.

- Adăugați un nou depozit apt:

`add-apt-repository {{repository_spec}}`

- Îndepărtați un depozit apt:

`add-apt-repository --remove {{repository_spec}}`

- Actualizați memoria cache a pachetelor după adăugarea unui depozit:

`add-apt-repository --update {{repository_spec}}`

- Activați pachetele sursă:

`add-apt-repository --enable-source {{repository_spec}}`
