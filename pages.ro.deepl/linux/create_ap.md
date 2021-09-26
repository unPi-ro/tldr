# create_ap

> Creați un AP (Access Point) pe orice canal.
> Mai multe informații: <https://github.com/oblique/create_ap>.

- Creați o rețea deschisă fără frază de acces:

`create_ap {{wlan0}} {{eth0}} {{access_point_ssid}}`

- Utilizați o frază de trecere WPA WPA2:

`create_ap {{wlan0}} {{eth0}} {{access_point_ssid}} {{passphrase}}`

- Creați un punct de acces fără partajare a internetului:

`create_ap -n {{wlan0}} {{acces_point_ssid}} {{passphrase}}`

- Creați o rețea punte cu partajare a internetului:

`create_ap -m bridge {{wlan0}} {{eth0}} {{access_point_ssid}} {{passphrase}}`

- Creați o rețea punte cu partajare Internet și o interfață punte pre-configurată:

`create_ap -m bridge {{wlan0}} {{br0}} {{access_point_ssid}} {{passphrase}}`

- Creați un port de acces pentru partajarea internetului din aceeași interfață Wi-Fi:

`create_ap {{wlan0}} {{wlan0}} {{access_point_ssid}} {{passphrase}}`

- Alegeți un alt driver pentru adaptorul Wi-Fi:

`create_ap --driver {{wifi_adapter}} {{wlan0}} {{eth0}} {{access_point_ssid}} {{passphrase}}`
