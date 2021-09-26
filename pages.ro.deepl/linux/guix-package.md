# guix package

> Instalarea, actualizarea și eliminarea pachetelor Guix sau revenirea la configurațiile anterioare.
> Mai multe informații: <https://guix.gnu.org/manual/html_node/Invoking-guix-package.html>.

- Instalați un nou pachet:

`guix package -i {{package_name}}`

- Îndepărtați un pachet:

`guix package -r {{package_name}}`

- Căutați în baza de date a pachetelor o expresie regulată:

`guix package -s "{{search_pattern}}"`

- Lista pachetelor instalate:

`guix package -I`

- Lista generațiilor:

`guix package -l`

- Reveniți la generația anterioară:

`guix package --roll-back`
