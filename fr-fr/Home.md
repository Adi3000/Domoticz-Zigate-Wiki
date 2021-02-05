![zigate.fr](../Images/ZiGate.png)

Bienvenue sur le wiki du plugin ZiGate pour DomoticZ !

Le but de ce wiki est de fournir les plus d'informations possible sur l'utilisation du plugin.

Nous développons ce projet sur notre temps libre. Si vous appréciez ce qui est fait, vous pouvez contribuer par un don PayPal; ce don permettra notamment l'achat d’équipements afin d'augmenter la liste de matériels certifiés compatibles avec le plugin ZiGate. [![PayPal donate](https://camo.githubusercontent.com/d5d24e33e2f4b6fe53987419a21b203c03789a8f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446f6e6174652d50617950616c2d677265656e2e737667)](https://paypal.me/pipiche)

**Ce wiki en français a été traduit à partir du [wiki anglais](../en-eng/home.md) :** si des choses ne sont pas claires ou approximées, ne pas hésiter à nous faire un retour.


## Introduction

L'objectif de ce plugin est de réaliser une passerelle entre une [ZiGate](https://zigate.fr), un récepteur ZigBee et le logiciel de domotique [DomoticZ](https://www.domoticz.com). Ce plugin permettra de gérer les dispositifs ZigBee utilisés par DomoticZ.

Le plugin dispose d'une interface utilisateur dédiée accessible depuis votre navigateur web. Cette interface permettra de configurer le plugin et régler le fonctionnement de la ZiGate.

Voici une liste non exhaustive des dispositifs compatibles : [https://zigbee.blakadder.com](https://zigbee.blakadder.com). Ceux présents dans la liste ont été "certifiés" : nous savons qu'ils fonctionnent avec le plugin.
Il est possible qu'il y ait d'autres dispositifs ZigBee qui fonctionnent (merci de remonter l'info afin que la liste soit mise à jour).


## Lexique

Explication des termes utilisés sur ce Wiki :

| Terme | Signification |
| ----- | ------------- |
| Objet | L'objet physique : sonde, bouton, ampoule, prise, volet, sirène, etc... |
| Routeur | Un objet branché généralement sur le secteur qui peut recevoir des commandes : une ampoule, une prise, un volet, etc... Il joue un rôle dans le maillage du réseau ZigBee |
| Objet terminal | Un objet généralement sur batterie qui envoi des informations : une sonde, un bouton |
| Dispositif | Fonction d'un objet qui se trouve dans Menu Configuration / Dispositifs de DomoticZ |
| Widget | Tuile dans le tableau de bord de DomoticZ correspondante à un dispositif |




## Installation

Il existe plusieurs façons d'installer le plugin ZiGate pour DomoticZ qui sont différentes en fonction du système d'exploitation.

Dans tous les cas, le plugin nécessite DomoticZ version 3.87 ou supérieure et Python version 3.5 ou supérieur. Assurez-vous que le paquet __python3-dev__ est installé. Plus d'informations sur la page [DomoticZ Python plugin](https://www.domoticz.com/wiki/Using_Python_plugins).


* Étape 1 [Installation du plugin](Plugin_Installation.md)
* Étape 2 [Paramétrage du plugin](Plugin_Parametrage.md)
* Étape 3 [Configuration du plugin](Plugin_Configuration.md)


## Mises à jour du plugin

* [Mettre à jour le plugin](Plugin_Mise-a-jour.md#mettre-à-jour-le-plugin)
* [Les branches de mises à jour](Plugin_Mise-a-jour.md#les-branches-de-mise-à-jour)


## Sauvegardes

* [Sauvegardes à faire pour pouvoir réinstaller le plugin sans perdre de données](Plugin_Sauvegardes.md)


## L'interface Web du plugin

* [Présentation générale](WebUI_Presentation-generale.md)
* La section [Tableau de bord](WebUI_Tableau-de-bord.md)
* La section [Management](WebUI_Management.md)
* La section [Réseau](WebUI_Reseau.md)
* La section [Admin](WebUI_Admin.md)
* La section [Réglages](WebUI_Reglages.md)
* La section [Outils](WebUI_Outils.md)
* La section [A propos](WebUI_A-propos.md)


## Tutoriels

* [Ajouter un nouveau dispositif](Tuto_Appairage-dispositif.md)
* [Supprimer un dispositif appairé](Tuto_Supprimer-un-dispositif.md)
* [Changer le canal ZigBee](Tuto_Changer-le-canal-ZigBee.md)
* [Gérer les groupes](Tuto_Gerer-les-groupes.md)
* [Mettre à jour le firmware d'un dispositif](Tuto_Maj-firmware-dispositif.md)
* [Mettre à jour le firmware de la ZiGate](Tuto_Maj-firmware-zigate.md)
* [Coupler deux dispositifs entre eux](Tuto_Coupler-deux-dispositifs.md)
* [Mettre une authentification sur interface d'administration du plugin](Tuto_Mettre-une-authentification-sur-interface-web.md)


## Que faire si un dispositif ne fonctionne pas correctement ?

* [Problèmes d'appairage](Probleme_Appairage.md)
* [Aide au débogage](Probleme_Aide-Debogage.md)


## Particularités de certains dispositifs

* [BlitzWolf](Les-objets_Blitzwolf.md)
* [Ikea Tradfri](Les-objets_Ikea.md)
* [Eurotronic](Les-objets_Eurotronic.md)
* [Profalux](Les-objets_Profalux.md)
* [Legrand Netatmo](Les-objets_Legrand.md)
* [Schneider Wiser](Les-objets_Schneider.md)
* [Livolo](Les-objets_Livolo.md)


## En cas de problèmes

1. Vérifiez les logs de DomoticZ, il devrait y avoir des informations si quelque chose ne fonctionne pas correctement.
2. Venez en discuter sur les forums :

   * [Le forum français](https://easydomoticz.com/forum/viewforum.php?f=28)
   * [Le forum anglais](https://www.domoticz.com/forum/viewforum.php?f=68)


## Scripts

* [Vérifier le niveau des batteries](../Contrib/CheckBatteryLevel.dzVents) en DzVents
* [Vérifier la perte de dispositifs](../Contrib/CheckDeadDevices.lua) en Lua
* [Vérifier la perte de dispositifs](../Contrib/CheckLastSeen.dzVents) en DzVents

[D'autres exemples](../Contrib/)


## Informations

* [Les caractéristiques des ZiGates](Info_Caracteristiques-des-ZiGates.md)
* [Interférences entre Wifi et ZigBee](Info_ZigBee-et-Wifi.md)
* [Topologie du réseau](Info_Topologie-reseau.md)
* [Configurer la ZiGate en sniffer ZigBee](../en-eng/Zigate-Sniffer.md)  en anglais


## Liens utiles

* [A Guide to Wireless range and Repeater](https://support.smartthings.com/hc/en-us/articles/209963206-A-guide-to-wireless-range-and-repeaters)
* [Pairing devices Aqara/Xiaomi](https://community.hubitat.com/t/xiaomi-aqara-devices-pairing-keeping-them-connected/623)
* [Cohexistence Xiaomi with other brands](https://community.hubitat.com/t/xiaomi-aqara-devices-pairing-keeping-them-connected/623)
