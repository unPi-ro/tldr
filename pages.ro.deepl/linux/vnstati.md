# vnstati

> Suport pentru ieșirea imaginilor PNG pentru vnStat.
> Mai multe informații: <https://manned.org/vnstati>.

- Afișează un rezumat al ultimelor 2: luni, zile și tot timpul:

`vnstati --summary --iface {{network_interface}} --output {{path/to/output.png}}`

- Realizați cele mai aglomerate 10 zile cu cel mai mare trafic din toate timpurile:

`vnstati --top10 --iface {{network_interface}} --output {{path/to/output.png}}`

- Afișează statisticile lunare de trafic din ultimele 12 luni:

`vnstati --months --iface {{network_interface}} --output {{path/to/output.png}}`

- Afișează statisticile orare de trafic din ultimele 24 de ore:

`vnstati --hours --iface {{network_interface}} --output {{path/to/output.png}}`
