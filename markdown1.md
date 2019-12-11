# Memo Markdown

## Menu

## Intro

**Markdown** est un système d’édition et de formatage de texte ; c’est à la fois une syntaxe, un script de conversion texte → HTML et un format de fichier. Il est couramment utilisé pour les fichiers de documentation d’un projet ou d’un jeu de données -souvent nommé readme.md. Il est stocké au format texte classique et est plus léger que sa version interprétée puisqu’il ne contient pas les balises html.

La philosophie du système veut que le texte écrit soit lisible sans interpréteur particulier en mode texte. Il est léger et épuré de l’essentiel de la verbosité d’un language balisé. Les éléments de syntaxe sont des caractères de ponctuation qui font sens visuellement même non convertis. Une fois converti, le navigateur web (qui joue alors le rôle d’interpréteur) en rendra la lecture plus claire.

Les fichiers sont généralement enregistrés avec l’extension .md (ou .markdown ) pour indiquer aux interpréteur la nature du texte qu’il vont lire ; mais ça n’a rien d’obligatoire.

Comme le résultat sera exporté en HMTL, vous pouvez tout à fait introduire directement des balises HTML dans votre texte ; mais celui-ci deviendra moins lisible et ne pourra plus être édité par quelqu’un ne maîtrisant pas le HTML. Attention, le formatage markdown ne sera pas appliqué à l’intérieur de ces balises.

## Headings

Pour créer un titre, on ajoute un signe numérique # devant un mot ou une phrase. Le nombre de signes numériques utilisés doit correspondre au niveau de l'en-tête.

- #### Exemples
 
  ##### En Markdown

1. \# Heading level 1
2. \## Heading level 2
3. \### Heading level 3

##### Output

1. # Heading level 1
2. # Heading level 2
3. # Heading level 3
  
Il existe *une syntaxe alternative* :

on ajoute == caractères en dessous de heading level 1 ou --

- #### Exemples

Heading level 1

\================

## Paragraphes

Pour créer des paragraphes, on utilise une ligne vierge pour séparer une ou plusieurs lignes de texte. 

## Line Breaks 

Pour créer une ligne break \<br>, finir la ligne avec 2 espaces ou plus et ensuite return.

## Emphasis

On peut mettre l'accent en mettant le texte en gras (bold) ou en italique (italic)

### Bold
On ajoute ** ou __ avant et après un mot ou une phrase

#### Exemple
Vive `**Be Code**`

### Italic
On ajoute * ou _ avant et après un mot ou une phrase

- #### Exemple 
Vive `*Be Code*`

### Bold and italic
On ajoute *** ou ___avant et après un mot ou une phrase

## Blockquotes
On ajoute > avant un paragraphe

- #### Exemple
`> Hello World!`
donne :
> Hello World!
donne:

##### Si on a plusieurs paragraphes:

`> Je suis apprenant Be Code`

`> `

`> Je suis à Charleroi `

donne :

> Je suis apprenant Be Code
>
> Je suis à Charleroi 


##### Imbrications:

`> Je suis apprenant Be Code`

`> `

`>> Je suis à Charleroi `

donne:

> Je suis apprenant Be Code
> 
>> Je suis à Charleroi 

##### Blockquotes et autres éléments: 
Blockquotes peuvent contenir d'autres éléments Markdown. Pas tous les éléments, il faut tester.

