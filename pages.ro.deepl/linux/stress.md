# stress

> Un instrument pentru a testa la stres CPU, memoria și IO pe un sistem Linux.

- Dezvoltați 4 lucrători pentru a testa CPU:

`stress -c {{4}}`

- Creați 2 lucrători pentru a testa IO și ieșiți din timp după 5 secunde:

`stress -i {{2}} -t {{5}}`

- Creați 2 lucrători pentru a testa memoria de stres (fiecare lucrător alocă 256M de octeți):

`stress -m {{2}} --vm-bytes {{256M}}`

- Se generează 2 lucrători care se învârt pe write()/unlink() (fiecare lucrător scrie 1G bytes):

`stress -d {{2}} --hdd-bytes {{1GB}}`
