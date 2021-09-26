# protonvpn-cli connect

> Client oficial pentru a vă conecta la ProtonVPN din linia de comandă.
> Mai multe informații: <https://protonvpn.com/support/linux-vpn-setup/>.

- Conectați-vă la ProtonVPN în mod interactiv:

`protonvpn-cli connect`

- Conectați-vă la ProtonVPN utilizând cel mai rapid server disponibil:

`protonvpn-cli connect --fastest`

- Conectați-vă la ProtonVPN utilizând un anumit server cu un anumit protocol:

`protonvpn-cli connect {{server_name}} --protocol {{udp|tcp}}`

- Conectați-vă la ProtonVPN utilizând un server aleatoriu cu un protocol specific:

`protonvpn-cli connect --random --protocol {{udp|tcp}}`

- Conectați-vă la ProtonVPN utilizând cel mai rapid server care acceptă Tor:

`protonvpn-cli connect --tor`

- Ajutor pentru afișare:

`protonvpn connect --help`
