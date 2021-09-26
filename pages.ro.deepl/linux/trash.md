# trash

> Un CLI pentru gestionarea coșului de gunoi / coș de reciclare.
> Mai multe informații: <https://github.com/andreafrancia/trash-cli>.

- Ștergeți un fișier (trimiteți la coșul de gunoi):

`trash {{path/to/file}}`

- Lista fișierelor din coșul de gunoi:

`trash-list`

- Restaurați fișierul din coșul de gunoi:

`trash-restore`

- Goliți gunoiul:

`trash-empty`

- Goliți coșul de gunoi, păstrând fișierele eliminate cu mai puțin de {{10}} zile în urmă:

`trash-empty {{10}}`

- Eliminați toate fișierele cu numele "foo" din coșul de gunoi:

`trash-rm foo`

- Elimină toate fișierele cu o anumită locație inițială:

`trash-rm {{/absolute/path/to/file_or_directory}}`
