# lxi

> Controlați instrumentele compatibile LXI, cum ar fi osciloscoapele.
> Mai multe informații: <https://github.com/lxi-tools/lxi-tools>.

- Descoperiți dispozitivele LXI în rețelele disponibile:

`lxi discover`

- Capturați o captură de ecran, detectând automat un plugin:

`lxi screenshot --address {{ip_address}}`

- Captură o captură de ecran folosind un plugin specificat:

`lxi screenshot --address {{ip_address}} --plugin {{rigol-1000z}}`

- Trimiteți o comandă SCPI către un instrument:

`lxi scpi --address {{ip_address}} "{{*IDN?}}"`

- Executați un test de referință pentru performanța cererilor și a răspunsurilor:

`lxi benchmark --address {{ip_address}}`
