# mocp

> Player audio Music on Console (MOC).
> Mai multe informații: <https://manned.org/mocp>.

- Lansați interfața de utilizare a terminalului MOC:

`mocp`

- Lansați interfața de utilizare a terminalului MOC într-un anumit director:

`mocp {{path/to/directory}}`

- Porniți serverul MOC în fundal, fără a lansa interfața de utilizare a terminalului MOC:

`mocp --server`

- Adăugați o anumită melodie la coada de redare în timp ce MOC se află în fundal:

`mocp --enqueue {{path/to/audio_file}}`

- Adăugați melodii în mod recursiv la coada de redare în timp ce MOC se află în fundal:

`mocp --append {{path/to/directory}}`

- Ștergeți coada de redare în timp ce MOC se află în fundal:

`mocp --clear`

- Redă sau oprește melodia aflată în coada de așteptare în timp ce MOC se află în fundal:

`mocp --{{play|stop}}`

- Opriți serverul MOC în timp ce se află în fundal:

`mocp --exit`
