# apt-get

> Utilitar de gestionare a pachetelor Debian și Ubuntu.
> Căutați pachete folosind `apt-cache`.
> Mai multe informații: <https://manpages.debian.org/latest/apt/apt-get.8.html>.

- Actualizează lista de pachete și versiuni disponibile (se recomandă să fie executată înainte de alte comenzi `apt-get`):

`apt-get update`

- Instalați un pachet sau actualizați-l la cea mai recentă versiune disponibilă:

`apt-get install {{package}}`

- Îndepărtați un pachet:

`apt-get remove {{package}}`

- Elimină un pachet și fișierele de configurare ale acestuia:

`apt-get purge {{package}}`

- Actualizați toate pachetele instalate la cele mai noi versiuni disponibile:

`apt-get upgrade`

- Curățarea depozitului local - eliminarea fișierelor de pachete (`.deb`) din descărcările întrerupte care nu mai pot fi descărcate:

`apt-get autoclean`

- Eliminați toate pachetele care nu mai sunt necesare:

`apt-get autoremove`

- Actualizează pachetele instalate (la fel ca `upgrade`), dar elimină pachetele învechite și instalează pachete suplimentare pentru a satisface noile dependențe:

`apt-get dist-upgrade`
