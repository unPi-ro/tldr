# sar

> Monitorizați performanța diferitelor subsisteme Linux.

- Raportează I/O și rata de transfer emise către dispozitivele fizice, una pe secundă (apăsați CTRL C pentru a ieși):

`sar -b {{1}}`

- Raportează un total de 10 statistici privind dispozitivele de rețea, una la fiecare 2 secunde:

`sar -n DEV {{2}} {{10}}`

- Raportează utilizarea CPU, una la fiecare 2 secunde:

`sar -u ALL {{2}}`

- Raportează un total de 20 de statistici de utilizare a memoriei, una pe secundă:

`sar -r ALL {{1}} {{20}}`

- Raportează media lungimii cozii de așteptare și a încărcăturii, una pe secundă:

`sar -q {{1}}`

- Raportează statisticile de paging, una la fiecare 5 secunde:

`sar -B {{5}}`
