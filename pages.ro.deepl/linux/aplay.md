# aplay

> Player de sunet în linie de comandă pentru driverul de placă de sunet ALSA.
> Mai multe informații: <https://manned.org/aplay>.

- Redă un fișier specific (rata de eșantionare, adâncimea de biți etc. vor fi determinate automat pentru formatul de fișier):

`aplay {{path/to/file}}`

- Redă primele 10 secunde ale unui anumit fișier la 2500 Hz:

`aplay --duration={{10}} --rate={{2500}} {{path/to/file}}`

- Redați fișierul brut ca fișier Mu-Law `.au` de 22050 Hz, mono, pe 8 biți:

`aplay --channels={{1}} --file-type {{raw}} --rate={{22050}} --format={{mu_law}} {{path/to/file}}`
