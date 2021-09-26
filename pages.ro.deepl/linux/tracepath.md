# tracepath

> Urmăriți calea către o gazdă de rețea și descoperiți MTU de-a lungul acestei căi.
> Mai multe informații: <https://manned.org/tracepath>.

- O modalitate preferată de urmărire a traseului către o gazdă:

`tracepath -p {{33434}} {{host}}`

- Specificați portul de destinație inițial, util în cazul unor setări de firewall non-standard:

`tracepath -p {{destination_port}} {{host}} `

- Tipărește atât numele de gazdă, cât și adresele IP numerice:

`tracepath -b {{host}}`

- Specificați un TTL (număr maxim de salturi):

`tracepath -m {{max_hops}} {{host}}`

- Specificați lungimea inițială a pachetului (valoarea implicită este 65535 pentru IPv4 și 128000 pentru IPv6):

`tracepath -l {{packet_length}} {{host}}`

- Utilizați numai adrese IPv6:

`tracepath -6 {{host}}`
