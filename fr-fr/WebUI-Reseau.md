# L'interface Web - La section Réseau

Pour accéder à l'interface d'administration du plugin, voir l'étape 3 [Configuration du plugin](Configuration.md).

La section __Réseau__ comporte les pages :

* [Topologie](#topologie)
* [Niveau d'interférences](#niveau-dinterf%C3%A9rences)

## Topologie

Voici la page __Topologie__ de l'interface Web du plugin : 

![Network_Topology](https://github.com/pipiche38/Domoticz-Zigate-Wiki/blob/master/Images/Network_Topology.png)
*Cette page est suceptible d'avoir évoluer depuis l'écriture de cette documentation.*

### Utilisation

Cette page permet de visualiser le réseau ZigBee. 

Elle permet :

* De visualiser et gérer les différents rapports d'analyse du réseau
* De lancer une analyse du réseau

### Description d'un rapport de topologie réseau

Le rapport de topologie réseau est constitué de deux graphiques présentant le maillage et le réseau.

#### Le graphique du maillage

L'illustration de votre maillage montre tout les liens entre 2 dispositifs. 
Si vous déplacez le curseur sur un lien vous verrez la liaison ainsi que la qualité de la liaison : échelle de 0 (très mauvaise) à 255 (la meilleure).

Un bouton en haut à droite du graphique permet de l'afficher en plein écran, de l'imprimer ou de l'exporter sous différent formats.

#### Le graphique du réseau

L'illustration de votre maillage montre l'architecture du réseau ZigBee (les connexions entre les différents dispositifs). 
Vous pouvez visualiser sur quel router est accroché votre dispositif terminal.

Un bouton en haut à droite du graphique permet de l'afficher en plein écran, de l'imprimer ou de l'exporter sous différent formats.


## Niveau d'interférences

Voici la page __Niveau d'interférences__ de l'interface Web du plugin : 

![InterferenceLevels](https://raw.githubusercontent.com/pipiche38/Domoticz-Zigate-Wiki/master/Images/InterferenceLevels.png)
*Cette page est suceptible d'avoir évoluer depuis l'écriture de cette documentation.*

### Utilisation

Cette page permet de visualiser les niveaux d'interférences par canal du réseau ZigBee.

Elle permet :

* De visualiser et gérer les différents rapports d'interférence du réseau.
* De lancer une analyse des interférences par canal
* De lancer une analyse complète des niveaux d'interférence par canal

### Description d'un rapport de niveau d'interférence

Voir les [explications](ZigBee-et-Wifi.md) sur les interférences entre le Wifi et le ZigBee

Le niveaux d'interférence est calculé avec la communication entre la Zigate et un router. C'est un petit peu le même principe que lors d'un ping sur le réseau ethernet où vous avez le nombre de paquets perdus.  
Si vous ne disposez pas de router, vous ne pouvez pas faire d'analyse du niveau d'interférence.

Le graphique montre pour chaque canal ZigBee (de 11 à 26) et pour chaque router, le niveau d'interférence lors de la communication avec la Zigate: échelle de 0 (aucune interférence) à 255 (beaucoupo d'interférence). 


Voir les autres pages de l'[interface Web du plugin](Home.md#linterface-web-du-plugin)
