# lrzuntar

> Un wrapper pentru `lrunzip` pentru a simplifica decomprimarea directoarelor.
> A se vedea și: `lrztar`, `lrzip`.
> Mai multe informații: <https://manned.org/lrzuntar>.

- Decomprimare dintr-un fișier în directorul curent:

`lrzuntar {{path/to/archive.tar.lrz}}`

- Decomprimare dintr-un fișier în directorul curent folosind un anumit număr de fire de procesare:

`lrzuntar -p {{8}} {{path/to/archive.tar.lrz}}`

- Decomprimarea dintr-un fișier în directorul curent și suprascrierea silențioasă a elementelor care există deja:

`lrzuntar -f {{archive.tar.lrz}}`

- Specificați calea de ieșire:

`lrzuntar -O {{path/to/directory}} {{archive.tar.lrz}}`

- Ștergeți fișierul comprimat după decomprimare:

`lrzuntar -D {{path/to/archive.tar.lrz}}`
