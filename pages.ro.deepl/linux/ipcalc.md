# ipcalc

> Efectuarea de operații și calcule simple privind adresele IP și rețelele.
> Mai multe informații: <https://manned.org/ipcalc>.

- Afișează informații despre o adresă sau o rețea cu o anumită mască de subrețea:

`ipcalc {{1.2.3.4}} {{255.255.255.0}}`

- Afișează informații despre o adresă sau o rețea în notație CIDR:

`ipcalc {{1.2.3.4}}/{{24}}`

- Afișează adresa de difuzare a unei adrese sau rețele:

`ipcalc -b {{1.2.3.4}}/{{30}}`

- Afișează adresa de rețea a adresei IP și a măștii de rețea furnizate:

`ipcalc -n {{1.2.3.4}}/{{24}}`

- Afișează informații geografice despre o anumită adresă IP:

`ipcalc -g {{1.2.3.4}}`
