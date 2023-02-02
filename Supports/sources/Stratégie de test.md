# Stratégie de test

Il est fréquent que le code qui fonctionne bien sur le poste du développeur se mette à bugger une fois déplacé dans son contexte d'exploitation.

D'autre part, il n'y a généralement pas pire testeur que le développeur lui-même. Parce que celui qui écrit du code aura tendance à tester le même scénario et avec les mêmes données qu'il avait en tête au moment de l'écriture du code.

Il est donc capital de faire des tests en dehors du contexte de développement et de celui de la production.

Établir une stratégie de test consiste donc à décrire les moyens et les procédures qui vont permettre de passer de l'environnement de développement à celui de production de la manière la plus sûre possible.

Pour tout mandat/projet, nous définissons une stratégie de test en décrivant :
1.	Le matériel et logiciel tiers.
2.	Les données de test.
3.	Les personnes qui vont participer aux tests : camarades de classe, amis, famille, profs, …
4.	Le timing des activités de test
5.	Les types et niveaux de tests effectués

Exemple de stratégie de test pour un site web qui est le yearbook d'une école:

> Pour le développement du site web, le serveur sera un wamp installé sur le même PC que celui sur lequel j’écrirai le code. Sur ce poste, je ne ferai que des tests fonctionnels.
> 
> Je préparerai  
> •	Un script SQL qui créera 60 élèves répartis dans 4 classes.  
> •	Un ZIP contenant des photos fictives pour les 60 élèves
> 
> J’utiliserai ensuite une machine virtuelle VMWare avec Debian 9 installé dessus et un serveur LAMP. Cette machine virtuelle sera également sur mon PC de développement. Elle ne servira qu’à faire des tests fonctionnels. Elle sera visible sur le réseau de l’école. Mon chef de projet ainsi que deux de mes camarades de classe l’utiliseront pour faire quelques tests.
> 
> Je déploierai mon site du l’hébergeur ‘Swisscenter’ pour faire les tests fonctionnels finaux. Avec l’aide d’autres camarades, nous effectuerons également des tests de robustesse et de performance en se connectant à plusieurs simultanément.
> 
> Les tests fonctionnels seront faits avec les navigateurs Google Chrome et Firefox sur Windows, Google Chrome, Firefox et Safari sur Mac. Aucun test n’est prévu sur Edge.
