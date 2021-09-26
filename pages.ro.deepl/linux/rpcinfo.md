# rpcinfo

> Efectuează un apel RPC către un server RPC și raportează ceea ce găsește.

- Afișează tabelul complet al tuturor serviciilor RPC înregistrate pe localhost:

`rpcinfo`

- Afișează un tabel concis cu toate serviciile RPC înregistrate pe localhost:

`rpcinfo -s {{localhost}}`

- Afișează tabelul cu statisticile operațiunilor rpcbind pe localhost:

`rpcinfo -m`

- Afișează lista de intrări cu numele serviciului dat (mountd) și numărul versiunii (2) pe o partajare nfs la distanță:

`rpcinfo -l {{remote_nfs_server_ip}} {{mountd}} {{2}}`

- Ștergeți înregistrarea pentru versiunea 1 a serviciului mountd pentru toate mijloacele de transport:

`rpcinfo -d {{mountd}} {{1}}`
