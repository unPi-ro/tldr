# rfkill

> Activați și dezactivați dispozitivele fără fir.

- Lista de dispozitive:

`rfkill`

- Filtrați după coloane:

`rfkill -o {{ID,TYPE,DEVICE}}`

- Blocați dispozitivele în funcție de tip (de exemplu, bluetooth, wlan):

`rfkill block {{bluetooth}}`

- Deblocați dispozitivele în funcție de tip (de exemplu, bluetooth, wlan):

`rfkill unblock {{wlan}}`

- Ieșire în format JSON:

`rfkill -J`
