# veracrypt

> Software gratuit și cu sursă deschisă de criptare a discurilor.
> Mai multe informații: <https://www.veracrypt.fr/code/VeraCrypt/plain/doc/html/Documentation.html>.

- Creați un nou volum prin intermediul unei interfețe utilizator text și utilizați `/dev/urandom` ca sursă de date aleatoare:

`veracrypt --text --create --random-source={{/dev/urandom}}`

- Decriptați un volum în mod interactiv printr-o interfață text și montați-l într-un director:

`veracrypt --text {{path/to/volume}} {{path/to/mount_point}}`

- Decriptați o partiție folosind un fișier cheie și montați-o într-un director:

`veracrypt --keyfiles={{path/to/keyfile}} {{/dev/sdXN}} {{path/to/mount_point}}`

- Demontarea unui volum în directorul în care este montat:

`veracrypt --dismount {{path/to/mounted_point}}`
