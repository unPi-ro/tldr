# ctrlaltdel

> Utilitar pentru a controla ce se întâmplă atunci când este apăsat CTRL ALT DEL.

- Obține setarea curentă:

`ctrlaltdel`

- Setați CTRL ALT DEL pentru a reporni imediat, fără nicio pregătire:

`sudo ctrlaltdel hard`

- Setați CTRL ALT DEL pentru a reporni "în mod normal", oferind proceselor o șansă de a ieși mai întâi (trimiteți SIGINT la PID1):

`sudo ctrlaltdel soft`
