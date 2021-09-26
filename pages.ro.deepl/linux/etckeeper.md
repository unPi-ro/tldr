# etckeeper

> Urmăriți fișierele de configurare a sistemului în Git.
> Mai multe informații: <http://etckeeper.branchable.com/>.

- Configurați un repo Git și efectuați diverse sarcini de configurare (se execută din `/etc`):

`sudo etckeeper init`

- Trimiteți toate modificările în `/etc`:

`sudo etckeeper commit {{message}}`

- Executați comenzi Git arbitrare:

`sudo etckeeper vcs {{status}}`

- Verifică dacă există modificări neangajate (returnează doar un cod de ieșire):

`sudo etckeeper unclean`

- Distrugeți repo-ul existent și nu mai urmăriți modificările:

`sudo etckeeper uninit`
