# mdadm

> Utilitar de gestionare RAID.
> Mai multe informații: <https://manned.org/mdadm>.

- Creați o matrice:

`mdadm --create {{/dev/md/MyRAID}} --level {{raid_level}} --raid-devices {{number_of_disks}} {{/dev/sdXN}}`

- Stop array:

`mdadm --stop {{/dev/md0}}`

- Marcați discul ca eșuat:

`mdadm --fail {{/dev/md0}} {{/dev/sdXN}}`

- Scoateți discul:

`mdadm --remove {{/dev/md0}} {{/dev/sdXN}}`

- Adăugați un disc la matrice:

`mdadm --assemble {{/dev/md0}} {{/dev/sdXN}}`

- Afișează informații RAID:

`mdadm --detail {{/dev/md0}}`
