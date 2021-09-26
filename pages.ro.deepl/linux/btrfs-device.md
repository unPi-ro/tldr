# btrfs device

> Gestionați dispozitive într-un sistem de fișiere btrfs.
> Mai multe informații: <https://btrfs.wiki.kernel.org/index.php/Manpage/btrfs-device>.

- Adăugați unul sau mai multe dispozitive la un sistem de fișiere btrfs:

`sudo btrfs device add {{path/to/block_device1}} [{{path/to/block_device2}}] {{path/to/btrfs_filesystem}}`

- Elimină un dispozitiv dintr-un sistem de fișiere btrfs:

`sudo btrfs device remove {{path/to/device|device_id}} [{{...}}]`

- Afișează statisticile privind erorile:

`sudo btrfs device stats {{path/to/btrfs_filesystem}}`

- Scanați toate discurile și informați nucleul cu privire la toate sistemele de fișiere btrfs detectate:

`sudo btrfs device scan --all-devices`

- Afișează statisticile detaliate de alocare per disc:

`sudo btrfs device usage {{path/to/btrfs_filesystem}}`
