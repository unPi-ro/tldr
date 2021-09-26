# netselect-apt

> Creați un fișier `sources.list` pentru o oglindă Debian cu cea mai mică latență.
> Mai multe informații: <https://manpages.debian.org/buster/netselect-apt/netselect-apt.1.html>.

- Creați `sources.list` folosind serverul cu cea mai mică latență:

`sudo netselect-apt`

- Specificați ramura Debian, stabilă este utilizată în mod implicit:

`sudo netselect-apt {{testing}}`

- Includeți o secțiune neliberă:

`sudo netselect-apt --non-free`

- Specificați o țară pentru căutarea în lista de oglinzi:

`sudo netselect-apt -c {{India}}`
