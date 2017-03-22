# Partie 2 : Introduction à GitHub
Bienvenue dans la deuxième partie de ce tutoriel sur Git. Dans cette
partie, nous allons voir comment fonctionne GitHub et comment le prendre en main
de façon intuitive.
Prérequis : parties précédentes.

### Création d'un compte GitHub
Pour commencer à utiliser l'outil GitHub, il va falloir créer un compte. Rendez-vous
sur le site de GitHub et inscrivez-vous : il faudra renseigner les champs nécessaires.

### Un premier dépôt GitHub
Vous voilà en possession d'un compte GitHub ! ... Mais qu'est-ce qu'on en fait ?
L'interface peut sembler un peu surchargée au début, mais la plupart des outils
ne nous serviront que plus tard. Pour l'instant, nous allons créer notre premier
**dépôt**.

>Un dépôt ? Qu'est-ce que c'est ?

Un dépôt est l'équivalent du dossier de projet (souvenez-vous de la partie 0 !) : 
c'est ce qui contiendra vos fichiers source ! Nous verrons comment le maintenir
et l'administrer par la suite.

Pour créer un nouveau dépôt GitHub, il faut cliquer sur le "+" sur la barre de
navigation en haut : "new repository". Pour commencer, nous allons faire un programme
"Hello World" basique ; il est courant de nommer son dépôt selon le programme
ou le projet effectué. Nommons alors ce dépôt "Hello World".

Ajouter une description à son dépôt permet un meilleur référencement. A vous de
trouver une bonne description pour ce programme !

Sans payer l'abonnement mensuel, on ne peut pas faire de dépôt privé. Ce n'est
pas grave, car ce projet est sans importance ; mais en entreprise, cette
solution, ou alors d'autres plateforme de développement en entreprise sont
envisagées.

N'oubliez pas de cocher "Initialize this repository with a README" : votre
dépôt aura alors un fichier "Lisez-moi" qui sera visible sur la page
principale de votre dépôt.

N'ajoutez pas de .gitignore ni de license, nous verrons ça plus tard. Cliquez
sur "Create repository : voilà votre nouveau dépôt créé !"

### L'anatomie d'un dépôt
Vous voici sur votre page de dépôt. Il y a plusieurs menus, et nous allons
les explorer.

##### La barre des menus
En haut de la page, juste en dessous de la barre sombre de navigation sur le site,
il y a plusieurs onglets de disponible : "Code", "Issues"...

- Code : C'est l'endroit où sont stockés les fichiers et l'arborescence du
      projet.
    
- Issues : Les bugs, fonctionnalités manquantes ou tout autre problème
      signalé par des utilisateurs du dépôt sont listées ici. Dans cet onglet, on peut créer,
      supprimer, confirmer des problèmes.
    
- Pull requests : C'est la liste des requêtes de pull (nous verrons ce que c'est plus
      tard).

- Projects : Une fonctionnalité pratique qui permet de créer des colonnes à idées,
      pour organiser un planning, ce qu'il reste à faire...

- Wiki : Une page vide au début, elle sert par la suite à documenter le dépôt et donc
      de permettre à l'utilisateur de le consulter en cas de doute.

- Pulse : Donne la "santé" du dépôt : la fréquence de modifications, les statistiques
      sur les principaux contributeurs...

- Graphs : Une série de statistiques et de graphiques qui permettent de voir l'évolution
      du dépôt au cours du temps

- Settings : Comme son nom l'indique, ce sont les réglages du dépôt.

##### Le menu Code
Nous allons nous intéresser au menu Code, et observer les sous-menus de cette page :

- X commits : Le nombre de commits (nous y reviendrons dans la prochaine partie)
      effectués sur la branche de développement sélectionnée.
    
- X branches : Le nombre de branches de développement actives sur le dépôt.

- X releases : Le nombre de versions finales du projet

- X contributors : La liste des contributeurs au projet

Voilà, on s'y retrouve déjà un peu mieux dans ce menu ! Pensez à revenir dans cette partie
si un menu ou un sous-menu vous échappe. Dans la prochaine partie, nous allons voir comment
travailler sur le dépôt !