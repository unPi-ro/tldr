# hlint

> Instrument pentru a sugera îmbunătățiri la codul Haskell.
> Mai multe informații: <http://hackage.haskell.org/package/hlint>.

- Afișează sugestii pentru un anumit fișier:

`hlint {{path/to/file}} options`

- Verifică toate fișierele Haskell și generează un raport:

`hlint {{path/to/directory}} --report`

- Aplicați automat majoritatea sugestiilor:

`hlint {{path/to/file}} --refactor`

- Afișați opțiuni suplimentare:

`hlint {{path/to/file}} --refactor-options`

- Generează un fișier de setări care ignoră toate indicațiile restante:

`hlint {{path/to/file}} --default > {{.hlint.yaml}}`
