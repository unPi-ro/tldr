# pihole

> Interfață terminală pentru serverul DNS de blocare a anunțurilor Pi-hole.
> Mai multe informații: <https://pi-hole.net>.

- Verificați starea daemonului Pi-hole:

`pihole status`

- Actualizare Pi-hole:

`pihole updatePihole`

- Monitorizați starea detaliată a sistemului:

`pihole chronometer`

- Porniți sau opriți demonul:

`pihole {{enable|disable}}`

- Reporniți demonul (nu serverul în sine):

`pihole restartdns`

- Lista albă sau lista neagră a unui domeniu:

`pihole {{whitelist|blacklist}} {{example.com}}`

- Căutați un domeniu în liste:

`pihole query {{example.com}}`

- Deschideți un jurnal în timp real al conexiunilor:

`pihole tail`
