# runcon

> Rulați un program într-un context de securitate SELinux diferit.
> Fără context și fără comandă, tipărește contextul de securitate curent.
> Mai multe informații: <https://www.gnu.org/software/coreutils/runcon>.

- Determinați domeniul curent:

`runcon`

- Specificați domeniul în care se execută o comandă:

`runcon -t {{domain}}_t {{command}}`

- Specificați rolul de context cu care se execută o comandă:

`runcon -r {{role}}_r {{command}}`

- Specificați contextul complet în care se execută o comandă:

`runcon {{user}}_u:{{role}}_r:{{domain}}_t {{command}}`
