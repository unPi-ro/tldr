# yum

> Utilitar de gestionare a pachetelor pentru RHEL, Fedora și CentOS (pentru versiunile mai vechi).
> Mai multe informații: <https://man7.org/linux/man-pages/man8/yum.8.html>.

- Instalați un nou pachet:

`yum install {{package}}`

- Instalați un nou pachet și presupuneți că ați răspuns afirmativ la toate întrebările (funcționează, de asemenea, cu update, excelent pentru actualizările automate):

`yum -y install {{package}}`

- Găsiți pachetul care oferă o anumită comandă:

`yum provides {{command}}`

- Îndepărtați un pachet:

`yum remove {{package}}`

- Afișează actualizările disponibile pentru pachetele instalate:

`yum check-update`

- Actualizați pachetele instalate la cele mai noi versiuni disponibile:

`yum upgrade`
