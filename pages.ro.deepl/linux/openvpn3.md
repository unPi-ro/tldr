# openvpn3

> OpenVPN 3 Linux client.
> Mai multe informații: <https://community.openvpn.net/openvpn/wiki/OpenVPN3Linux>.

- Începeți o nouă sesiune VPN:

`openvpn3 session-start --config {{path/to/config.conf}}`

- Lista sesiunilor stabilite:

`openvpn3 sessions-list`

- Deconectează sesiunea stabilită în prezent, începută cu configurația dată:

`openvpn3 session-manage --config {{path/to/config.conf}} --disconnect`

- Importați configurația VPN:

`openvpn3 config-import --config {{path/to/config.conf}}`

- Lista configurațiilor importate:

`openvpn3 configs-list`
