# userdel

> Eliminați un cont de utilizator sau eliminați un utilizator dintr-un grup.
> Notă: toate comenzile trebuie să fie executate ca root.
> Mai multe informații: <https://manned.org/userdel>.

- Eliminați un utilizator:

`userdel {{name}}`

- Îndepărtați un utilizator împreună cu directorul de domiciliu și cu spool-ul de poștă electronică al acestuia:

`userdel --remove {{name}}`

- Eliminați un utilizator dintr-un grup:

`userdel {{name}} {{group}}`

- Îndepărtați un utilizator din alt director rădăcină:

`userdel --root {{path/to/other/root}} {{name}}`
