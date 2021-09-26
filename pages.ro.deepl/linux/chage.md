# chage

> Modificați informațiile de expirare a contului de utilizator și a parolei.
> Mai multe informații: <https://manned.org/chage>.

- Enumeră informațiile privind parola utilizatorului:

`chage --list {{username}}`

- Activați expirarea parolei în 10 zile:

`sudo chage --maxdays {{10}} {{username}}`

- Dezactivați expirarea parolei:

`sudo chage --maxdays {{-1}} {{username}}`

- Setați data de expirare a contului:

`sudo chage --expiredate {{YYYY-MM-DD}} {{username}}`

- Forțați utilizatorul să schimbe parola la următoarea autentificare:

`sudo chage --lastday {{0}} {{username}}`
