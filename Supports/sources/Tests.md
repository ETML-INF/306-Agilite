# Les tests

## Problématique

Pendant la réalisation de notre mandat, nous travaillons dans notre environnement de travail que nous connaissons bien. Plus ou moins consciemment, nous adaptons nos choix à cet environnement. Pire encore (nous sommes humains): nous avons tendance à favoriser les tests que l’on sait qu’ils vont passer.

Le moment venu de mettre en service ou de publier notre système, l’environnement change, l’utilisateur change, et soudain les problèmes surgissent.

Comment faire pour minimiser, voire éliminer ces problèmes ?

## Niveau de test

Dans la mesure du temps et des moyens à disposition, nous essayons de faire des tests de chacun des trois niveaux de test suivants :

- Le Test unitaire : Il vérifie le bon fonctionnement d’un composant réalisé par une personne. Exemple : on vérifie qu’une pièce de Mécano respecte les dimensions voulues
- Le Test d’intégration : Il vérifie que deux ou plusieurs composants testés unitairement fonctionnent correctement ensemble. Exemple : on vérifie que diverses pièces de Mécano peuvent bien être assemblées au moyen des vis et écrous.
- Le Test Système : Il vérifie le bon fonctionnement du système complet dans l’environnement où
il va être vraiment utilisé.
- Page 37 -
Exemple : on vérifie le bon fonctionnement de notre construction complète.
Type de test
Dans la mesure du temps et des moyens à disposition, nous essayons de faire des tests de chacun des
quatre types de tests suivants :
 Le Test fonctionnel, qui vérifie que l’élément testé fait ce qu’on attend de lui ;
 Le Test de performance, qui vérifie que l’élément testé peut traiter la quantité d’information
voulue dans le temps voulu ;
 Le Test de robustesse, qui vérifie que l’élément testé peut reprendre un fonctionnement
normal après avoir passé par une situation anormale.
 Le Test de non-régression, qui vérifie qu’un changement effectué à un endroit du système n’a
pas affecté le bon fonctionnement du système dans son ensemble.
Exemple : considérons la machine ci-dessus.
- Page 38 -
Elle sert à imprimer des flyers, les plier, les insérer dans une enveloppe, fermer l’enveloppe et faire des
paquets de 100 enveloppes fermées.
Un test fonctionnel vérifiera que les flyers sont bien pliés en trois volets égaux et qu’il y a bien 100
enveloppes par paquet au final
Un test de performance vérifiera que la machine est capable de produire 250 paquets de 100
enveloppes en une heure
Un test de robustesse vérifiera que si on fournit des enveloppes qui sont déjà remplies, le système les
écarte et reprend son fonctionnement dès que les enveloppes fournies sont vides