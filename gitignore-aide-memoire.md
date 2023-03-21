# `.gitignore feuille aide-mémoire`

Créez un fichier `.gitignore` dans votre répertoire racine.
Chaque ligne de votre fichier contient une règle.
Les règles sont séparées par un retour de ligne seulement.

## Ignorer les fichiers uniques

**Doit spécifier le nom du fichier et l'extension**

```bash
exemple.txt
```

## Conserver des fichiers uniques

```bash
!exemple.txt
```

## Plusieurs fichiers avec la même extension

```bash
*.SMS
```

## Plusieurs fichiers avec le même nom

```bash
exemple*
```

## Les dossiers

```bash
exemples/
```

## Fichiers à l'intérieur d'un dossier

**Vous pouvez appliquer les mêmes techniques pour plusieurs fichiers dans le répertoire racine**

```bash
exemples/exemple.txt
```

## Tout à l'intérieur d'un dossier à l'exception de certains fichiers

**Lorsque vous ignorez tout le dossier pour la première fois, vous devez avoir une étoile à la fin.**

**L'étoile signifie que vous ignorez les fichiers à l'intérieur du dossier, tandis que l'absence d'étoile signifie que vous ignorez tout le dossier**

```bash
exemples/*
!exemples/exemple.txt
```

## Ignorer les fichiers dans tout les répertoires

**Cela ignore tous les fichiers nommés example.txt dans chaque dossier. Vous pouvez également utiliser les mêmes techniques pour ignorer des noms ou des extensions spécifiques avec cette syntaxe.**

```bash
**/exemple.txt
```

## Ignorer les fichiers uniquement dans le répertoire racine

**Doit inclure une barre oblique au début**

```bash
/exemple.txt
```

## Correspondant à plusieurs caractères

**Ceci ignore les fichiers nommés `Example.txt` et `example.txt`. Vous pouvez faire correspondre autant de personnages que vous le souhaitez à la fois.**

```bash
[Ee]xample.txt
```