# pvcreate

> Inițializați un disc sau o partiție pentru a o utiliza ca volum fizic.
> A se vedea și: `lvm`.
> Mai multe informații: <https://man7.org/linux/man-pages/man8/pvcreate.8.html>.

- Inițializați volumul `/dev/sda1` pentru a fi utilizat de LVM:

`pvcreate {{/dev/sda1}}`

- Forțați crearea fără nicio cerere de confirmare:

`pvcreate --force {{/dev/sda1}}`
