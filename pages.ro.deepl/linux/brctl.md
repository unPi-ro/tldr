# brctl

> Administrarea punților Ethernet.
> Mai multe informații: <https://manned.org/brctl>.

- Afișează o listă cu informații despre punțile Ethernet existente în prezent:

`sudo brctl show`

- Creați o nouă interfață de punte Ethernet:

`sudo brctl add {{bridge_name}}`

- Ștergeți o interfață de punte Ethernet existentă:

`sudo brctl del {{bridge_name}}`

- Adăugați o interfață la o punte existentă:

`sudo brctl addif {{bridge_name}} {{interface_name}}`

- Îndepărtați o interfață de pe o punte existentă:

`sudo brctl delif {{bridge_name}} {{interface_name}}`
