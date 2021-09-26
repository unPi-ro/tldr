# gpasswd

> Administrați `/etc/group` și `/etc/gshadow`.
> Mai multe informații: <https://manned.org/gpasswd>.

- Definiți administratorii de grup:

`sudo gpasswd -A {{user1,user2}} {{group}}`

- Setați lista membrilor grupului:

`sudo gpasswd -M {{user1,user2}} {{group}}`

- Creați o parolă pentru grupul numit:

`gpasswd {{group}}`

- Adăugați un utilizator la grupul numit:

`gpasswd -a {{user}} {{group}}`

- Elimină un utilizator din grupul numit:

`gpasswd -d {{user}} {{group}}`
