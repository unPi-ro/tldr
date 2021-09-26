# top

> Afișați informații dinamice în timp real despre procesele în curs de desfășurare.
> Mai multe informații: <https://manned.org/top>.

- Începeți de sus:

`top`

- Nu afișați niciun proces inactiv sau zombie:

`top -i`

- Afișează numai procesele deținute de un anumit utilizator:

`top -u {{username}}`

- Sortează procesele în funcție de un câmp:

`top -o {{field_name}}`

- Afișează firele individuale ale unui anumit proces:

`top -Hp {{process_id}}`

- Afișează numai procesele cu PID-ul (PID-urile) dat(e), transmis(e) ca o listă separată prin virgulă. (În mod normal, nu trebuie să cunoașteți PID-urile din mers. Acest exemplu selectează PID-urile din numele procesului):

`top -p $(pgrep -d ',' {{process_name}})`

- Obțineți ajutor cu privire la comenzile interactive:

`?`
