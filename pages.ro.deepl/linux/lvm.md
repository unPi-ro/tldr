# lvm

> Gestionați volumele fizice, grupurile de volume și volumele logice utilizând shell-ul interactiv Logical Volume Manager (LVM).
> Mai multe informații: <https://man7.org/linux/man-pages/man8/lvm.8.html>.

- Porniți shell-ul interactiv Logical Volume Manager:

`sudo lvm`

- Enumerați comenzile Logical Volume Manager:

`sudo lvm help`

- Inițializați o unitate sau o partiție pentru a fi utilizată ca volum fizic:

`sudo lvm pvcreate {{/dev/sdXY}}`

- Afișează informații despre volumele fizice:

`sudo lvm pvdisplay`

- Creați un grup de volume numit vg1 din volumul fizic de pe `/dev/sdXY`:

`sudo lvm vgcreate {{vg1}} {{/dev/sdXY}}`

- Afișați informații despre grupurile de volume:

`sudo lvm vgdisplay`

- Creați un volum logic cu dimensiunea de 10G din grupul de volume vg1:

`sudo lvm lvcreate -L {{10G}} {{vg1}}`

- Afișați informații despre volumele logice:

`sudo lvm lvdisplay`
