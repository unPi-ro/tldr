# gdebi

> Un instrument simplu pentru a instala fișiere `.deb`.
> Mai multe informații: <https://www.commandlinux.com/man-page/man1/gdebi.1.html>.

- Instalează pachetele locale `.deb`, rezolvând și instalând dependențele sale:

`gdebi {{path/to/package.deb}}`

- Afișează versiunea programului:

`gdebi --version`

- Nu afișați informații privind progresul:

`gdebi {{path/to/package.deb}} --quiet`

- Setați o opțiune de configurare APT:

`gdebi {{path/to/package.deb}} --option={{APT_OPTS}}`

- Folosiți directorul rădăcină alternativ:

`gdebi {{path/to/package.deb}} --root={{path/to/root_dir}}`
