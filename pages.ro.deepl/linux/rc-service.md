# rc-service

> Localizați și rulați serviciile OpenRC cu argumente.
> Vezi și `openrc`.

- Afișează starea unui serviciu:

`rc-service {{service_name}} status`

- Începeți un serviciu:

`sudo rc-service {{service_name}} start`

- Opriți un serviciu:

`sudo rc-servie {{service_name}} stop`

- Reporniți un serviciu:

`sudo rc-service {{service_name}} restart`

- Simulați rularea unei comenzi personalizate a unui serviciu:

`sudo rc-service --dry-run {{service_name}} {{command_name}}`

- Executați de fapt comanda personalizată a unui serviciu:

`sudo rc-service {{service_name}} {{command_name}}`

- Rezolvarea locației unei definiții de serviciu pe disc:

`sudo rc-service --resolve {{service_name}}`
