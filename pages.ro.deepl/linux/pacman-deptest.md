# pacman --deptest

> Verifică fiecare dependență specificată și returnează o listă de dependențe care nu sunt satisfăcute în prezent în sistem.
> Mai multe informații: <https://man.archlinux.org/man/pacman.8>.

- Tipărește numele pachetelor de dependențe care nu sunt instalate:

`pacman --deptest {{package_name1}} {{package_name2}}`

- Verifică dacă pachetul instalat corespunde versiunii minime date:

`pacman --deptest "{{bash>=5}}"`

- Verifică dacă este instalată o versiune ulterioară a unui pachet:

`pacman --deptest "{{bash>5}}"`

- Ajutor pentru afișare:

`pacman --deptest --help`
