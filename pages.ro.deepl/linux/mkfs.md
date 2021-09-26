# mkfs

> Construiți un sistem de fișiere Linux pe o partiție de hard disk.
> Această comandă este depreciată în favoarea utilităților specifice sistemului de fișiere mkfs.<type>.
> Mai multe informații: <https://manned.org/mkfs>.

- Construiți un sistem de fișiere Linux ext2 pe o partiție:

`mkfs {{path/to/partition}}`

- Construiește un sistem de fișiere de un tip specificat:

`mkfs -t {{ext4}} {{path/to/partition}}`

- Construiește un sistem de fișiere de un tip specificat și verifică dacă există blocuri defecte:

`mkfs -c -t {{ntfs}} {{path/to/partition}}`
