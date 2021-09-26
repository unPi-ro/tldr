# pacman-mirrors

> Generați o listă oglindă pacman pentru Manjaro Linux.
> Fiecare rulare a pacman-mirrors vă cere să vă sincronizați baza de date și să vă actualizați sistemul folosind `sudo pacman -Syyu`.
> Mai multe informații: <https://wiki.manjaro.org/index.php?title=Pacman-mirrors>.

- Generați o listă de oglinzi utilizând setările implicite:

`sudo pacman-mirrors --fasttrack`

- Obține starea oglinzilor curente:

`pacman-mirrors --status`

- Afișează ramura curentă:

`pacman-mirrors --get-branch`

- Treceți la o altă sucursală:

`sudo pacman-mirrors --api --set-branch {{stable|unstable|testing}}`

- Generați o listă de oglinzi, folosind doar oglinzile din țara dumneavoastră:

`sudo pacman-mirrors --geoip`
