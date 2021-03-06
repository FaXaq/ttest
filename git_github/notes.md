## Git
Système de gestion de version. Pour des fichiers en tout genres (principalement du code)

Il se base sur les concepts suivants.

- Index: Liste des fichiers dont les modifications sont suivies par git.
- Commit: Engagement sur des modifications AVEC OBLIGATOIREMENT UN MESSAGE.
- Branch: Label de catégorie pour un commit

### Utilisation Git
0. taper `git status` pour connaitre l'état de l'index dans le répertoire git courant
1. taper `git init` dans un terminal, à la racine du dossier que l'on veut suivre 
2. taper `git add <filename>` ajoute un fichier / dossier à l'index de git
3. taper `git rm <filename>` enlève un fichier / dossier à l'index de git
4. taper `git commit -m "message"` engage sur des fichiers
5. taper `git branch <branchname>` pour créer une branche
6. taper `git branch` pour lister les branches
7. taper `git checkout <branchname>` pour basculer sur la branche
8. taper `git merge <branchname>` pour fusionner la branchname avec la branche sur laquelle on est
9. COUCOU


## Github
Application web permettant de voir et favoriser la collaboration autour de code sources gérées par Git.

Il se base sur des concepts:
- Répertoire : Dossier hébergeant le code source d'un projet
- Remote : Adresse git de votre répertoire distant
- Pull Request : Façon de merger une branche dans une autre avec Github


### Utilisation Github
0. taper `git remote add <remotename> <url>` pour ajouter une remote (adresse d'un répertoire distant)
1. taper `git push <remotename> <branchname>` pour envoyer les COMMITS sur le répertoire distant
2. taper `git clone <url>` pour cloner le répertoire venant de github

## Git flow
Lisez les bonnes pratiques mais n'utilisez pas l'outil
[https://fr.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow](https://fr.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow)