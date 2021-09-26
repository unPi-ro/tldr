# lxc

> Gestionați containerele Linux utilizând API-ul REST lxd.
> Orice nume sau model de container poate fi prefixat cu numele unui server la distanță.
> Mai multe informații: <https://manned.org/lxc>.

- Lista containerelor locale care corespund unui șir de caractere. Omiteți șirul pentru a lista toate containerele locale:

`lxc list {{match_string}}`

- Lista imaginilor care corespund unui șir de caractere. Omiteți șirul pentru a lista toate imaginile:

`lxc image list [{{remote}}:]{{match_string}}`

- Creați un nou container dintr-o imagine:

`lxc init [{{remote}}:]{{image}} {{container}}`

- Începeți un container:

`lxc start [{{remote}}:]{{container}}`

- Opriți un container:

`lxc stop [{{remote}}:]{{container}}`

- Afișează informații detaliate despre un container:

`lxc info [{{remote}}:]{{container}}`

- Faceți o fotografie instantanee a unui container:

`lxc snapshot [{{remote}}:]{{container}} {{snapshot}}`
