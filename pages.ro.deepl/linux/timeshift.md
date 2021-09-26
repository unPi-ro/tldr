# timeshift

> Utilitarul de restaurare a sistemului.
> Mai multe informații: <https://github.com/teejee2008/timeshift>.

- Lista de instantanee:

`sudo timeshift --list`

- Creați un nou instantaneu (dacă este programat):

`sudo timeshift --check`

- Creați un nou instantaneu (chiar dacă nu este programat):

`sudo timeshift --create`

- Restaurați un instantaneu (selectând ce instantaneu să restaurați în mod interactiv):

`sudo timeshift --restore`

- Restaurați un anumit instantaneu:

`sudo timeshift --restore --snapshot '{{snapshot}}'`

- Ștergeți un anumit instantaneu:

`sudo timeshift --delete --snapshot '{{snapshot}}'`
