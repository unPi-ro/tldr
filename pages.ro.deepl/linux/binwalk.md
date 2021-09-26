# binwalk

> Firmware Analysis Tool.
> Mai multe informații: <https://github.com/ReFirmLabs/binwalk>.

- Scanează un fișier binar:

`binwalk {{path/to/binary}}`

- Extrage fișiere dintr-un fișier binar, specificând directorul de ieșire:

`binwalk --extract --directory {{output_directory}} {{path/to/binary}}`

- Extrage în mod recurent fișiere dintr-un fișier binar, limitând adâncimea de recursivitate la 2:

`binwalk --extract --matryoshka --depth {{2}} {{path/to/binary}}`

- Extrage fișiere dintr-un fișier binar cu semnătura specificată:

`binwalk --dd '{{png image:png}}' {{path/to/binary}}`

- Analizează entropia unui binar, salvând graficul cu același nume ca și binarul și cu extensia `.png` atașată:

`binwalk --entropy --save {{path/to/binary}}`

- Combinați analiza entropiei, a semnăturilor și a codurilor operaționale într-o singură comandă:

`binwalk --entropy --signature --opcodes {{path/to/binary}}`
