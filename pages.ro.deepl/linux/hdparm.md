# hdparm

> Obțineți și setați parametrii hard disk-urilor SATA și IDE.
> Mai multe informații: <https://manned.org/hdparm>.

- Solicită informațiile de identificare a unui anumit dispozitiv:

`sudo hdparm -I /dev/{{device}}`

- Obțineți nivelul Advanced Power Management:

`sudo hdparm -B /dev/{{device}}`

- Setați valoarea Advanced Power Management (valorile 1-127 permit rotirea în jos, iar valorile 128-254 nu permit acest lucru):

`sudo hdparm -B {{1}} /dev/{{device}}`

- Afișează starea actuală a modului de alimentare a dispozitivului:

`sudo hdparm -C /dev/{{device}}`

- Forțează o unitate să intre imediat în modul de așteptare (de obicei, determină o unitate să se rotească în jos):

`sudo hdparm -y /dev/{{device}}`

- Treceți unitatea în modul inactiv (cu consum redus de energie), stabilind și timpul de așteptare:

`sudo hdparm -S {{standby_timeout}} {{device}}`
