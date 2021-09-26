# pkgfile

> Instrument pentru căutarea fișierelor din pachetele din depozitele oficiale pe sistemele bazate pe arhive.
> Vezi și `pacman files`, care descrie utilizarea lui `pacman --files`.
> Mai multe informații: <https://man.archlinux.org/man/extra/pkgfile/pkgfile.1>.

- Sincronizarea bazei de date pkgfile:

`sudo pkgfile --update`

- Căutați un pachet care deține un anumit fișier:

`pkgfile {{filename}}`

- Listează toate fișierele furnizate de un pachet:

`pkgfile --list {{package_name}}`

- Listează numai fișierele furnizate de un pachet aflat în directorul `bin` sau `sbin`:

`pkgfile --list --binaries {{package_name}}`

- Căutați un pachet care deține un anumit fișier folosind o potrivire insensibilă la majuscule și minuscule:

`pkgfile --ignorecase {{filename}}`

- Căutați un pachet care deține un anumit fișier în directorul `bin` sau `sbin`:

`pkgfile --binaries {{filename}}`

- Căutați un pachet care deține un anumit fișier, afișând versiunea pachetului:

`pkgfile --verbose {{filename}}`

- Căutați un pachet care deține un anumit fișier într-un anumit depozit:

`pkgfile --repo {{repository_name}} {{filename}}`
