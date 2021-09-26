# fakeroot

> Executați o comandă într-un mediu care falsifică privilegii de root pentru manipularea fișierelor.
> Mai multe informații: <https://manpages.debian.org/latest/fakeroot/fakeroot.1.html>.

- Porniți shell-ul implicit ca fakeroot:

`fakeroot`

- Rulați o comandă ca fakeroot:

`fakeroot -- {{command}} {{command_arguments}}`

- Executați o comandă ca fakeroot și salvați mediul într-un fișier la ieșire:

`fakeroot -s {{path/to/file}} -- {{command}} {{command_arguments}}`

- Încărcați un mediu fakeroot și rulați o comandă ca fakeroot:

`fakeroot -i {{path/to/file}} -- {{command}} {{command_arguments}}`

- Rulați o comandă care păstrează proprietatea reală a fișierelor în loc să pretindă că acestea sunt deținute de root:

`fakeroot --unknown-is-real -- {{command}} {{command_arguments}}`

- Ajutor pentru afișare:

`fakeroot --help`
