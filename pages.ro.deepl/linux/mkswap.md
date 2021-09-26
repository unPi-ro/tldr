# mkswap

> Configurați o zonă de swap Linux pe un dispozitiv sau într-un fișier.
> Mai multe informații: <https://manned.org/mkswap>.

- Configurați o anumită partiție ca zonă de swap:

`sudo mkswap {{/dev/sdb7}}`

- Utilizează un fișier dat ca zonă de swap:

`sudo mkswap {{path/to/file}}`

- Verificați dacă există blocuri defecte pe o partiție înainte de a crea zona de swap:

`sudo mkswap -c {{/dev/sdb7}}`

- Specificați o etichetă pentru fișier (pentru a permite lui `swapon` să folosească eticheta):

`sudo mkswap -L {{swap1}} {{path/to/file}}`
