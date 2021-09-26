# btrfs filesystem

> Gestionați sistemele de fișiere btrfs.
> Mai multe informații: <https://btrfs.wiki.kernel.org/index.php/Manpage/btrfs-filesystem>.

- Afișează utilizarea sistemului de fișiere (opțional, se poate rula ca root pentru a afișa informații detaliate):

`btrfs filesystem usage {{path/to/btrfs_mount}}`

- Afișați utilizarea pe dispozitive individuale:

`sudo btrfs filesystem show {{path/to/btrfs_mount}}`

- Defragmentați un singur fișier de pe un sistem de fișiere btrfs (evitați în timp ce un agent de deduplicare este în curs de execuție):

`sudo btrfs filesystem defragment -v {{path/to/file}}`

- Defragmentați un director în mod recursiv (nu depășește limitele subvolumului):

`sudo btrfs filesystem defragment -v -r {{path/to/directory}}`

- Forțați sincronizarea blocurilor de date nescrise pe disc(e):

`sudo btrfs filesystem sync {{path/to/btrfs_mount}}`

- Rezumați utilizarea discului pentru fișierele dintr-un director în mod recursiv:

`sudo btrfs filesystem du --summarize {{path/to/directory}}`
