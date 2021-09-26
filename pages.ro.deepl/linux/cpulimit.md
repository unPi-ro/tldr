# cpulimit

> Un instrument pentru a limita utilizarea CPU a altor procese.
> Mai multe informații: <http://cpulimit.sourceforge.net/>.

- Limitați un proces existent cu PID 1234 pentru a utiliza doar 25% din CPU:

`cpulimit --pid {{1234}} --limit {{25%}}`

- Limitează un program existent după numele său executabil:

`cpulimit --exe {{program}} --limit {{25}}`

- Lansați un anumit program și limitați-l să utilizeze doar 50% din CPU:

`cpulimit --limit {{50}} -- {{program arg1 arg2 ...}}`

- Lansarea unui program, limitarea utilizării CPU la 50
și rulați cpulimit în fundal:

`cpulimit --limit {{50}} --background -- {{program}}`

- Opriți procesul acestuia dacă utilizarea CPU a programului depășește 50%:

`cpulimit --limit 50 --kill -- {{program}}`

- Regulați atât acest proces, cât și procesele sale copil, astfel încât niciunul să nu depășească 25 de unități de măsură:

`cpulimit --limit {{25}} --monitor-forks -- {{program}}`
