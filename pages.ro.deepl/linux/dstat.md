# dstat

> Instrument versatil pentru generarea de statistici privind resursele sistemului.
> Mai multe informații: <http://dag.wieers.com/home-made/dstat>.

- Afișează statisticile de CPU, de disc, de rețea, de paginare și de sistem:

`dstat`

- Afișarea statisticilor la fiecare 5 secunde și numai la 4 actualizări:

`dstat {{5}} {{4}}`

- Afișează doar statisticile privind CPU și memoria:

`dstat --cpu --mem`

- Listează toate plugin-urile dstat disponibile:

`dstat --list`

- Afișează procesul care utilizează cea mai mare parte a memoriei și a procesorului:

`dstat --top-mem --top-cpu`

- Afișează procentul de baterie și timpul rămas al bateriei:

`dstat --battery --battery-remain`
