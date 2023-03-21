# gitignore

Le fichier gitignore est très important pour la collaboration avec git. Il permet d'ignorer certains fichier et de ne pas les sauvegarder dans votre dépôt distant (github).

gitignore n'utilise pas RegEx, mais plutôt **Glob** comme language d'expression réguliaire. Leur fonctionnement est très similaire, mais **Glob** est utilisé pour correspondre les noms de fichier ou du texte dans un terminal.

En utilisant `gitignore-aide-memoire.md` ignorez les fichiers suivant dans votre projet :

- le fichier : /modules/lib/fichier-externe.txt
- tous les fichiers image avec l'Extension .png
- le dossier .vs-code


**Testez votre solution avec la commande git status**
