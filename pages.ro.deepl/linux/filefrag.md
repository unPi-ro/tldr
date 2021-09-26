# filefrag

> Raportează cât de fragmentat poate fi un anumit fișier.
> Mai multe informații: <https://manned.org/filefrag>.

- Afișează un raport pentru un anumit fișier:

`filefrag {{path/to/file}}`

- Afișează un raport pentru o listă de fișiere separate prin spații:

`filefrag {{path/to/file1}} {{path/to/file2}}`

- Afișarea unui raport utilizând o dimensiune de 1024 de octeți:

`filefrag -b {{path/to/file}}`

- Sincronizați fișierul înainte de a solicita maparea:

`filefrag -s {{path/to/files}}`

- Afișarea cartografierii atributelor extinse:

`filefrag -x {{path/to/files}}`

- Afișează un raport cu informații detaliate:

`filefrag -v {{path/to/files}}`
