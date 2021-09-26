# collectd

> Daemon de colectare a statisticilor de sistem.
> Mai multe informații: <https://collectd.org/>.

- Afișează ajutorul de utilizare, inclusiv versiunea programului:

`collectd -h`

- Testați fișierul de configurare și apoi ieșiți:

`collectd -t`

- Testați funcționalitatea de colectare a datelor din plugin și apoi ieșiți:

`collectd -T`

- Începeți collectd:

`collectd`

- Specificați o locație personalizată a fișierului de configurare:

`collectd -C {{path/to/file}}`

- Specificați o locație personalizată a fișierului PID:

`collectd -P {{path/to/file}}`

- Nu te bifurca în fundal:

`collectd -f`
