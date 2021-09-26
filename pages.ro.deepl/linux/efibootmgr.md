# efibootmgr

> Manipulați Managerul de pornire UEFI.
> Mai multe informații: <https://manned.org/efibootmgr>.

- Enumeră setările curente / bootnums:

`efibootmgr`

- Enumeră traseele fișierelor:

`efibootmgr -v`

- Adăugați UEFI Shell v2 ca opțiune de pornire:

`sudo efibootmgr -c -d {{/dev/sda1}} -l {{\EFI\tools\Shell.efi}} -L "{{UEFI Shell}}"`

- Modificați ordinea curentă de pornire:

`sudo efibootmgr -o {{0002,0008,0001,0005}}`

- Ștergeți o opțiune de pornire:

`sudo efibootmgr -b {{0008}} --delete-bootnum`
