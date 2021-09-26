# unset

> Eliminați variabilele sau funcțiile de shell.
> Mai multe informații: <https://manned.org/unset>.

- Eliminați variabila `foo` sau, dacă variabila nu există, eliminați funcția `foo`:

`unset {{foo}}`

- Eliminați variabilele foo și bar:

`unset -v {{foo}} {{bar}}`

- Eliminați funcția my_func:

`unset -f {{my_func}}`
