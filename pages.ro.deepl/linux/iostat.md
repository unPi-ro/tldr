# iostat

> Raportați statisticile pentru dispozitive și partiții.
> Mai multe informații: <https://manned.org/iostat>.

- Afișează un raport cu statisticile CPU și de disc de la pornirea sistemului:

`iostat`

- Afișează un raport cu statisticile CPU și de disc cu unități convertite în megabytes:

`iostat -m`

- Afișează statisticile CPU:

`iostat -c`

- Afișați statisticile discurilor cu numele discurilor (inclusiv LVM):

`iostat -N`

- Afișați statisticile extinse ale discului cu numele discurilor pentru dispozitivul "sda":

`iostat -xN {{sda}}`

- Afișează rapoarte incrementale ale statisticilor CPU și ale discului la fiecare 2 secunde:

`iostat {{2}}`
