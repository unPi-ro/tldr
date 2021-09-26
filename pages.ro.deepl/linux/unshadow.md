# unshadow

> Utilitar furnizat de proiectul John the Ripper pentru a obține fișierul tradițional de parole Unix dacă sistemul folosește parolele de tip "shadow".
> Mai multe informații: <https://www.openwall.com/john/>.

- Combină `/etc/shadow` și `/etc/passwd` ale sistemului actual:

`sudo unshadow /etc/passwd /etc/shadow`

- Combinați două fișiere arbitrare de umbre și parole:

`sudo unshadow {{path/to/passwd}} {{path/to/shadow}}`
