# virt-manager

> Lansator CLI pentru virt-manager, o interfață de utilizator desktop pentru gestionarea mașinilor virtuale KVM și Xen și a containerelor LXC.
> Mai multe informații: <https://manpages.ubuntu.com/manpages/man1/virt-manager.1.html>.

- Lansați virt-manager:

`virt-manager`

- Conectați-vă la un hipervizor:

`virt-manager --connect {{hypervisor_uri}}`

- Nu puneți procesul virt-manager în fundal la pornire:

`virt-manager --no-fork`

- Imprimă ieșirea de depanare:

`virt-manager --debug`

- Deschideți expertul "New VM":

`virt-manager --show-domain-creator`

- Afișează fereastra cu detalii despre domeniu:

`virt-manager --show-domain-editor {{name|id|uuid}}`

- Afișează fereastra de performanță a domeniului:

`virt-manager --show-domain-performance {{name|id|uuid}}`

- Afișează fereastra cu detalii despre conexiune:

`virt-manager --show-host-summary`
