# lrzip

> Un program de comprimare a fișierelor mari.
> A se vedea, prin urmare, `lrunzip`, `lrztar`, `lrzuntar`.
> Mai multe informații: <https://manned.org/lrzip>.

- Comprimați un fișier cu LZMA - compresie lentă, decompresie rapidă:

`lrzip {{filename}}`

- Comprimați un fișier cu BZIP2 - o soluție de mijloc bună pentru compresie/viteză:

`lrzip -b {{filename}}`

- Compresie cu ZPAQ - compresie extremă, dar foarte lentă:

`lrzip -z {{filename}}`

- Compresie cu LZO - compresie ușoară, decompresie extrem de rapidă:

`lrzip -l {{filename}}`

- Comprimați un fișier și protejați-l/criptați-l cu parolă:

`lrzip -e {{filename}}`

- Suprascrieți numărul de fire de procesare care trebuie utilizate:

`lrzip -p {{8}} {{filename}}`
