# duperemove

> Găsește extente de sistem de fișiere duplicate și, opțional, le programează pentru deduplicare.
> O extensie este o mică parte a unui fișier din cadrul sistemului de fișiere.
> Pe unele sisteme de fișiere, o extensie poate fi menționată de mai multe ori, atunci când părți din conținutul fișierelor sunt identice.
> Mai multe informații: <https://markfasheh.github.io/duperemove/>.

- Căutați extents duplicate într-un director și afișați-le:

`duperemove -r {{path/to/directory}}`

- Deduplicați extents duplicate pe un sistem de fișiere Btrfs sau XFS (experimental):

`duperemove -r -d {{path/to/directory}}`

- Folosiți un fișier hash pentru a stoca hașurile de extensie (mai puțină memorie utilizată și poate fi reutilizat la rulări ulterioare):

`duperemove -r -d --hashfile={{path/to/hashfile}} {{path/to/directory}}`

- Limitați firele de intrare/ieșire/ieșire (pentru etapa de hashing și deducere) și firele CPU (pentru etapa de căutare a extensiilor duplicate):

`duperemove -r -d --hashfile={{path/to/hashfile}} --io-threads={{N}} --cpu-threads={{N}} {{path/to/directory}}`
