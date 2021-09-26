# dpkg-query

> Un instrument care afișează informații despre pachetele instalate.
> Mai multe informații: <https://manpages.debian.org/latest/dpkg/dpkg-query.1.html>.

- Listează toate pachetele instalate:

`dpkg-query -l`

- Listează pachetele instalate care corespund unui model:

`dpkg-query -l '{{pattern}}'`

- Listează toate fișierele instalate de un pachet:

`dpkg-query -L {{package_name}}`

- Afișează informații despre un pachet:

`dpkg-query -s {{package_name}}`
