# mkinitcpio

> Generează mediile inițiale ale ramdisk-ului pentru pornirea kernel-ului Linux pe baza setărilor predefinite specificate.
> Mai multe informații: <https://man.archlinux.org/man/mkinitcpio.8>.

- Efectuați un exercițiu de probă (imprimați ceea ce ar trebui făcut fără a o face efectiv):

`mkinitcpio`

- Generează un mediu ramdisk bazat pe preset-ul `linux`:

`mkinitcpio --preset {{linux}}`

- Generează un mediu ramdisk bazat pe preset-ul `linux-lts`:

`mkinitcpio --preset {{linux-lts}}`

- Generează mediile ramdisk pe baza tuturor presetărilor existente (utilizate pentru a regenera toate imaginile initramfs după o modificare în `/etc/mkinitcpio.conf`):

`mkinitcpio --allpresets`

- Generarea unei imagini initramfs utilizând un fișier de configurare alternativ:

`mkinitcpio --config {{path/to/mkinitcpio.conf}} --generate {{path/to/initramfs.img}}`

- Generează o imagine initramfs pentru un alt kernel decât cel care rulează în prezent (versiunile de kernel instalate pot fi găsite în `/usr/lib/modules/`):

`mkinitcpio --kernel {{kernel_version}} --generate {{path/to/initramfs.img}}`

- Enumeră toate cârligele disponibile:

`mkinitcpio --listhooks`

- Afișează ajutorul pentru un anumit cârlig:

`mkinitcpio --hookhelp {{hook_name}}`
