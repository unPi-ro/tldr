# rig

> Utilitar pentru a pune laolaltă un nume, un prenume, un nume de familie, un număr de stradă și o adresă aleatorie, împreună cu un oraș, un stat, un cod poștal și un prefix de zonă care să corespundă din punct de vedere geografic (adică, toate se potrivesc cu aceeași zonă).
> Mai multe informații: <https://manpages.ubuntu.com/manpages/focal/man6/rig.6.html>.

- Afișați un nume aleatoriu (bărbat sau femeie) și o adresă:

`rig`

- Afișați un nume și o adresă aleatoare [m]ale (sau [f]emale):

`rig -{{m|f}}`

- Utilizează fișierele de date dintr-un anumit director (valoarea implicită este `/usr/share/rig`):

`rig -d {{path/to/directory}}`

- Afișează un anumit număr de identități:

`rig -c {{number}}`

- Afișarea unui anumit număr de identități feminine:

`rig -f -c {{number}}`
