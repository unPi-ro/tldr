# btrfs

> Un sistem de fișiere bazat pe principiul copy-on-write (COW) pentru Linux.
> Unele subcomandă, cum ar fi `btrfs device`, au propria documentație de utilizare.
> Mai multe informații: <https://btrfs.wiki.kernel.org/index.php/Manpage/btrfs>.

- Create subvolume:

`sudo btrfs subvolume create {{path/to/subvolume}}`

- Listează subvolumele:

`sudo btrfs subvolume list {{path/to/mount_point}}`

- Afișează informații despre utilizarea spațiului:

`sudo btrfs filesystem df {{path/to/mount_point}}`

- Activează cota:

`sudo btrfs quota enable {{path/to/subvolume}}`

- Afișați cota:

`sudo btrfs qgroup show {{path/to/subvolume}}`
