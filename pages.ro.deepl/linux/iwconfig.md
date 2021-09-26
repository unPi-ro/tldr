# iwconfig

> Configurați și afișați parametrii unei interfețe de rețea fără fir.
> Mai multe informații: <https://manned.org/iwconfig>.

- Afișează parametrii și statisticile tuturor interfețelor:

`iwconfig`

- Afișează parametrii și statisticile interfeței specificate:

`iwconfig {{interface}}`

- Setează ESSID (numele rețelei) al interfeței specificate (de exemplu, eth0 sau wlp2s0):

`iwconfig {{interface}} {{new_network_name}}`

- Setează modul de operare al interfeței specificate:

`iwconfig {{interface}} mode {{ad hoc|Managed|Master|Repeater|Secondary|Monitor|Auto}}`
