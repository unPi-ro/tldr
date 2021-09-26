# cpufreq-info

> Un instrument pentru a afișa informații despre frecvența CPU.
> Mai multe informații: <https://manned.org/cpufreq-info>.

- Afișează informații despre frecvența procesorului pentru toate procesoarele:

`cpufreq-info`

- Afișează informații despre frecvența CPU pentru CPU-ul specificat:

`cpufreq-info -c {{cpu_number}}`

- Afișează frecvența minimă și maximă permisă pentru CPU:

`cpufreq-info -l`

- Afișează în format tabelar frecvența și politica curentă minimă și maximă a procesorului:

`cpufreq-info -o`

- Afișează politicile de frecvență CPU disponibile:

`cpufreq-info -g`

- Afișează frecvența curentă de lucru a procesorului într-un format lizibil pentru oameni, în conformitate cu modulul de kernel cpufreq:

`cpufreq-info -f -m`

- Afișează frecvența curentă de lucru a procesorului într-un format lizibil pentru oameni, citind-o de la hardware (disponibil numai pentru root):

`sudo cpufreq-info -w -m`
