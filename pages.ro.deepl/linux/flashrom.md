# flashrom

> Citirea, scrierea, verificarea și ștergerea cipurilor flash.
> Mai multe informații: <https://manned.org/flashrom>.

- Sondați cipul, asigurându-vă că cablarea este corectă:

`flashrom --programmer {{programmer}}`

- Citiți flash-ul și salvați-l într-un fișier:

`flashrom -p {{programmer}} --read {{path/to/file}}`

- Scrieți un fișier în memoria flash:

`flashrom -p {{programmer}} --write {{path/to/file}}`

- Verificarea flash-ului în raport cu un fișier:

`flashrom -p {{programmer}} --verify {{path/to/file}}`

- Sondați cipul cu ajutorul Raspberry Pi:

`flashrom -p {{linux_spi:dev=/dev/spidev0.0}}`
