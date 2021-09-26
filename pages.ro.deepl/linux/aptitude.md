# aptitude

> Utilitar de gestionare a pachetelor Debian și Ubuntu.
> Mai multe informații: <https://manpages.debian.org/latest/aptitude/aptitude.8.html>.

- Sincronizarea listei de pachete și versiuni disponibile. Aceasta ar trebui să fie executată mai întâi, înainte de a executa comenzile aptitude ulterioare:

`aptitude update`

- Instalați un nou pachet și dependențele sale:

`aptitude install {{package}}`

- Căutați un pachet:

`aptitude search {{package}}`

- Căutați un pachet instalat (`?installed` este un termen de căutare aptitude):

`aptitude search '?installed({{package}})'`

- Îndepărtați un pachet și toate pachetele care depind de el:

`aptitude remove {{package}}`

- Actualizați pachetele instalate la cele mai noi versiuni disponibile:

`aptitude upgrade`

- Actualizarea pachetelor instalate (ca `aptitude upgrade`), inclusiv eliminarea pachetelor învechite și instalarea de pachete suplimentare pentru a satisface noile dependențe de pachete:

`aptitude full-upgrade`

- Puneți un pachet instalat în așteptare pentru a împiedica actualizarea automată a acestuia:

`aptitude hold '?installed({{package}})'`
