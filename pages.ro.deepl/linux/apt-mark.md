# apt-mark

> Utilitar pentru a schimba starea pachetelor instalate.
> Mai multe informații: <https://manpages.debian.org/latest/apt/apt-mark.8.html>.

- Marcați un pachet ca fiind instalat automat:

`sudo apt-mark auto {{package_name}}`

- Menține un pachet la versiunea sa curentă și împiedică actualizările acestuia:

`sudo apt-mark hold {{package_name}}`

- Permiteți ca un pachet să fie actualizat din nou:

`sudo apt-mark unhold {{package_name}}`

- Afișează pachetele instalate manual:

`apt-mark showmanual`

- Afișează pachetele reținute care nu sunt actualizate:

`apt-mark showhold`
