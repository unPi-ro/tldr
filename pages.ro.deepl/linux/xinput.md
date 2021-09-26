# xinput

> Listați dispozitivele de intrare disponibile, interogați informații despre un dispozitiv și modificați setările dispozitivului de intrare.

- Enumeră toate dispozitivele de intrare:

`xinput list`

- Dezactivează o intrare:

`xinput disable {{id}}`

- Activează o intrare:

`xinput enable {{id}}`

- Deconectează o intrare de la magistrala sa:

`xinput float {{id}}`

- Reatașați o intrare ca sclav la un maestru:

`xinput reattach {{id}} {{master_id}}`

- Listează setările unui dispozitiv de intrare:

`xinput list-props {{id}}`

- Modificați o setare a unui dispozitiv de intrare:

`xinput set-prop {{id}} {{setting_id}} {{value}}`
