# dget

> Descărcați pachetele Debian.
> Mai multe informații: <https://manpages.debian.org/dget>.

- Descărcați un pachet binar:

`dget {{package_name}}`

- Descărcați și extrageți sursa unui pachet din fișierul `.dsc` al acestuia:

`dget {{http://deb.debian.org/debian/pool/main/h/haskell-tldr/haskell-tldr_0.4.0-2.dsc}}`

- Descărcați un pachet sursă tarball din fișierul `.dsc`, dar nu-l extrageți:

`dget -d {{http://deb.debian.org/debian/pool/main/h/haskell-tldr/haskell-tldr_0.4.0-2.dsc}}`
