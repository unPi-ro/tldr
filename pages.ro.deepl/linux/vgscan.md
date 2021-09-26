# vgscan

> Scanați pentru grupuri de volume pe toate dispozitivele de bloc Logical Volume Manager (LVM) acceptate.
> Vezi și `lvm`, `vgchange`.
> Mai multe informații: <https://manned.org/vgscan>.

- Scanează pentru grupuri de volume și tipărește informații despre fiecare grup găsit:

`sudo vgscan`

- Scanarea grupurilor de volume și adăugarea fișierelor speciale în `/dev`, dacă acestea nu există deja, necesare pentru a accesa volumele logice din grupurile găsite:

`sudo vgscan --mknodes`
