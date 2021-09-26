# zramctl

> Configurați și controlați dispozitivele zram.
> Folosiți `mkfs` sau `mkswap` pentru a formata dispozitive zram în partiții.

- Verificați dacă este activat zram:

`lsmod | grep -i zram`

- Activați zram cu un număr dinamic de dispozitive (folosiți `zramctl` pentru a configura mai departe dispozitivele):

`sudo modprobe zram`

- Activați zram cu exact 2 dispozitive:

`sudo modprobe zram num_devices={{2}}`

- Găsiți și inițializați următorul dispozitiv zram liber pentru o unitate virtuală de 2 GB folosind compresia LZ4:

`sudo zramctl --find --size {{2GB}} --algorithm {{lz4}}`

- Lista dispozitivelor inițializate în prezent:

`zramctl`
