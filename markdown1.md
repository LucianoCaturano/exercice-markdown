# Memo Markdown
## Menu
[A lire](README.md)     
[Les différentes sources](sources.md)
## Intro

## Listes

### Listes ordonnées

Pour créer une liste ordonées il faut toujours commencer par la liste par le numéro "1.". Le reste des numéros n'a pas d'importance et permet les numéros affichés seront recalculer automatiquement dans un ordre logique.

#### Markdown

    1. First item
    2. Second item
    3. Third item
    4. Fourth item

#### Rendu à l'écran

1. First item

2. Second item

3. Third item

4. Fourth item


### Listes non ordonées

Les listes non ordonées peuvent utiliser les puces suivantes: 

- First item (- First item)
* First item (* First item)
+ First item (+ First item)

### Créer des sous listes

Pour créer des sous listes il faut ajouter un tab (ou 4 espace et reprendre une nouvelle liste).

#### Markdown
    - First item
    - Second item
    - Third item
        - Indented item
        - Indented item
    - Fourth item

#### Rendu à l'écran

- First item
- Second item
- Third item
    - Indented item
    - Indented item
- Fourth item

### Block-codes

Les block-codes sont utilisés pour écrire sur la programmation ou le code source de balisage. Plutôt que de former des paragraphes normaux, les lignes d'un bloc de code sont interprétées littéralement. 

    <html>
          <head>
            <title>test</title>
          </head>

### Insertion d'images

Pour ajouter une image, ajoutez un point d'exclamation (!), Suivi du texte alternatif entre crochets et du chemin ou de l'URL de l'élément d'image entre parenthèses. Vous pouvez éventuellement ajouter un titre après l'URL entre parenthèses.

    ![Markdown](/assets/markdown.png)
![Markdown](/assets/markdown.png)

Pour les images animées c'est la même chose, il faut juste change le .png par un .gif .

    ![Good](/assets/markdown.gif)
![Good](/assets/markdown.gif)
