# readelf

> Afișează informații despre fișierele ELF.
> Mai multe informații: <http://man7.org/linux/man-pages/man1/readelf.1.html>.

- Afișează toate informațiile despre fișierul ELF:

`readelf -all {{path/to/binary}}`

- Afișează toate anteturile prezente în fișierul ELF:

`readelf --headers {{path/to/binary}}`

- Afișează intrările din secțiunea tabel de simboluri a fișierului ELF, dacă acesta are una:

`readelf --symbols {{path/to/binary}}`

- Afișează informațiile conținute în antetul ELF de la începutul fișierului:

`readelf --file-header {{path/to/binary}}`
