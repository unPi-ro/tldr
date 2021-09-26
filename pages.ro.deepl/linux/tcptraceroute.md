# tcptraceroute

> O implementare traceroute folosind pachete TCP.
> Mai multe informații: <https://github.com/mct/tcptraceroute>.

- Urmăriți traseul către o gazdă:

`tcptraceroute {{host}}`

- Specificați portul de destinație și lungimea pachetului în octeți:

`tcptraceroute {{host}} {{destination_port}} {{packet_length}}`

- Specificați portul sursă local și adresa sursă:

`tcptraceroute {{host}} -p {{source_port}} -s {{source_address}}`

- Setați primul și maximul TTL:

`tcptraceroute {{host}} -f {{first_ttl}} -m {{max_ttl}}`

- Specificați timpul de așteptare și numărul de interogări pe salt:

`tcptraceroute {{host}} -w {{wait_time}} -q {{number_of_queries}}`

- Specificați interfața:

`tcptraceroute {{host}} -i {{interface}}`
