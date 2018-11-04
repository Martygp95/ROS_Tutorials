# ROS_Tutorials
Tutorials de ROS


## 2: Sistema de fitxers de ROS

En aquest tutorial se'ns presenten algunes funcions útils per tal d'accedir a paquets de ROS de manera senzilla; aquestes funcions es troben dins del paquet de **rosbash** , on trobem multitud de funcions per facilitar l'ús de ROS.

Per tal de navegar en el sistema de fitxers de ROS, hi ha una funció que retorna el path del paquet demanat; la funció és *rospack*

![alt_text](imatges/i1.png)

Si es vol accedir directament al directori, es pot fer servir la comanda *roscd* amb la qual ens portarà diectament al paquet que indiquem. Amb la comanda de linux *pwd* podem veure en quin directori estem.

Per tal d'accedir a informació sobre el paquet, es pot executar directament la comanda de *rosls* seguit del paquet del qual volem obtenir informació.

![alt_text](imatges/i2.png)

Una altra utilitat que ens ensenya és que amb el tabulador es pot escriure d'una manera més eficient per tal de no haver d'escriure noms llargs. En cas d'haver diverses opcions que comencin amb el mateix nom, es mostren en el terminal.


### RESUM

Per tant, les funcions a tenir en compte per a un millor ús de ROS són les següents:

- *rospack*, per tal de demanar el directori a on es troba un paquet en concret
- *roscd*, per accedir directament al directori a on es troba el paquet
- *rosls*, per tal d'obtenir directament la informació d'un paquet

Altres utiltats d'aquest tutorial són:

- La comanda *pwd*, per tal de mostrar el directori actual
- El tabulador, per tal d'escriure més ràpid


