## Git
Système de gestion de version. Pour des fichiers en tout genres (principalement du code)

Il se base sur les concepts suivants.

- Index: Liste des fichiers dont les modifications sont suivies par git.
- Commit: Engagement sur des modifications AVEC OBLIGATOIREMENT UN MESSAGE.
- Branch: Label de catégorie pour un commit

### Utilisation Git
1. taper `git init` dans un terminal, à la racine du dossier que l'on veut suivre 
2. taper `git add <filename>` ajoute un fichier / dossier à l'index de git
3. taper `git rm <filename>` enlève un fichier / dossier à l'index de git
4. taper `git commit -m "message"` engage sur des fichiers
5. taper `git branch <branchname>` pour créer une branche
6. taper `git branch` pour lister les branches
7. taper `git checkout <branchname>` pour basculer sur la branche