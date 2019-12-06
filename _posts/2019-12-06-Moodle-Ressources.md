---
layout: post
title: Moodle Ressources
image: ./image/media/vidéo.png
---

L'exemple suivant contient une page Moodle avec :
  - une vidéo
  - un lien externe vers un site internet (repéré sur [Eduthèque](http://www.edutheque.fr/accueil.html))

![Vidéo et lien](/images/media/vidéo.png "Page Moodle avec une vidéo et un lien")

## Lien externe

Dans Moodle, il est possible d'**ajouter un lien** à son cours à travers une ressource spécifique, la ressource URL.

![Ressource URL](/images/media/Moodle_URL.png)

Mais l'éditeur permet également très aisément d'ajouter un lien vers une page interne ou un site externe en cliquant sur **l'icône "Lien"** de la barre d'édition.

![Lien](/images/media/Moodle_BarreEdition_Lien.png)

Il est bon d'ajouter un titre à ce lien, pour des raisons d'accessibilité. Si on veut que le lien s'ouvre dans une nouvelle page, le spécifie dans l'onglet "Cible de ce lien".

![Option du lien](/images/media/Moodle_Lien_EditionLien2.png)


## Intégration de la vidéo

Pour intégrer une vidéo qui est présente dans un autre site, on utilisera un **iframe**.

La plupart des sites hébergeant des vidéos proposent **un code d'intégration** de la vidéo.

![Code d'intégration d'une vidéo](/images/media/IntegrationVideo.gif)

Dans Moodle, il faut coller ce code dans la page dans laquelle vous voulez que cette vidéo apparaisse.

Exemple :
```html
<iframe src="https://www.youtube.com/embed/Cpa8s9UqzLc" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="" width="560" height="315" frameborder="0"></iframe>
```
**Attention** toutefois, il faut coller ce code dans le code de la page. Pour le faire apparaître, il faut utiliser la barre d'édition et cliquer ici :

![Icône code](/images/media/CodeIntegration.png)


## Ergonomie

Du point de vue de l'apparence de la page, **le petit cadre bleu** est créé avec le code suivant :

```html
<div class="d-flex align-items-center p-3 my-3 text-white-50 bg-info rounded box-shadow">
<div class="lh-100">
<h3 class="mb-0 text-white lh-100">Vidéo du musée d'Orsay<span class="small"></span></h3>
</div>
</div>
```

L'ensemble de la page est encadré par un petit cadre grâce au code suivant

```html
<div class="container">
<div class="card">
<div class="card-body">
.... <!-- ... Le reste de votre code-->
</div>
</div>
</div>
```
