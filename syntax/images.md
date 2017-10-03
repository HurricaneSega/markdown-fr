# Images

`` `Markdown
# En ligne
! [Texte alternatif] (/path/to/img.jpg "Titre facultatif")

# Référence
[Texte alternatif] [id]
[id]: url/to/image "Titre facultatif"
`` `
Comme vous l'avez peut-être remarqué, les images Markdown sont très similaires aux liens.
La différence est:
* les parenthèses doivent être précédées d'un point d'exclamation;
* ils peuvent contenir du texte alternatif, qui s'affiche lorsque l'image ne peut pas être chargée.

---

Voici un quiz sur les images de markdown.

Sélectionnez les images valides:
- [] `[Google logo] (https://www.google.ru/logo.png)`
- [x] `! [] (https://www.google.ru/logo.png) `

> Les images doivent être préfixées avec un point d'exclamation.
Le texte alternatif et un titre sont facultatifs.

Ce qui est vrai sur la ligne suivante: `` `Funny Dog (http://cats.ru/funny.png)" Share this ")` ``
- [x] si l'URL est 404, "Funny cat" sera affiché
- [] un point d'exclamation peut être omis dans ce cas
- [] si l'url est 404, "Partager ceci" sera affiché
- [x] sur la souris sur l'image

> De manière similaire aux liens, les images peuvent comporter 3 parties: le texte alternatif, l'URL et un titre. Un point d'exclamation n'est pas nécessaire.

---