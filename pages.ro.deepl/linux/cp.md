# cp

> Copiați fișiere și directoare.
> Mai multe informații: <https://www.gnu.org/software/coreutils/cp>.

- Copiați un fișier în altă locație:

`cp {{path/to/source_file.ext}} {{path/to/target_file.ext}}`

- Copiază un fișier în alt director, păstrând numele fișierului:

`cp {{path/to/source_file.ext}} {{path/to/target_parent_directory}}`

- Copiază în mod recurent conținutul unui director într-o altă locație (dacă destinația există, directorul este copiat în interiorul acesteia):

`cp -r {{path/to/source_directory}} {{path/to/target_directory}}`

- Copiază un director în mod recursiv, în modul verbose (afișează fișierele pe măsură ce sunt copiate):

`cp -vr {{path/to/source_directory}} {{path/to/target_directory}}`

- Copiază fișiere text într-o altă locație, în mod interactiv (solicită utilizatorului înainte de a suprascrie):

`cp -i {{*.txt}} {{path/to/target_directory}}`

- Urmăriți legăturile simbolice înainte de copiere:

`cp -L {{link}} {{path/to/target_directory}}`

- Utilizați calea completă a fișierelor sursă, creând toate directoarele intermediare lipsă la copiere:

`cp --parents {{source/path/to/file}} {{path/to/target_file}}`
