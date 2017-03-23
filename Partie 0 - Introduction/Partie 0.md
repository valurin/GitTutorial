# Partie 0 : Introduction aux logiciels de version
Bienvenue dans cette première partie du tutoriel sur Git. Nous allons voir dans cette première
partie les logiciels de version, leur histoire et un en particulier : Git.

### Un peu d'histoire...
>Les logiciels de gestion de versions (Ou VCS en anglais, pour _Version Control System_), permettent
de stocker un ensemble de fichiers en conservant la chronologie de toutes les modifications qui 
ont été effectuées dessus. 

_Source : Wikipédia (https://fr.wikipedia.org/wiki/Logiciel_de_gestion_de_versions)_

Pensez-y comme un historique de dossier : il stocke des fichiers, du code source, de la documentation...
et se rappelle des versions précédentes ! Il gère ainsi quelles modifications sont faites sur le projet,
et agit en conséquence.

Ce concept de gestion permet notamment de gérer un projet de programmation par plusieurs développeurs,
sans se soucier de mettre en commun fastidieusement un à un les fichiers source, ce qui facilite grandement
la tâche !

Les premiers VCS voient le jour au milieu des années 70, quand IBM travaille encore sur des cartes perforées.
Aujourd'hui, il en existe plusieurs, qui ont tous leur mode de fonctionnement : la caractéristique la
plus notable à prendre en compte est la centralisation ou la décentralisation du logiciel : c'est à dire,
si les données sont regroupées sur un serveur, ou alors dispersées chez les utilisateurs qui les 
mettent en commun !

### Git : un VCS décentralisé
Nous allons nous concentrer et utiliser le logiciel nommé Git (prononcé "guite"), développé par
Linus Torvalds, le créateur même du noyau Linux ! En effet, il a été créé en 2005 lorsque le développement
et la maintenance du projet n'était plus possible .

Sa particularité est qu'il est décentralisé (voir plus haut), ce qui le distingue de SVN, son concurrent.

Sous licence GPL-2.0, il est utilisé par beaucoup de développeurs et est très souvent associé à
GitHub, qui n'est qu'un "réseau social" de Git : il permet de s'y retrouver dans ses
projets.

### Terminologie de Git
>Un projet, dans Git, est appelé un _dépôt_. Pour commencer à travailler dessus, nous verrons
qu'il est recommandé de le _forker_, ou de le _cloner_, et d'effectuer ses changements ; 
après être satisfait, l'utilisateur peut envoyer une _requête de pull_ pour demander
à l'administrateur du projet de valider et d'incorporer ses changements.

Pas de panique si vous n'y comprenez rien : nous verrons à quoi correspond tous ces
mots dans les prochaines parties. Si vous avez tout compris, je vous invite à vous
rendre maintenant à la partie 1 si vous ne possédez pas Git sur votre ordinateur de
travail, ou 2 si vous l'avez déjà (c'est le cas sur les ordinateurs de l'IUT !)
