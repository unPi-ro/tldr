# extrace

> Urmăriți apelurile exec().
> Mai multe informații: <https://github.com/chneukirchen/extrace>.

- Urmăriți toate execuțiile de program care au loc pe sistem:

`sudo extrace`

- Executați o comandă și urmăriți numai descendenții acestei comenzi:

`sudo extrace {{command}}`

- Tipărește directorul de lucru curent al fiecărui proces:

`sudo extrace -d`

- Rezolvă calea completă a fiecărui executabil:

`sudo extrace -l`

- Afișează utilizatorul care execută fiecare proces:

`sudo extrace -u`
