# Images

```markdown
# Inline
![texte alternatif](/path/to/img.jpg "titre optionel")

# Reference
![Texte alternatif][id]
[id]: url/to/image  "Titre optionel"
```
Comme vous avez dû le remarquer, les images en Markdown sont très semblables aux liens.  
La différence est la suivante :
* les crochets doivent être précédés par un point d'exclamation ;
* ils peuvent contenir un texte alternatif, qui s'affiche quand l'image ne peut être chargée.

---

Voici un quiz sur les images Markdown.

Selectionne les images valides:
- [ ] `[Google logo](https://www.google.ru/logo.png)`
- [x] `![](https://www.google.ru/logo.png)`

>Les images doivent être précédés par un point d'exclamation.
Le texte alternatif et le titre sont optionel.

Qu'est ce qui est vrai à propos de la ligne suivante: ```![Funny cat](http://cats.ru/funny.png "Share this")```
- [x] si l'url est 404, "funny cat" sera affiché
- [ ] le point d'exclamation peut être omis dans ce cas
- [ ] si l'url est 404, "Share this" sera affiché
- [x] par un passage de souris sur l'image "Share this" sera affiché

>Similairement au liens, les images peuvent avoir 3 parties: le texte alternatif, l'url et un titre. un point d'exclamation est necessaire.

---