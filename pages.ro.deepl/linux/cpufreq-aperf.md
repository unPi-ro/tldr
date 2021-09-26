# cpufreq-aperf

> Calculați frecvența medie a procesorului pe o perioadă de timp.
> Necesită privilegii de root.
> Mai multe informații: <https://manned.org/cpufreq-aperf>.

- Începeți să calculați, în mod implicit pe toate nucleele CPU și la un interval de reîmprospătare de 1 secundă:

`sudo cpufreq-aperf`

- Începeți să calculați numai pentru CPU 1:

`sudo cpufreq-aperf -c {{1}}`

- Începeți calculul cu un interval de reîmprospătare de 3 secunde pentru toate nucleele CPU:

`sudo cpufreq-aperf -i {{3}}`

- Se calculează o singură dată:

`sudo cpufreq-aperf -o`
