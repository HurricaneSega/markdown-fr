# Titres

Lorsque nous avons commencé à écrire un document de réduction, nous devons ajouter un titre et des sous-titres.

Markdown prend en charge deux styles d'en-têtes, Setext et atx.

Les en-têtes de type Setext sont "soulignés" en utilisant des signes égaux (pour les en-têtes de premier niveau) et les tirets (pour les en-têtes de second niveau). Par exemple:

`` `
C'est un H1
=============

C'est un H2
-------------
`` `

Tout le nombre de sous-lignes = 's or-s fonctionnera.

Les en-têtes style Atx utilisent 1-6 caractères hash au début de la ligne, correspondant aux niveaux d'en-tête 1-6. Par exemple:

`` `
# C'est un H1

## Ceci est un H2

###### Ceci est un H6
`` `


En option, vous pouvez "fermer" les en-têtes de type atx. Ceci est purement cosmétique - vous pouvez utiliser cela si vous le pensez mieux. Les hachages de fermeture n'ont même pas besoin de correspondre au nombre de hachages utilisés pour ouvrir l'en-tête. (Le nombre de hachages d'ouverture détermine le niveau d'en-tête).

`` `
# C'est un H1 #

## Ceci est un H2 ##

### Ceci est un H3 ######
`` `


---

Voici un quiz sur les titres de réduction.

Sélectionnez les en-têtes valides:
- [x] `# hello`
- [] `# hello`

> Les en-têtes ont besoin d'espace entre les caractères hash et le texte.

Sélectionnez les en-têtes valides:
- []
`` `
tester
########
`` `
- [X]
`` `
tester
=======
`` `

> Seul '=' et '-' sont acceptés pour souligner un en-tête.

---