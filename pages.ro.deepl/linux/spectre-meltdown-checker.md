# spectre-meltdown-checker

> Instrument de detectare a atenuării Spectre și Meltdown.
> Mai multe informații: <https://manned.org/spectre-meltdown-checker.1>.

- Verificați dacă în kernelul care rulează în prezent există Spectre sau Meltdown:

`sudo spectre-meltdown-checker`

- Verificați nucleul care rulează în prezent și prezentați o explicație a acțiunilor care trebuie întreprinse pentru a atenua o vulnerabilitate:

`sudo spectre-meltdown-checker --explain`

- Verifică variantele specifice (valoarea implicită este "toate"):

`sudo spectre-meltdown-checker --variant {{1|2|3|3a|4|l1tf|msbds|mfbds|mlpds|mdsum|taa|mcespc|srbds}}`

- Afișarea ieșirii utilizând un format de ieșire specific:

`sudo spectre-meltdown-checker --batch {{text|json|nrpe|prometheus|short}}`

- Nu folosiți interfața `/sys` chiar dacă este prezentă:

`sudo spectre-meltdown-checker --no-sysfs`

- Verificați un kernel care nu rulează:

`sudo spectre-meltdown-checker --kernel {{path/to/kernel_file}}`
