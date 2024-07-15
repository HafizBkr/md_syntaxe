
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


### Tâches (Listes de Tâches)

Les listes de tâches sont créées en utilisant des crochets et des espaces. Cochez les tâches avec un `x`.

\`\`\`markdown
- [ ] Tâche à faire
- [x] Tâche accomplie
\`\`\`

### Aperçu

- [ ] Tâche à faire
- [x] Tâche accomplie

### Texte en Exposant

Pour le texte en exposant, utilisez le symbole `^` avant et après le texte.

\`\`\`markdown
E = mc^2^
\`\`\`

### Aperçu

E = mc^2^

### Commentaires HTML

Vous pouvez insérer des commentaires HTML dans votre document Markdown. Ces commentaires ne seront pas affichés dans la version rendue.

\`\`\`markdown
<!-- Ceci est un commentaire HTML -->
\`\`\`

### Aperçu

<!-- Ceci est un commentaire HTML -->

### Texte en Code Inline

Pour insérer du texte en code inline, utilisez des accents graves (\`).

\`\`\`markdown
Voici un exemple de \`code inline\`.
\`\`\`

### Aperçu

Voici un exemple de \`code inline\`.

### Blocs de Code Indentés

Vous pouvez également créer des blocs de code en indentant chaque ligne avec quatre espaces.

    Voici un bloc de code indenté.
    Chaque ligne commence avec quatre espaces.

### Aperçu

    Voici un bloc de code indenté.
    Chaque ligne commence avec quatre espaces.

### Sauts de Ligne

Pour insérer un saut de ligne sans commencer un nouveau paragraphe, ajoutez deux espaces à la fin de la ligne.

\`\`\`markdown
Ligne 1 avec deux espaces à la fin.  
Ligne 2 sur une nouvelle ligne.
\`\`\`

### Aperçu

Ligne 1 avec deux espaces à la fin.  
Ligne 2 sur une nouvelle ligne.

### Encadrés

Pour créer des encadrés colorés sur certaines plateformes Markdown (comme GitHub), utilisez des points d'exclamation ou des astérisques avec des mots-clés spécifiques.

\`\`\`markdown
> :warning: **Avertissement:** Ceci est un encadré d'avertissement.
> :information_source: **Information:** Ceci est un encadré d'information.
\`\`\`

### Aperçu

> :warning: **Avertissement:** Ceci est un encadré d'avertissement.
> :information_source: **Information:** Ceci est un encadré d'information.

### Emphase combinée

Vous pouvez combiner gras et italique pour mettre encore plus en valeur du texte.

\`\`\`markdown
***Texte en italique et gras***
\`\`\`

### Aperçu

***Texte en italique et gras***

