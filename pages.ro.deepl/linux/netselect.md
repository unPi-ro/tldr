# netselect

> Test de viteză pentru alegerea unui server de rețea rapid.
> Mai multe informații: <https://github.com/apenwarr/netselect>.

- Alegeți serverul cu cea mai mică latență:

`sudo netselect {{host_1}} {{host_2}}`

- Afișează rezoluția și statisticile serverului de nume:

`sudo netselect -vv {{host_1}} {{host_2}}`

- Definiți TTL (time to live) maxim:

`sudo netselect -m {{10}} {{host_1}} {{host_2}}`

- Imprimă cele mai rapide N servere dintre gazde:

`sudo netselect -s {{N}} {{host_1}} {{host_2}} {{host_3}}`

- Enumerați opțiunile disponibile:

`netselect`
