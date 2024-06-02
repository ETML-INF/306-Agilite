Expérience avec les CIN1B = compliqué.

La durée de concentration dont ce groupe est capable est faible. Cela varie naturellement d'une personne à l'autre, mais globalement il est pratiquement impossible de parler pendant plus de cinq minutes sans qu'une partie significative des élèves ne décroche.

Chez un bon quart du groupe, je constate le syndrome du "coup d'œil inquiet par-dessus l'épaule" en permanence.

Dans le feed-back qu'ils m'ont donné, ils ont relevé le stress lié aux livraisons de chaque semaine. Sur le moment je me suis contenté de noter, mais je pense que ce serait une bonne chose de conserver cela et de leur faire comprendre qu'il s'agit là d'un bon exercice pour qu'il puisse être un peu plus serein par la suite lors de releases véritablement significatives.

Dans le deuxième test, la qualité des burn up charts rendus était vraiment mauvaise. J'ai beau me remettre en question, je ne vois pas comment j'aurais pu faire autrement sans procéder de manière ultra classique théorie exercice corrigé. Je leur ai  demandé de faire le graphique à partir des données de leur projet, ils sont restés bloqués. Je leur ai généré un tableau des données absolument similaire à celui du test en guise d'exercice, il ne s'y sont pas intéressés. Il n'y avait que deux ou trois élèves attentifs au moment où j'ai fait la correction au tableau. Les autres ont choisi de ne pas écouter.

Je pense être arrivé au bout de l'idée sweet Home 3D. Cela a mieux fonctionné que les fois précédentes avec un seul immeuble, mais il reste malgré tout des problèmes importants :
  1. Les élèves jouent à construire plutôt qu'à gérer leurs projets. J'ai dû constamment surveiller et rappeler à l'ordre des élèves qui passaient leur temps à construire un truc fun durant des moments où ils auraient dû travailler. Exemple : la réalisation du burnup chart
  2. La stabilité de l'application. Suivre les modèles choisi par les élèves, leur fichier devenait tellement lourd que l'application n'arrivait plus à gérer l'intégration de plusieurs pièces dans un seul fichier.
  3. Les diverses versions de l'application. Nous avons utilisé la version portable pour simplifier le processus d'installation. Fausse bonne idée. Cette version pose plus de problèmes que la version officielle.
  4. La taille des fichiers générés devient trop grosse pour Git
  5. L'abstraction que représente le modèle visuel par rapport au bâtiment réel continue de poser problème aux élèves

 l'enchaînement des concepts étaient plutôt réussi. En tout cas meilleur que les fois précédentes.

Idées pour la suite :
  - Faire faire la planification au moyen de legos: Une plaque représente un sprint, une partie de cette plaque déjà entamée par le travail de fond (administratif, théorie,...). On donne aux élèves un tas de pièces qui représente le backlog produit. Chaque pièce représente une user story dont l'estimation est le nombre de picots. Dans un premier temps, ils remplissent au mieux trois plaques avec l'ensemble des pièces. Ensuite, ils refont l'exercice mais avec un nombre de pièces trop élevé pour tenir sur les plaques. La couleur des pièces indique si la Story est obligatoire ou pas. On refait une troisième fois l'exercice, mais en introduisant cette fois une dépendance d'ordre basé sur la couleur (les pièces verte doivent être placées avant que celle d'une autre couleur puisse être placées par exemple)
  - Faire un parallèle explicite entre la manière de travailler avec un serveur de fichiers ou avec Git. Dans les deux cas, ce qui nous intéresse c'est la progression au fil du temps. Lorsqu'on travaille avec des fichiers uniquement, on s'appuie sur des conventions de nommage (de fichiers ou de répertoire). Avec Git, on garde toujours le même nom pour un fichier et c'est l'historique Git qui nous permet d'obtenir l'information de progression dans le temps
  - Utiliser [Roadmaps](https://roadmap.sh/).
