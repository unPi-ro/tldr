# ldconfig

> Configurați legăturile simbolice și memoria cache pentru dependențele bibliotecilor partajate.
> Mai multe informații: <https://manned.org/ldconfig>.

- Actualizarea legăturilor simbolice și reconstruirea memoriei cache (de obicei, se execută atunci când este instalată o nouă bibliotecă):

`sudo ldconfig`

- Actualizează legăturile simbolice pentru un anumit director:

`sudo ldconfig -n {{path/to/directory}}`

- Tipărește bibliotecile din memoria cache și verifică dacă o anumită bibliotecă este prezentă:

`ldconfig -p | grep {{library_name}}`
