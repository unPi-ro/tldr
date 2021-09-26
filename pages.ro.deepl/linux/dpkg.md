# dpkg

> Managerul de pachete Debian.
> Unele subcomandă, cum ar fi `dpkg deb`, au propria lor documentație de utilizare.
> Mai multe informații: <https://manpages.debian.org/buster/dpkg/dpkg.1.en.html>.

- Instalați un pachet:

`dpkg -i {{path/to/file.deb}}`

- Îndepărtați un pachet:

`dpkg -r {{package_name}}`

- Lista pachetelor instalate:

`dpkg -l {{pattern}}`

- Enumeră conținutul unui pachet:

`dpkg -L {{package_name}}`

- Listează conținutul unui fișier de pachete locale:

`dpkg -c {{path/to/file.deb}}`

- Aflați ce pachet deține un fișier:

`dpkg -S {{filename}}`
