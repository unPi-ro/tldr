# rpmbuild

> Instrumentul de construire a pachetelor RPM.
> Mai multe informații: <https://docs.fedoraproject.org/en-US/quick-docs/creating-rpm-packages/>.

- Construiți pachete binare și sursă:

`rpmbuild -ba {{path/to/spec_file}}`

- Construiește un pachet binar fără pachetul sursă:

`rpmbuild -bb {{path/to/spec_file}}`

- Specificați variabile suplimentare atunci când construiți un pachet:

`rpmbuild -bb {{path/to/spec_file}} --define "{{variable1}} {{value1}}" --define "{{variable2}} {{value2}}"`
