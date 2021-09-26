# dmesg

> Scrieți mesajele kernelului pe ieșirea standard.
> Mai multe informații: <https://manned.org/dmesg>.

- Afișează mesajele kernelului:

`dmesg`

- Afișează mesajele de eroare ale kernelului:

`dmesg --level err`

- Afișează mesajele kernelului și continuă să citească mesajele noi, similar cu `tail -f` (disponibil în kernel-urile 3.5.0 și mai noi):

`dmesg -w`

- Afișează câtă memorie fizică este disponibilă pe acest sistem:

`dmesg | grep -i memory`

- Afișează mesajele kernelului, câte o pagină pe rând:

`dmesg | less`

- Afișează mesajele kernelului cu o marcă de timp (disponibil în kernel-urile 3.5.0 și mai noi):

`dmesg -T`

- Afișează mesajele kernelului într-o formă lizibilă pentru oameni (disponibil în kernel-urile 3.5.0 și mai noi):

`dmesg -H`

- Colorize output (disponibil în kernel-urile 3.5.0 și mai noi):

`dmesg -L`
