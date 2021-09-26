# debugfs

> Un depanator interactiv de sisteme de fișiere ext2/ext3/ext4.
> Mai multe informații: <https://manned.org/debugfs>.

- Deschideți sistemul de fișiere în modul doar pentru citire:

`debugfs {{/dev/sdXN}}`

- Deschideți sistemul de fișiere în modul de citire și scriere:

`debugfs -w {{/dev/sdXN}}`

- Citește comenzile dintr-un fișier specificat, le execută și apoi iese:

`debugfs -f {{path/to/cmd_file}} {{/dev/sdXN}}`

- Vizualizați statisticile sistemului de fișiere în consola debugfs:

`stats`

- Închideți sistemul de fișiere:

`close -a`

- Enumeră toate comenzile disponibile:

`lr`
