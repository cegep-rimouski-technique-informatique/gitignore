# gitignore

Le fichier gitignore est très important pour la collaboration avec git. Il permet d'ignorer certains fichiers et de ne pas les sauvegarder dans votre dépôt distant (github).

gitignore n'utilise pas RegEx, mais plutôt **Glob** comme langage d'expression régulière. Leur fonctionnement est très similaire, mais **Glob** est utilisé pour correspondre les noms de fichier ou du texte dans un terminal.

Créez un fichier .gitignore et utilisez `gitignore-aide-memoire.md` pour ignorez les fichiers suivants dans votre projet :

- le fichier : /node_modules/lib/fichier-externe.txt
- tous les fichiers d'image avec l'extension .png
- l'intégralité du dossier .vs-code
- tous les fichiers avec le nom `main`
- les fichiers de config propre à votre IDE et OS (fichiers cachés)

**Testez votre solution avec la commande:**  
```
git rm -r --cached . && git status 
```

**les fichiers ignorés ne devraient pas être affichés**

