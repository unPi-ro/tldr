# lrunzip

> Un program de decomprimare a fișierelor mari.
> A se vedea, prin urmare, `lrzip`, `lrztar`, `lrzuntar`.
> Mai multe informații: <https://manned.org/lrunzip>.

- Decomprimarea unui fișier:

`lrunzip {{filename.lrz}}`

- Decomprimarea unui fișier utilizând un anumit număr de fire de procesare:

`lrunzip -p {{8}} {{filename.lrz}}`

- Decomprimarea unui fișier și suprascrierea silențioasă a fișierelor, dacă acestea există:

`lrunzip -f {{filename.lrz}}`

- Păstrați fișierele rupte sau deteriorate în loc să le ștergeți la decomprimare:

`lrunzip -K {{filename.lrz}}`

- Specificați numele și/sau calea fișierului de ieșire:

`lrunzip -o {{outfilename}} {{filename.lrz}}`
