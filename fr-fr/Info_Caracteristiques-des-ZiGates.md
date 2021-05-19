# Info - Les caractéristiques des ZiGates

Les ZiGates peuvent avoir des différences. Plutôt que d'éditer toutes les pages du wiki pour rajouter les infos pour les nouveaux modèles, toutes les informations de ce type sont regroupées dans cette page.

## Nombre d'objet limité

Le nombre d'objets géré par une ZiGate est limité :

Modèle **V1** avec **firmware standard** : 40 objets maximum en tout.
Modèle **V1** avec **firmware OptiPDM** : 20 objets maximum en direct sur la ZiGate et jusqu'à 70 en tout (en passant par des routeurs).

Modèle **V2** : 200 objets avec 20 maximum en direct sur la ZiGate et le reste en passant par des routeurs.


Dans tous les cas, **DomoticZ limite le nombre de dispositifs par plugin à 255**.

Pour info, un objet capteur de température Xiaomi / Aqara occupe 5 dispositifs : Température, Hygrométrie, Pression, Température + Hygrométrie et Température + Hygrométrie + Pression.


## Nombre de groupe limité

Le nombre de groupes auxquels une ZiGate peut appartenir est limité :

Modèle V1 : 5 Groupes
Modèle V2 : 15 Groupes


Le nombre de groupes auxquels un objet peut appartenir est limité :

Généralement, un objet peut appartenir à 5 groupes différents. Pour rappel, c'est l'objet qui sait dans quel groupe il appartient. Le nombre exact va dépendre de chaque objet.
