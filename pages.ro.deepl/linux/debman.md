# debman

> Citiți paginile de manual din pachetele dezinstalate.
> Mai multe informații: <https://manpages.debian.org/latest/debian-goodies/debman.1.html>.

- Citește o pagină de manual pentru o comandă care este furnizată de un nume de pachet specificat:

`debman -p {{package_name}} {{command_name}}`

- Specificați o versiune a pachetului de descărcat:

`debman -p {{package_name}}={{version}} {{command_name}}`

- Citește o pagină de manual într-un fișier `.deb`:

`debman -f {{path/to/filename.deb}} {{command_name}}`
