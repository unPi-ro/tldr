# pidof

> Obține ID-ul unui proces folosind numele acestuia.

- Listează toate ID-urile de proces cu numele dat:

`pidof {{bash}}`

- Listează un singur ID de proces cu numele dat:

`pidof -s {{bash}}`

- Listează ID-urile proceselor, inclusiv scripturile cu numele dat:

`pidof -x {{script.py}}`

- Ucide toate procesele cu numele dat:

`kill "$(pidof {{name}})" `
