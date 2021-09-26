# legit

> Interfață complementară de linie de comandă pentru Git.
> Mai multe informații: <https://frostming.github.io/legit>.

- Treceți la o ramură specificată, stocând și restabilind modificările neetajate:

`git switch {{target_branch}}`

- Sincronizarea ramurii curente, fuzionarea sau rebasarea automată, precum și stashing și unstashing:

`git sync`

- Publică o ramură specificată pe serverul de la distanță:

`git publish {{branch_name}}`

- Îndepărtați o ramură de pe serverul de la distanță:

`git unpublish {{branch_name}}`

- Enumerați toate ramurile și statutul lor de publicare:

`git branches {{glob_pattern}}`

- Elimină ultima confirmare din istoric:

`git undo {{--hard}}`
