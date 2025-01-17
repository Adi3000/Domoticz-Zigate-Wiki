# Bienvenue sur le wiki du plugin ZiGate pour DomoticZ !

![zigate.fr](../Images/ZiGate.png)

<a href=../en-eng/Home.md><img src="../Images/flag_uk.png" width="15" height="15"></a> [Link to the English Wiki](../en-eng/Home.md) <a href=../nl-dut/Home.md><img src="../Images/flag_netherlands.png" width="15" height="15"></a> [Link naar de Wiki in het Nederlands](../nl-dut/Home.md)

Nous développons ce projet sur notre temps libre. Si vous appréciez ce qui est fait, vous pouvez contribuer par un don PayPal; ce don permettra notamment l'achat d’équipements afin d'augmenter la liste de matériels certifiés compatibles avec le plugin ZiGate. [![PayPal donate](https://camo.githubusercontent.com/d5d24e33e2f4b6fe53987419a21b203c03789a8f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446f6e6174652d50617950616c2d677265656e2e737667)](https://paypal.me/pipiche)


## Introduction

* [Présentation](Info_Accueil.md) à lire pour les nouveaux utilisateurs
* [Lexique](Info_Accueil.md#lexique)


## Installation

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
* La section [Gestion](WebUI_Gestion.md)
* La section [Réseau](WebUI_Reseau.md)
* La section [Admin](WebUI_Admin.md)
* La section [Réglages](WebUI_Reglages.md)
* La section [Outils](WebUI_Outils.md)
* La section [A propos](WebUI_A-propos.md)

## Tutoriels

* [Construire un réseau ZigBee](Tuto_Construire-un-reseau-ZigBee.md)
* [Ajouter un nouvel objet](Tuto_Appairage-objet.md)
* [Supprimer un objet appairé](Tuto_Supprimer-un-objet.md)
* [Paramétrer les objets](Tuto_Parametrer-les-objets.md)
* [Utiliser les outils](Tuto_Utiliser-les-outils.md)
* [Gérer les groupes](Tuto_Gerer-les-groupes.md)
* [Coupler deux objets entre eux](Tuto_Coupler-deux-objets.md)
* [Gérer les erreurs](Tuto_Gerer-erreurs-plugin.md)
* [Changer le canal ZigBee](Tuto_Changer-le-canal-ZigBee.md)
* [Mettre à jour le firmware d'un objet](Tuto_Maj-firmware-objet.md)
* [Mettre à jour le firmware de la ZiGate](Tuto_Maj-firmware-zigate.md)
* [Remplacer ou ré-initialiser la ZiGate](Tuto_Remplacer-zigate.md)
* [Mettre une authentification sur interface d'administration du plugin](Tuto_Mettre-une-authentification-sur-interface-web.md)


## Tutoriels ZiGate

* [Sauvegarder / Restaurer la ZiGate](https://zigate.fr/documentation/sauvegardez-et-restaurez-votre-zigate)
* [Mettre à jour la ZiGate](https://zigate.fr/documentation/mise-a-jour-de-la-zigate)


## Que faire si un objet ne fonctionne pas correctement ?

* [Problèmes d'appairage](Probleme_Appairage.md)
* [Aide au débogage](Probleme_Aide-Debogage.md)


## Particularités de certains objets

* [BlitzWolf](Les-objets_Blitzwolf.md)
* [Eurotronic](Les-objets_Eurotronic.md)
* [Ikea Tradfri](Les-objets_Ikea.md)
* [Legrand Netatmo](Les-objets_Legrand.md)
* [Livolo](Les-objets_Livolo.md)
* [Muller Licht](Les-objets_Muller-Licht.md)
* [Profalux](Les-objets_Profalux.md)
* [Schneider Wiser](Les-objets_Schneider.md)


## En cas de problèmes

1. Vérifiez les logs de DomoticZ, ils contiennent de nombreuses informations utiles à la compréhension du(es) dysfonctionnement(s).
2. Venez en discuter sur les forums :

   * Le forum français : [https://easydomoticz.com/forum](https://easydomoticz.com/forum/viewforum.php?f=28)
   * Le forum anglais : [https://www.domoticz.com/forum](https://www.domoticz.com/forum/viewforum.php?f=68)

## Scripts

* [Vérifier le niveau des batteries](../Contrib/CheckBatteryLevel.dzVents) en DzVents
* [Vérifier la perte d'objets (version 1)](../Contrib/CheckLastSeen.dzVents) en DzVents
* [Vérifier la perte d'objets (version 2)](../Contrib/CheckDeadDevices.lua) en DzVents

[D'autres exemples](../Contrib/)

## Informations

* [Les objets compatibles](Info_Accueil.md#presentation)
* [Les caractéristiques des ZiGates](Info_Caracteristiques-des-ZiGates.md)
* [Interférences entre Wifi et ZigBee](Info_ZigBee-et-Wifi.md)
* [Topologie du réseau](Info_Topologie-reseau.md)
* [Configurer la ZiGate en sniffer ZigBee](../en-eng/Zigate-Sniffer.md)  en anglais
* [Installer DomoticZ sur un NAS Synology avec Docker](Info_Installer-Domoticz-NAS-Synology-Docker.md)

## Liens utiles

* [Le wiki ZiGate.fr](https://zigate.fr/documentation)
* [A Guide to Wireless range and Repeater](https://support.smartthings.com/hc/en-us/articles/209963206-A-guide-to-wireless-range-and-repeaters)
* [Pairing devices Aqara/Xiaomi](https://community.hubitat.com/t/xiaomi-aqara-devices-pairing-keeping-them-connected/623)
* [Cohexistence Xiaomi with other brands](https://community.hubitat.com/t/xiaomi-aqara-devices-pairing-keeping-them-connected/623)
