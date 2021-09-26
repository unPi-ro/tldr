# synopkg

> Utilitar de gestionare a pachetelor pentru Synology DiskStation Manager.
> Mai multe informații: <https://www.synology.com/dsm>.

- Enumeră numele pachetelor instalate:

`synopkg list --name`

- Enumeră pachetele care depind de un anumit pachet:

`synopkg list --depend-on {{package}}`

- Porniți/opriți un pachet:

`sudo synopkg {{start|stop}} {{package}}`

- Tipărește starea unui pachet:

`synopkg status {{package}}`

- Dezinstalați un pachet:

`sudo synopkg uninstall {{package}}`

- Verifică dacă sunt disponibile actualizări pentru un pachet:

`synopkg checkupdate {{package}}`

- Actualizați toate pachetele la cea mai recentă versiune:

`sudo synopkg upgradeall`

- Instalați un pachet dintr-un fișier synopkg:

`sudo synopkg install {{path/to/package.spk}}`
