# named

> Executați daemonul serverului DNS (Dynamic Name Service) care convertește numele de gazdă în adrese IP și invers.
> Mai multe informații: <https://manned.org/named>.

- Citește fișierul de configurare implicită `/etc/named.conf`, citește toate datele inițiale și ascultă interogările:

`named`

- Citiți un fișier de configurare personalizat:

`named -c {{path/to/named.conf}}`

- Utilizați numai IPv4 sau IPv6, chiar dacă mașina gazdă poate utiliza alte protocoale:

`named {{-4|-6}}`

- Ascultați interogările pe un port specific în loc de portul implicit 53:

`named -p {{port}}`

- Rulați serverul în prim-plan și nu îl utilizați ca daemon:

`named -f`
