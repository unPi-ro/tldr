# apt-add-repository

> Gestionează definițiile depozitului apt.
> Mai multe informații: <https://manpages.debian.org/latest/software-properties-common/apt-add-repository.1.html>.

- Adăugați un nou depozit apt:

`apt-add-repository {{repository_spec}}`

- Îndepărtați un depozit apt:

`apt-add-repository --remove {{repository_spec}}`

- Actualizați memoria cache a pachetelor după adăugarea unui depozit:

`apt-add-repository --update {{repository_spec}}`

- Activați pachetele sursă:

`apt-add-repository --enable-source {{repository_spec}}`
