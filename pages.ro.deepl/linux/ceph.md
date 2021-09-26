# ceph

> Un sistem de stocare unificat.
> Mai multe informații: <https://ceph.io>.

- Verificați starea de sănătate a clusterului:

`ceph status`

- Verificați statisticile de utilizare a clusterului:

`ceph df`

- Obține statisticile pentru grupurile de plasare dintr-un cluster:

`ceph pg dump --format {{plain}}`

- Creați un grup de stocare:

`ceph osd pool create {{pool_name}} {{page_number}}`

- Ștergeți un grup de stocare:

`ceph osd pool delete {{pool_name}}`

- Redenumiți un grup de stocare:

`ceph osd pool rename {{current_name}} {{new_name}}`

- Depozit de auto-reparare a piscinei:

`ceph pg repair {{pool_name}}`
