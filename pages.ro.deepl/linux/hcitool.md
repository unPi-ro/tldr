# hcitool

> Monitorizați, configurați conexiunile și trimiteți comenzi speciale către dispozitivele Bluetooth.
> Mai multe informații: <https://manned.org/hcitool>.

- Scanați pentru dispozitive Bluetooth:

`hcitool scan`

- Afișează numele unui dispozitiv, returnând adresa MAC a acestuia:

`hcitool name {{bdaddr}}`

- Obțineți informații despre un dispozitiv Bluetooth la distanță:

`hcitool info {{bdaddr}}`

- Verificați calitatea legăturii cu un dispozitiv Bluetooth:

`hcitool lq {{bdaddr}}`

- Modificați nivelul puterii de transmisie:

`hcitool tpl {{bdaddr}} {{0|1}}`

- Afișați politica de legătură:

`hcitool lp`

- Solicită autentificarea cu un anumit dispozitiv:

`hcitool auth {{bdaddr}}`

- Afișează dispozitivele locale:

`hcitool dev`
