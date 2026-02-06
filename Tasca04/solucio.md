# T04: Instal·lació Windows Server 2025

## 📝 Introducció al Cas

TransLògic S.A., després del nostre assessorament inicial, ens ha encarregat el **desplegament dels seus servidors Windows Server 2025**. Abans d’implantar-los en el seu entorn productiu, realitzarem una **instal·lació de prova en una màquina virtual** per validar els procediments i establir una guia clara i replicable.

Aquesta instal·lació pilot té dos objectius principals:

1. **Aprendre i validar el procediment tècnic** de configuració de la màquina virtual, instal·lació del sistema operatiu i ajustos inicials.
2. **Crear una guia d’instal·lació en format Markdown**, documentada amb captures i observacions, que servirà com a base per al desplegament definitiu als sistemes del client.

Aquest procés inclourà:
- la configuració de la VM segons els requisits del projecte,  
- la instal·lació de Windows Server 2025 en mode GUI,  
- la configuració inicial del sistema,  
- i una comparació entre els recursos assignats i els **requisits oficials de Microsoft** per assegurar coherència i bones pràctiques.

Aquesta documentació final serà essencial per garantir un desplegament segur, eficient i estandarditzat a TransLògic S.A.

## Guia

Primer de tot crearem la MV amb aquestes prestacions:

![imatge1](/Tasca04/img/captura1.png)

I posarem aquests adaptadors de xarxa:

![imatge2](/Tasca04/img/captura2.png)

![imatge3](/Tasca04/img/captura3.png)

Aquests són els requisits mínims de microsoft per al windows server:

![imatge4](/Tasca04/img/captura4.png)

![imatge5](/Tasca04/img/captura5.png)

![imatge6](/Tasca04/img/captura6.png)

![imatge7](/Tasca04/img/captura7.png)

Com podem veure, la nostra màquina supera els requisits mínims, per el que no cal que ens preocupem.

Un cop iniciada la màquina, seleccionarem aquests idiomes:

![imatge8](/Tasca04/img/captura8.png)

Posem la segona opció:

![imatge9](/Tasca04/img/captura9.png)

Aqui trieu la contrasenya que preferiu.

![imatge10](/Tasca04/img/captura10.png)

Seguidament canviarem el nom del nostre equip:

![imatge11](/Tasca04/img/captura11.png)

Ara Actualitzarem tot l’equip i seguidament pararem les actualitzacions:

![imatge12](/Tasca04/img/captura12.png)

![imatge13](/Tasca04/img/captura13.png)

Un cop acabades les actualitzacions canviarem la configuració de DNS:

![imatge14](/Tasca04/img/captura14.png)

I Finalment comprovem que tenim la hora ben posada:

![imatge15](/Tasca04/img/captura15.png)
