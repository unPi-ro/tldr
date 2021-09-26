# btrfs subvolume

> Gestionați subvolumele și instantaneele btrfs.
> Mai multe informații: <https://btrfs.wiki.kernel.org/index.php/Manpage/btrfs-subvolume>.

- Creați un nou subvolum gol:

`sudo btrfs subvolume create {{path/to/new_subvolume}}`

- Listează toate subvolumele și instantaneele din sistemul de fișiere specificat:

`sudo btrfs subvolume list {{path/to/btrfs_filesystem}}`

- Delete a subvolume:

`sudo btrfs subvolume delete {{path/to/subvolume}}`

- Creați un instantaneu numai pentru citire al unui subvolum existent:

`sudo btrfs subvolume snapshot -r {{path/to/source_subvolume}} {{path/to/target}}`

- Creați un instantaneu de citire-scriere al unui subvolum existent:

`sudo btrfs subvolume snapshot {{path/to/source_subvolume}} {{path/to/target}}`

- Afișează informații detaliate despre un subvolum:

`sudo btrfs subvolume show {{path/to/subvolume}}`
