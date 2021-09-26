# macchanger

> Utilitar în linie de comandă pentru manipularea adreselor MAC ale interfețelor de rețea.
> Mai multe informații: <https://manned.org/macchanger>.

- Vizualizați adresele MAC curente și permanente ale unei interfețe:

`macchanger --show {{interface}}`

- Setați interfața pe un MAC aleatoriu:

`macchanger --random {{interface}}`

- Setați interfața pe un anumit MAC:

`macchanger --mac {{XX:XX:XX:XX:XX:XX}} {{interface}}`

- Resetează interfața la MAC hardware-ul său permanent:

`macchanger --permanent {{interface}}`
