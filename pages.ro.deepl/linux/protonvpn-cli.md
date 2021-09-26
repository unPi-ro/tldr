# protonvpn-cli

> Client oficial pentru serviciul ProtonVPN din linia de comandă.
> Mai multe informații: <https://github.com/ProtonVPN/linux-cli>.

- Conectați-vă la contul ProtonVPN:

`protonvpn-cli login {{username}}`

- Porniți un kill switch la conectarea la ProtonVPN:

`protonvpn-cli killswitch --on`

- Conectați-vă la ProtonVPN în mod interactiv:

`protonvpn-cli connect`

- Afișează starea conexiunii:

`protonvpn-cli status`

- Blocați programele malware utilizând ProtonVPN NetShield:

`protonvpn-cli netshield --malware`

- Deconectați-vă de la ProtonVPN:

`protonvpn-cli disconnect`

- Afișează configurația ProtonVPN curentă:

`protonvpn-cli config --list`

- Afișează ajutorul pentru o subcomandă:

`protonvpn-cli {{subcommand}} --help`
