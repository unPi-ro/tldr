# pidstat

> Afișează utilizarea resurselor sistemului, inclusiv CPU, memorie, IO etc.

- Afișează statisticile CPU la un interval de 2 secunde pentru 10 ori:

`pidstat {{2}} {{10}}`

- Afișați erorile de pagină și utilizarea memoriei:

`pidstat -r`

- Afișează utilizarea intrărilor/ieșirilor pentru fiecare ID de proces:

`pidstat -d`

- Afișează informații despre un anumit PID:

`pidstat -p {{PID}}`

- Afișează statisticile de memorie pentru toate procesele al căror nume de comandă include "fox" sau "bird":

`pidstat -C "{{fox|bird}}" -r -p ALL`
