# Introduction à Markdown

Markdown est un langage de balisage léger, conçu pour faciliter l’écriture et la mise en forme de texte en utilisant une syntaxe simple.  
Il est largement utilisé pour rédiger des documents, des articles, des fichiers README, et même des commentaires sur des forums.  

Pourquoi utiliser Markdown ?  

• Lisibilité : Le texte en Markdown est facile à lire, même sans conversion.  
• Simplicité : La syntaxe est intuitive et nécessite peu d’apprentissage.  
• Interopérabilité : De nombreux outils et plateformes (comme GitHub, GitLab, et des blogs) prennent en charge Markdown.  

## Syntaxe de base  

### Titres  

Pour créer des titres, utilise le symbole dièse (#). Le nombre de dièses détermine le niveau du titre :  
```markdown
# Titre de niveau 1
## Titre de niveau 2
### Titre de niveau 3
#### Titre de niveau 4
##### Titre de niveau 5
###### Titre de niveau 6
```

### Texte en gras et italique  

Pour mettre du texte en gras ou en italique, utilise les astérisques (*) ou les tirets bas (_):  
```markdown
*Italique* ou _Italique_  
**Gras** ou __Gras__  
**_Gras et Italique_**
```

### Listes  

Listes à puces  
Utilise des astérisques, des plus ou des tirets pour créer des listes à puces :  
```markdown
- Élément 1
- Élément 2
    - Sous-élément 2.1
    - Sous-élément 2.2
```

### Listes numérotées  

Pour les listes numérotées, utilise simplement des chiffres suivis d’un point :  
```markdown
1. Premier élément
2. Deuxième élément
    1. Sous-élément 2.1
    2. Sous-élément 2.2
```

### Liens et images  

Liens  
Pour créer des liens, utilise la syntaxe suivante :  
```markdown
[Texte du lien](URL "Titre optionnel")
```

### Images  

Pour insérer une image, la syntaxe est similaire à celle des liens, mais commence par un point d’exclamation :  
```markdown
![Texte alternatif](URL_de_l_image "Titre optionnel")
```

### Blocs de code

Pour mettre en forme des blocs de code, utilise des backticks (```) pour les blocs multi-lignes ou des backticks simples pour du code en ligne :
```markdown
- simple ligne
`code en ligne`

- multiligne
    ```
    je suis du code
    sur plusieurs ligne
    ```
```

### Citations  

Pour citer du texte, commence la ligne avec le symbole > :  
```markdown
> Ceci est une citation.
```

## Syntaxe avancée  

### Tables  

Pour créer un tableau, utilise la syntaxe suivante :  
```markdown
| En-tête 1 | En-tête 2 |
|-----------|-----------|
| Cellule 1 | Cellule 2 |
| Cellule 3 | Cellule 4 |
```

### Listes de définition

Pour créer une liste de définitions :
```markdown
Terme
:   Définition du terme.
```

### Lignes horizontales

Pour ajouter une ligne horizontale, utilise trois tirets, trois astérisques ou trois underscores :
```markdown
---
```

## Commandes Markdown

Voici quelques commandes Markdown courantes :
```markdown
Commande	Description
# Titre	Crée un titre de niveau 1
## Titre	Crée un titre de niveau 2
*italique*	Met le texte en italique
**gras**	Met le texte en gras
- Élément	Crée un élément de liste à puces
1. Élément	Crée un élément de liste numérotée
   [Lien](URL)	Crée un lien
   ![Image](URL)	Insère une image
```	Démarre un bloc de code
>	Crée une citation
`	En-tête
---	Ajoute une ligne horizontale
```

## Conclusion  

Markdown est un langage puissant et facile à apprendre, idéal pour créer des documents formatés sans complexité.  
Que tu sois un développeur, un écrivain ou un simple utilisateur, Markdown peut t’aider à rendre ton texte plus structuré et attrayant.
