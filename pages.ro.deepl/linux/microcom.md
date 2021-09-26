# microcom

> Un program minimalist de terminal, utilizat pentru a accesa dispozitive la distanță prin intermediul unei conexiuni seriale, CAN sau telnet de la consolă.
> Mai multe informații: <https://manned.org/microcom>.

- Deschideți un port serial utilizând viteza de transmisie specificată:

`microcom --port {{path/to/serial_port}} --speed {{baud_rate}}`

- Stabilește o conexiune telnet la gazda specificată:

`microcom --telnet {{hostname}}:{{port}}`
