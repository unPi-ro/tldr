# partprobe

> Notifică nucleul sistemului de operare cu privire la modificările tabelei de partiții.
> Mai multe informații: <https://manned.org/partprobe>.

- Notifică nucleul sistemului de operare cu privire la modificările tabelei de partiții:

`sudo partprobe`

- Notifică kernelul cu privire la modificările tabelei de partiții și afișează un rezumat al dispozitivelor și al partițiilor acestora:

`sudo partprobe --summary`

- Afișează un rezumat al dispozitivelor și al partițiilor lor, dar nu notifică kernelul:

`sudo partprobe --summary --dry-run`
