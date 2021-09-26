# tshark

> Instrument de analiză a pachetelor, versiunea CLI a Wireshark.
> Mai multe informații: <https://tshark.dev/>.

- Monitorizați totul pe localhost:

`tshark`

- Capturați numai pachetele care corespund unui anumit filtru de captură:

`tshark -f '{{udp port 53}}'`

- Afișează numai pachetele care corespund unui anumit filtru de ieșire:

`tshark -Y '{{http.request.method == "GET"}}'`

- Decodarea unui port TCP utilizând un anumit protocol (de exemplu, HTTP):

`tshark -d tcp.port=={{8888}},{{http}}`

- Specificați formatul de ieșire capturat:

`tshark -T {{json|text|ps|…}}`

- Selectați câmpurile specifice pentru a ieși:

`tshark -T {{fields|ek|json|pdml}} -e {{http.request.method}} -e {{ip.src}}`

- Scrie pachetul capturat într-un fișier:

`tshark -w {{path/to/file}}`

- Analizați pachetele dintr-un fișier:

`tshark -r {{filename}}.pcap`
