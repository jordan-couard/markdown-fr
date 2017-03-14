# Titres

Comme nous avons commencé à écrire un document de réduction, nous devons ajouter un titre et quelques sous-entêtes.

Markdown prend en charge deux styles d'en-têtes, Setext et atx.

Les en-têtes de type Setext sont «soulignés» en utilisant des signes d'égalité (pour les en-têtes de premier niveau) et des tirets (pour les en-têtes de second niveau). Par exemple:

```
# H #
=============

## H ##
=============
```

Tout le nombre de sous-titres = 's ou -'s fonctionnera.

Les en-têtes Atx-style utilisent 1-6 caractères de hachage au début de la ligne, correspondant aux niveaux d'en-tête 1-6. Par exemple:

```
# H #
===========

## H ##
===========

###### H ######
===========
```

En option, vous pouvez "fermer" des en-têtes style atx. C'est purement cosmétique - vous pouvez utiliser ceci si vous pensez qu'il semble mieux. Les hachages de fermeture n'ont même pas besoin de correspondre au nombre de hachages utilisés pour ouvrir l'en-tête. (Le nombre de hachures d'ouverture détermine le niveau d'en-tête.):

```
# H #
=============

## H ##
=============

### H ######
=============
```


---

Voici un quiz sur les titres de rabais.

Sélectionnez les en-têtes valides:
- [x] `# hello`
- [ ] `#hello`

> Les en-têtes ont besoin d'espace entre les caractères de hachage et le texte.

Sélectionnez les en-têtes valides:
- [ ]  
```
test
########
```
- [x]   
```
test
=======
```

> Seuls '=' et '-' sont acceptés pour souligner un en-tête.

---
