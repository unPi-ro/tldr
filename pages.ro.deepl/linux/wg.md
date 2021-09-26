# wg

> Gestionați configurația interfețelor WireGuard.
> Mai multe informații: <https://www.wireguard.com/quickstart/>.

- Verifică starea interfețelor active în prezent:

`sudo wg`

- Imprimați o nouă cheie privată:

`wg genkey`

- Imprimă o nouă cheie publică:

`echo {{private_key}} | wg pubkey`

- Generați o cheie publică și una privată:

`wg genkey | tee {{privatekey.txt}} | wg pubkey > {{publickey.txt}}`
