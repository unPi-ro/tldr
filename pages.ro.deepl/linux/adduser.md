# adduser

> Utilitarul de adăugare a utilizatorilor.
> Mai multe informații: <https://manpages.debian.org/latest/adduser/adduser.html>.

- Creați un nou utilizator cu un director principal implicit și solicitați utilizatorului să seteze o parolă:

`adduser {{username}}`

- Creați un nou utilizator fără un director personal:

`adduser --no-create-home {{username}}`

- Creează un nou utilizator cu un director personal în calea specificată:

`adduser --home {{path/to/home}} {{username}}`

- Creează un nou utilizator cu shell-ul specificat ca shell de autentificare:

`adduser --shell {{path/to/shell}} {{username}}`

- Creează un nou utilizator care aparține grupului specificat:

`adduser --ingroup {{group}} {{username}}`

- Adaugă un utilizator existent în grupul specificat:

`adduser {{username}} {{group}}`
