# strace

> Instrument de depanare pentru urmărirea apelurilor de sistem.

- Începe urmărirea unui anumit proces în funcție de PID-ul acestuia:

`strace -p {{pid}}`

- Urmăriți un proces și filtrați ieșirea în funcție de apelul de sistem:

`strace -p {{pid}} -e {{system_call_name}}`

- Numără timpul, apelurile și erorile pentru fiecare apel de sistem și raportează un rezumat la ieșirea din program:

`strace -p {{pid}} -c`

- Afișează timpul petrecut în fiecare apel de sistem:

`strace -p {{pid}} -T`

- Începeți urmărirea unui program prin execuția acestuia:

`strace {{program}}`

- Începe urmărirea operațiunilor de urmărire a fișierelor unui program:

`strace -e trace=file {{program}}`
