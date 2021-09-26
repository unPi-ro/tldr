# nixos-rebuild

> Reconfigurați o mașină NixOS.
> Mai multe informații: <https://nixos.org/nixos/manual/#sec-changing-config>.

- Construiți și comutați la noua configurație, făcând-o implicită pentru pornire:

`sudo nixos-rebuild switch`

- Construiți și comutați la noua configurație, făcând-o implicită la pornire și numind intrarea de pornire:

`sudo nixos-rebuild switch -p {{name}}`

- Construiți și treceți la noua configurație, transformând-o în configurația implicită de pornire și instalând actualizările:

`sudo nixos-rebuild switch --upgrade`

- Retragerea modificărilor aduse configurației, revenind la generația anterioară:

`sudo nixos-rebuild switch --rollback`

- Construiți noua configurație și faceți-o să fie cea implicită la pornire fără a trece la ea:

`sudo nixos-rebuild boot`

- Construiți și activați noua configurație, dar nu faceți o intrare de pornire (în scopuri de testare):

`sudo nixos-rebuild test`

- Creați configurația și deschideți-o într-o mașină virtuală:

`sudo nixos-rebuild build-vm`
