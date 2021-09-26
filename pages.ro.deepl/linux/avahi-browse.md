# avahi-browse

> Afișează serviciile și gazdele expuse în rețeaua locală prin mDNS/DNS-SD.
> Avahi este compatibil cu Bonjour (Zeroconf), care se găsește în dispozitivele Apple.
> Mai multe informații: <https://www.avahi.org/>.

- Enumeră toate serviciile disponibile în rețeaua locală împreună cu adresele și porturile acestora, ignorându-le pe cele locale:

`avahi-browse --all --resolve --ignore-local`

- Enumerați toate domeniile:

`avahi-browse --browse-domains`

- Limitați căutarea la un anumit domeniu:

`avahi-browse --all --domain={{domain}}`
