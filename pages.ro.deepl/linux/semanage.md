# semanage

> Instrumentul de gestionare a politicilor SELinux.
> Mai multe informații: <https://manned.org/semanage>.

- Particularizări locale de ieșire:

`semanage -S {{store}} -o {{path/to/output_file}}`

- Preia un set de comenzi dintr-un fișier specificat și le încarcă într-o singură tranzacție:

`semanage -S {{store}} -i {{path/to/input_file}}`

- Gestionați booleeni. Booleanele permit administratorului să modifice confinarea proceselor pe baza configurației curente:

`semanage boolean -S {{store}} {{--delete|--modify|--list|--noheading|--deleteall}} {{-on|-off}} -F {{boolean|boolean_file}}`

- Gestionați modulele de politici:

`semanage module -S {{store}} {{--add|--delete|--list|--modify}} {{--enable|--disable}} {{module_name}}`

- Dezactivați/activați regulile de dontaudit din politică:

`semanage dontaudit -S {{store}} {{on|off}}`
