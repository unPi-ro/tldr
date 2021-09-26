# nmon

> Un administrator de sistem, tuner și instrument de referință.

- Start nmon:

`nmon`

- Salvează înregistrările într-un fișier ("-s 300 -c 288" în mod implicit):

`nmon -f`

- Salvați înregistrările în fișier cu un total de 240 de măsurători, luând 30 de secunde între fiecare măsurătoare:

`nmon -f -s {{30}} -c {{240}}`
