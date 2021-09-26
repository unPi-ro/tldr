# datamash

> Instrument pentru efectuarea de operații numerice, textuale și statistice de bază pe fișiere de date textuale de intrare.
> Mai multe informații: <http://www.gnu.org/software/datamash/>.

- Obțineți maximul, minimul, media și mediana unei singure coloane de numere:

`seq 3 | datamash max 1 min 1 mean 1 median 1`

- Obține media unei singure coloane de numere flotante (numerele flotante trebuie să folosească "," și nu "."):

`echo -e '1.0\n2.5\n3.1\n4.3\n5.6\n5.7' | tr '.' ',' | datamash mean 1`

- Obține media unei singure coloane de numere cu o precizie zecimală dată:

`echo -e '1\n2\n3\n4\n5\n5' | datamash -R {{number_of_decimals_wanted}} mean 1`

- Obține media unei singure coloane de numere, ignorând șirurile "Na" și "NaN" (literal):

`echo -e '1\n2\nNa\n3\nNaN' | datamash --narm mean 1`
