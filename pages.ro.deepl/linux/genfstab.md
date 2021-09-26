# genfstab

> Script de instalare Arch Linux pentru a genera o ieșire potrivită pentru a fi adăugată la un fișier fstab.
> Mai multe informații: <https://man.archlinux.org/man/extra/arch-install-scripts/genfstab.8>.

- Afișează o ieșire compatibilă cu fstab pe baza unei etichete de volum:

`genfstab -L {{path/to/mount_point}}`

- Afișează o ieșire compatibilă cu fstab pe baza unui UUID de volum:

`genfstab -U {{path/to/mount_point}}`

- O modalitate obișnuită de a genera un fișier fstab, care necesită permisiuni de root:

`genfstab -U {{/mnt}} >> {{/mnt/etc/fstab}}`

- Adăugați un volum la un fișier fstab pentru a-l monta automat:

`genfstab -U {{path/to/mount_point}} | sudo tee -a /etc/fstab`
