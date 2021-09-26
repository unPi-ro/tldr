# ncat

> Utilizați funcționalitatea normală `cat` în rețele.

- Ascultă intrările pe portul specificat și le scrie în fișierul specificat:

`ncat -l {{port}} > {{path/to/file}}`

- Acceptă mai multe conexiuni și menține ncat deschis după ce acestea au fost închise:

`ncat -lk {{port}}`

- Scrie ieșirea fișierului specificat la gazda specificată pe portul specificat:

`ncat {{address}} {{port}} < {{path/to/file}}`
