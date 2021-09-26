# homectl

> Creați, eliminați, modificați sau inspectați directoarele de domiciliu utilizând serviciul systemd-homed.
> Mai multe informații: <https://man.archlinux.org/man/homectl.1>.

- Listează conturile de utilizator și directoarele de origine asociate acestora:

`homectl list`

- Creați un cont de utilizator și un director principal asociat acestuia:

`sudo homectl create {{username}}`

- Îndepărtați un anumit utilizator și directorul principal asociat:

`sudo homectl remove {{username}}`

- Modificați parola pentru un anumit utilizator:

`sudo homectl passwd {{username}}`

- Rulați un shell sau o comandă cu acces la un anumit director principal:

`sudo homectl with {{username}} -- {{command}} {{command_arguments}}`

- Blocați sau deblocați un anumit director principal:

`sudo homectl {{lock|unlock}} {{username}}`

- Modificați spațiul pe disc atribuit unui anumit director principal la 100 GiB:

`sudo homectl resize {{username}} {{100G}}`

- Ajutor pentru afișare:

`homectl --help`
