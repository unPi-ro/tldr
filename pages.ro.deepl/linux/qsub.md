# qsub

> Trimite un script către sistemul de gestionare a cozilor de așteptare TORQUE.

- Trimiteți un script cu setări implicite (depinde de setările TORQUE):

`qsub {{script.sh}}`

- Trimiteți un script cu o limită de timp de execuție specificată de 1 oră, 2 minute și 3 secunde:

`qsub -l walltime={{1}}:{{2}}:{{3}} {{script.sh}}`

- Trimiteți un script care este executat pe 2 noduri utilizând 4 nuclee pe nod:

`qsub -l nodes={{2}}:ppn={{4}} {{script.sh}}`

- Trimiteți un script la o anumită coadă de așteptare. Rețineți că diferitele cozi pot avea limite de timp de execuție maxime și minime diferite:

`qsub -q {{queue_name}} {{script.sh}}`
