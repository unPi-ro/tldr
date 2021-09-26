# reflector

> Arch script pentru a prelua și sorta listele de oglinzi.

- Obțineți toate oglinzile, sortați-le în funcție de viteza de descărcare și salvați-le:

`sudo reflector --sort {{rate}} --save {{/etc/pacman.d/mirrorlist}}`

- Obțineți numai oglinzi HTTPS germane:

`reflector --country {{Germany}} --protocol {{https}}`

- Obțineți doar cele 10 oglinzi recent sincronizate:

`reflector --latest {{10}}`
