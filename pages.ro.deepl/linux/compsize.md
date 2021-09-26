# compsize

> Calculați rata de compresie a unui set de fișiere pe un sistem de fișiere btrfs.
> Vezi și `btrfs filesystem` pentru recomprimarea unui fișier prin defragmentarea acestuia.
> Mai multe informații: <https://github.com/kilobyte/compsize>.

- Calculează rata de compresie curentă pentru un fișier sau un director:

`sudo compsize {{path/to/file_or_directory}}`

- Nu traversează limitele sistemului de fișiere:

`sudo compsize --one-file-system {{path/to/file_or_directory}}`

- Afișați numărul de octeți brut în loc de dimensiuni lizibile pentru oameni:

`sudo compsize --bytes {{path/to/file_or_directory}}`
