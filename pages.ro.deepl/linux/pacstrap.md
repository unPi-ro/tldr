# pacstrap

> Scriptul de instalare Arch Linux pentru a instala pachetele în noul director rădăcină specificat.
> Mai multe informații: <https://man.archlinux.org/man/pacstrap.8>.

- Instalați pachetul `base`, kernelul Linux și firmware-ul pentru hardware-ul obișnuit:

`pacstrap {{path/to/new/root}} {{base}} {{linux}} {{linux-firmware}}`

- Instalați pachetul `base`, nucleul Linux LTS și instrumentele de construcție `base-devel`:

`pacstrap {{path/to/new/root}} {{base}} {{base-devel}} {{linux-lts}}`

- Instalați pachetele fără a copia lista de oglinzi a gazdei pe țintă:

`pacstrap -M {{path/to/new/root}} {{packages}}`

- Utilizați un fișier de configurare alternativ pentru Pacman:

`pacstrap -C {{path/to/pacman.conf}} {{path/to/new/root}} {{packages}}`

- Instalați pachetele utilizând memoria cache a pachetelor de pe gazdă și nu de pe țintă:

`pacstrap -c {{path/to/new/root}} {{packages}}`

- Instalarea pachetelor fără a copia pe țintă cheile pacman ale gazdei:

`pacstrap -G {{path/to/new/root}} {{packages}}`

- Instalarea pachetelor în modul interactiv (solicită confirmarea):

`pacstrap -i {{path/to/new/root}} {{packages}}`

- Instalați pachetele utilizând fișiere de pachete:

`pacstrap -U {{path/to/new/root}} {{path/to/package1}} {{path/to/package2}}`
