
# Syntaxe et Commandes Markdown

Markdown est un langage de balisage léger qui permet de formater du texte facilement. Voici un guide des commandes et syntaxes Markdown les plus couramment utilisées avec leur aperçu.

## Titres

Utilisez le symbole `#` pour créer des titres, le nombre de `#` détermine le niveau du titre (de 1 à 6).

\`\`\`markdown
# Titre de niveau 1
## Titre de niveau 2
### Titre de niveau 3
#### Titre de niveau 4
##### Titre de niveau 5
###### Titre de niveau 6
\`\`\`

### Aperçu

# Titre de niveau 1
## Titre de niveau 2
### Titre de niveau 3
#### Titre de niveau 4
##### Titre de niveau 5
###### Titre de niveau 6

## Texte en Italique

Entourez le texte avec des astérisques (*) ou des tirets bas (_).

\`\`\`markdown
*Italique* ou _Italique_
\`\`\`

### Aperçu

*Italique* ou _Italique_

## Texte en Gras

Entourez le texte avec deux astérisques (**) ou deux tirets bas (__).

\`\`\`markdown
**Gras** ou __Gras__
\`\`\`

### Aperçu

**Gras** ou __Gras__

## Texte en Italique et Gras

Combinez trois astérisques (***).

\`\`\`markdown
***Italique et Gras***
\`\`\`

### Aperçu

***Italique et Gras***

## Listes

### Listes Non Ordonnées

Utilisez des tirets (-), des astérisques (*) ou des signes plus (+) pour créer des listes non ordonnées.

\`\`\`markdown
- Élément 1
- Élément 2
  - Élément 2.1
  - Élément 2.2
\`\`\`

### Aperçu

- Élément 1
- Élément 2
  - Élément 2.1
  - Élément 2.2

### Listes Ordonnées

Utilisez des chiffres suivis d'un point (1., 2., etc.) pour créer des listes ordonnées.

\`\`\`markdown
1. Élément 1
2. Élément 2
   1. Élément 2.1
   2. Élément 2.2
\`\`\`

### Aperçu

1. Élément 1
2. Élément 2
   1. Élément 2.1
   2. Élément 2.2

## Liens

Utilisez des crochets pour le texte du lien et des parenthèses pour l'URL.

\`\`\`markdown
[Texte du lien](http://exemple.com)
\`\`\`

### Aperçu

[Texte du lien](http://exemple.com)

## Images

Similaire aux liens, mais avec un point d'exclamation au début.

\`\`\`markdown
![Texte alternatif](http://exemple.com/image.jpg)
\`\`\`

### Aperçu

![Texte alternatif](http://exemple.com/image.jpg)

## Blocs de Code

Utilisez des accents graves triples (\`\`\`) avant et après le bloc de code. Vous pouvez spécifier le langage pour la coloration syntaxique.

\`\`\`markdown
\`\`\`langage
// Exemple de code
\`\`\`
\`\`\`

### Aperçu

\`\`\`go
// Exemple de code en Go
package main

import "fmt"

func main() {
    fmt.Println("Hello, World!")
}
\`\`\`

## Blocs de Citation

Utilisez le symbole `>` pour créer des blocs de citation.

\`\`\`markdown
> Ceci est une citation.
\`\`\`

### Aperçu

> Ceci est une citation.

## Tableaux

Utilisez des pipes (`|`) et des tirets (-) pour créer des tableaux.

\`\`\`markdown
| Titre 1 | Titre 2 |
|---------|---------|
| Cellule 1.1 | Cellule 1.2 |
| Cellule 2.1 | Cellule 2.2 |
\`\`\`

### Aperçu

| Titre 1 | Titre 2 |
|---------|---------|
| Cellule 1.1 | Cellule 1.2 |
| Cellule 2.1 | Cellule 2.2 |

## Lignes Horizontales

Utilisez trois tirets (---), astérisques (***) ou underscores (___) pour créer des lignes horizontales.

\`\`\`markdown
---
\`\`\`

### Aperçu

---

## Texte Barré

Utilisez deux tildes (~~) pour barrer du texte.

\`\`\`markdown
~~Texte barré~~
\`\`\`

### Aperçu

~~Texte barré~~

## Échappement de Caractères

Utilisez une barre oblique inverse (\) pour échapper des caractères spéciaux.

\`\`\`markdown
\*Ce texte ne sera pas en italique\*
\`\`\`

### Aperçu

\*Ce texte ne sera pas en italique\*

---

Ceci conclut notre guide sur les commandes et syntaxes Markdown les plus courantes. Utilisez-les pour formater vos documents de manière claire et efficace.
