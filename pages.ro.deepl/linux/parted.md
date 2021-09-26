# parted

> Un program de manipulare a partițiilor.
> Vezi și: `partprobe`.
> Mai multe informații: <https://www.gnu.org/software/parted/parted.html>.

- Listează partițiile de pe toate dispozitivele bloc:

`sudo parted --list`

- Pornește modul interactiv cu discul specificat selectat:

`sudo parted {{/dev/sdX}}`

- Creează o nouă tabelă de partiții cu tipul de etichetă specificat:

`sudo parted --script {{/dev/sdX}} mklabel {{aix|amiga|bsd|dvh|gpt|loop|mac|msdos|pc98|sun}}`

- Afișează informații despre partiții în modul interactiv:

`print`

- Selectați un disc în modul interactiv:

`select {{/dev/sdX}}`

- Creează o partiție de 16 GB cu sistemul de fișiere specificat în modul interactiv:

`mkpart {{primary|logical|extended}} {{btrfs|ext2|ext3|ext4|fat16|fat32|hfs|hfs+|linux-swap|ntfs|reiserfs|udf|xfs}} {{0%}} {{16G}}`

- Redimensionați o partiție în modul interactiv:

`resizepart {{/dev/sdXN}} {{end_position_of_partition}}`

- Îndepărtați o partiție în modul interactiv:

`rm {{/dev/sdXN}}`
