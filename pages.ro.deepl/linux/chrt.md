# chrt

> Manipulați atributele în timp real ale unui proces.
> Mai multe informații: <https://man7.org/linux/man-pages/man1/chrt.1.html>.

- Afișează atributele unui proces:

`chrt --pid {{PID}}`

- Afișează atributele tuturor firelor de execuție ale unui proces:

`chrt --all-tasks --pid {{PID}}`

- Afișează valorile de prioritate min/max care pot fi utilizate cu `chrt`:

`chrt --max`

- Setați politica de planificare pentru un proces:

`chrt --pid {{PID}} --{{deadline|idle|batch|rr|fifo|other}}`
