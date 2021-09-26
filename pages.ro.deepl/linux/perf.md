# perf

> Cadru pentru măsurători de contorizare a performanțelor Linux.

- Afișează statisticile de bază ale contorului de performanță pentru o comandă:

`perf stat {{gcc hello.c}}`

- Afișează profilul contorului de performanță în timp real la nivelul întregului sistem:

`sudo perf top`

- Executați o comandă și înregistrați profilul acesteia în `perf.data`:

`sudo perf record {{command}}`

- Citește `perf.data` (creat de `perf record`) și afișează profilul:

`sudo perf report`
