# xclock

> Afișați ora în format analogic sau digital.

- Afișează un ceas analogic:

`xclock`

- Afișează un ceas digital de 24 de ore numai cu câmpurile de ore și minute:

`xclock -digital -brief`

- Afișează un ceas digital utilizând un șir de caractere în format strftime (a se vedea strftime(3)):

`xclock -digital -strftime {{format}}`

- Afișează un ceas digital de 24 de ore cu câmpurile de oră, minut și secundă care se actualizează la fiecare secundă:

`xclock -digital -strftime '%H:%M:%S' -update 1`

- Afișează un ceas digital de 12 ore, doar cu câmpurile de oră și minute:

`xclock -digital -twelve -brief`
