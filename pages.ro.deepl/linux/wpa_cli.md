# wpa_cli

> Adăugați și configurați interfețe wlan.

- Căutați rețelele disponibile:

`wpa_cli scan`

- Afișați rezultatele scanării:

`wpa_cli scan_results`

- Adăugați o rețea:

`wpa_cli add_network {{number}}`

- Setați SSID-ul unei rețele:

`wpa_cli set_network {{number}} ssid "{{SSID}}"`

- Activează rețeaua:

`wpa_cli enable_network {{number}}`

- Salvați configurația:

`wpa_cli save_config`
