# apt

> Utilitar de gestionare a pachetelor pentru distribuțiile bazate pe Debian.
> Înlocuitor recomandat pentru apt-get atunci când este utilizat în mod interactiv în versiunile Ubuntu 16.04 și ulterioare.
> Mai multe informații: <https://manpages.debian.org/latest/apt/apt.8.html>.

- Actualizează lista de pachete și versiuni disponibile (se recomandă să fie executată înainte de alte comenzi `apt`):

`sudo apt update`

- Căutați un anumit pachet:

`apt search {{package}}`

- Afișează informații pentru un pachet:

`apt show {{package}}`

- Instalați un pachet sau actualizați-l la cea mai recentă versiune disponibilă:

`sudo apt install {{package}}`

- Elimină un pachet (dacă se folosește `purge` în schimb, se elimină și fișierele de configurare ale acestuia):

`sudo apt remove {{package}}`

- Actualizați toate pachetele instalate la cele mai noi versiuni disponibile:

`sudo apt upgrade`

- Lista tuturor pachetelor:

`apt list`

- Lista pachetelor instalate:

`apt list --installed`
