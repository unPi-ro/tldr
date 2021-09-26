# snap

> Instrument de gestionare a pachetelor software autonome "snap".
> Similar cu ceea ce este `apt` pentru ".deb".

- Căutați un pachet:

`snap find {{package_name}}`

- Instalați un pachet:

`snap install {{package_name}}`

- Actualizarea unui pachet:

`snap refresh {{package_name}}`

- Actualizarea unui pachet pe un alt canal (cale, risc sau ramură):

`snap refresh {{package_name}} --channel={{channel}}`

- Actualizați toate pachetele:

`snap refresh`

- Afișează informații de bază despre software-ul snap instalat:

`snap list`

- Dezinstalați un pachet:

`snap remove {{package_name}}`

- Verificați dacă în sistem au avut loc modificări recente ale snap-urilor:

`snap changes`
