# ptx

> Generați un index permutat de cuvinte din unul sau mai multe fișiere text.
> Mai multe informații: <https://www.gnu.org/software/coreutils/ptx>.

- Generează un index permutat în care primul câmp al fiecărei linii este o referință de index:

`ptx --references {{path/to/file}}`

- Generarea unui index permutat cu referințe de index generate automat:

`ptx --auto-reference {{path/to/file}}`

- Generează un index permutat cu o lățime fixă:

`ptx --width={{width_in_columns}} {{path/to/file}}`

- Generează un index permutat cu o listă de cuvinte filtrate:

`ptx --only-file={{path/to/filter}} {{path/to/file}}`

- Generează un index permutat cu comportamente de tip SYSV:

`ptx --traditional {{path/to/file}}`
