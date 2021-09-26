# dumpe2fs

> Tipăriți informațiile despre super-bloc și grupul de blocuri pentru sistemele de fișiere ext2/ext3/ext4.
> Demontați partiția înainte de a rula această comandă folosind `umount {{device}}`.
> Mai multe informații: <https://manned.org/dumpe2fs>.

- Afișează informații despre sistemele de fișiere ext2, ext3 și ext4:

`dumpe2fs {{/dev/sdXN}}`

- Afișează blocurile care sunt rezervate ca fiind rele în sistemul de fișiere:

`dumpe2fs -b {{/dev/sdXN}}`

- Forțați afișarea informațiilor despre sistemul de fișiere chiar și în cazul în care există stegulețe de caracteristici nerecunoscute:

`dumpe2fs -f {{/dev/sdXN}}`

- Afișează numai informațiile despre superbloc, dar nu și informațiile detaliate despre descriptorul grupului de blocuri:

`dumpe2fs -h {{/dev/sdXN}}`

- Tipărește numerele detaliate ale blocurilor de informații de grup în format hexazecimal:

`dumpe2fs -x {{/dev/sdXN}}`
