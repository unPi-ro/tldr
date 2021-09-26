# iwctl

> O unealtă în linie de comandă pentru a controla supplicantul de rețea iwd.
> Mai multe informații: <https://iwd.wiki.kernel.org/gettingstarted>.

- Pornește modul interactiv, în acest mod puteți introduce comenzile direct, cu autocompletare:

`iwctl`

- Apelați la ajutor general:

`iwctl --help`

- Afișați stațiile Wi-Fi:

`iwctl station list`

- Începeți să căutați rețele cu o stație:

`iwctl station {{station}} scan`

- Afișează rețelele găsite de o stație:

`iwctl station {{station}} get-networks`

- Conectați-vă la o rețea cu o stație; dacă sunt necesare acreditări, acestea vor fi solicitate:

`iwctl station {{station}} connect {{network_name}}`
