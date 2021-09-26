# lsblk

> Afișează informații despre dispozitive.
> Mai multe informații: <https://manned.org/lsblk>.

- Enumeră toate dispozitivele de stocare într-un format arborescent:

`lsblk`

- De asemenea, listează dispozitivele goale:

`lsblk -a`

- Tipărește coloana SIZE în octeți, mai degrabă decât într-un format lizibil pentru oameni:

`lsblk -b`

- Informații de ieșire despre sistemele de fișiere:

`lsblk -f`

- Utilizați caractere ASCII pentru formatarea arborelui:

`lsblk -i`

- Informații de ieșire despre topologia blocului de dispozitive:

`lsblk -t`

- Excludeți dispozitivele specificate de lista de numere de dispozitive principale, separate prin virgulă:

`lsblk -e {{1,7}}`

- Afișează un rezumat personalizat utilizând o listă de coloane separate prin virgulă:

`lsblk --output {{NAME}},{{SERIAL}},{{MODEL}},{{TRAN}},{{TYPE}},{{SIZE}},{{FSTYPE}},{{MOUNTPOINT}}`
