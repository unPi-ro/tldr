# bluetoothd

> Daemon pentru gestionarea dispozitivelor bluetooth.
> Mai multe informații: <https://manned.org/bluetoothd>.

- Porniți demonul:

`bluetoothd`

- Pornește demonul, înregistrându-se în stdout:

`bluetoothd --nodetach`

- Pornește demonul cu un fișier de configurare specific (valoarea implicită este `/etc/bluetooth/main.conf`):

`bluetoothd --configfile {{path/to/file}}`

- Pornește demonul cu o ieșire de tip verbose pe stderr:

`bluetoothd --debug`

- Pornește demonul cu o ieșire verbose care provine din anumite fișiere din sursa bluetoothd sau plugins:

`bluetoothd --debug={{path/to/file1}}:{{path/to/file2}}:{{path/to/file3}}`
