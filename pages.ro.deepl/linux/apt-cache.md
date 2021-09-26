# apt-cache

> Instrument de interogare a pachetelor Debian și Ubuntu.
> Mai multe informații: <https://manpages.debian.org/latest/apt/apt-cache.8.html>.

- Căutați un pachet în sursele dvs. curente:

`apt-cache search {{query}}`

- Afișează informații despre un pachet:

`apt-cache show {{package}}`

- Arată dacă un pachet este instalat și actualizat:

`apt-cache policy {{package}}`

- Afișează dependențele pentru un pachet:

`apt-cache depends {{package}}`

- Afișează pachetele care depind de un anumit pachet:

`apt-cache rdepends {{package}}`
