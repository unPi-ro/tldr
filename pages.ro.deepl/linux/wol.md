# wol

> Client pentru trimiterea pachetelor magice Wake-on-LAN.
> Mai multe informații: <https://sourceforge.net/projects/wake-on-lan/>.

- Trimite un pachet WoL către un dispozitiv:

`wol {{mac_address}}`

- Trimiteți un pachet WoL către un dispozitiv din altă subrețea pe baza IP-ului acestuia:

`wol --ipaddr={{ip_address}} {{mac_address}}`

- Trimiteți un pachet WoL către un dispozitiv din altă subrețea pe baza numelui de gazdă al acestuia:

`wol --host={{hostname}} {{mac_address}}`

- Trimite un pachet WoL către un anumit port al unei gazde:

`wol --port={{port_number}} {{mac_address}}`

- Citiți adresele hardware, adresele IP/numele de gazdă, porturile opționale și parolele SecureON dintr-un fișier:

`wol --file={{path/to/file}}`

- Activați ieșirea verbose:

`wol --verbose {{mac_address}}`
