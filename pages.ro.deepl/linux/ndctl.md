# ndctl

> Utilitar pentru gestionarea modulelor DIMM non volatile.

- Crearea unui spațiu de nume de mod "fsdax":

`ndctl create-namespace --mode={{fsdax}}`

- Schimbă modul unui spațiu de nume în "raw":

`ndctl create-namespace --reconfigure={{namespaceX.Y}} --mode={{raw}}`

- Verifică un spațiu de nume în modul sector pentru consecvență și îl repară dacă este necesar:

`ndctl check-namespace --repair {{namespaceX.Y}}`

- Enumeră toate spațiile de nume, regiunile și autobuzele (inclusiv cele dezactivate):

`ndctl list --namespaces --regions --buses --idle`

- Listați un spațiu de nume specific și includeți o mulțime de informații suplimentare:

`ndctl list -vvv --namespace={{namespaceX.Y}}`

- Rulați un monitor pentru a urmări evenimentele de sănătate SMART pentru NVDIMM-urile de pe magistrala "ACPI.NFIT":

`ndctl monitor --bus={{ACPI.NFIT}}`

- Elimină un spațiu de nume (dacă este cazul) sau îl readuce la o stare inițială:

`ndctl destroy-namespace --force {{namespaceX.Y}}`
