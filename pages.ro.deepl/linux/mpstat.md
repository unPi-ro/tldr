# mpstat

> Raportați statisticile CPU.
> Mai multe informații: <https://manned.org/mpstat>.

- Afișează statisticile CPU la fiecare 2 secunde:

`mpstat {{2}}`

- Afișează 5 rapoarte, unul câte unul, la intervale de 2 secunde:

`mpstat {{2}} {{5}}`

- Afișarea a 5 rapoarte, unul câte unul, de la un anumit procesor, la intervale de 2 secunde:

`mpstat -P {{0}} {{2}} {{5}}`
