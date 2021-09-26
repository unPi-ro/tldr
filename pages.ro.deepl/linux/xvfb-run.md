# xvfb-run

> Executați o comandă într-un mediu virtual de server X.
> Mai multe informații: <https://www.x.org/wiki/>.

- Executați comanda specificată într-un server X virtual:

`xvfb-run {{command}}`

- Încercați să obțineți un număr de server liber, dacă numărul implicit (99) nu este disponibil:

`xvfb-run --auto-servernum {{command}}`

- Transmite argumente către serverul Xvfb:

`xvfb-run --server-args "{{-screen 0 1024x768x24}}" {{command}}`
