---
layout: post
title: Orchestrer ressources et activités dans une page  
subtitle: Un exemple de page avec un grain de manuel
image: /img/media/ressource3.png
tags: [moodle, ressources, manuel, activité, ergonomie]
---

La page ci-dessous contient à la fois des informations et des consignes mais également un grain extrait du manuel de la classe ; ces différentes ressources débouchent sur une activité de rédaction sur support papier.

![Ressources et exercice](/img/media/ressource3.png)

## Exporter un grain de manuel

Le manuel utilisé dans la classe est le manuel de français du [Livre Scolaire](https://www.lelivrescolaire.fr/lycee/francais).

L'export d'un grain se fait aisément :

![Export d'un grain de manuel](/img/media/exportGrainManuel.gif "Export d'un grain de manuel")

Il faut ensuite l'intégrer dans le code d'une  page Moodle (voir [cet article](https://nbannier.github.io/2019-12-06-Une-Page-Moodle-Simple/)).

## Des liens vers différentes ressources

La page contient également des liens vers différentes ressources, essentiellement, des liens vers des fichiers déposés dans le cours.

Pour plus de clarté dans le cours, j'utilise fréquemment la fonction "Cacher / Rendre disponible" de Moodle. Cela permet selon moi d'organiser plus clairement les ressources pour les élèves.

![Cacher puis rendre disponible une ressource ou une activité dans Moodle](/img/media/moodleCacherDisponible.gif "Cacher puis rendre disponible une ressource ou une activité dans Moodle")

Ensuite, j'insère un lien dans ma page vers cette ressource.

Voici le code que j'utilise :

```html
<p>Exemple de paragraphe rédigé <a target="_blank" href="https://0672604s.moodle.monbureaunumerique.fr/pluginfile.php/13049/mod_resource/content/1/AnalyseKilty_Paragraphe.html" title="Lien vers un exemple de paragraphe rédigé" class="btn-sm btn-outline-primary">Lien</a></p>
```

## Vers l'activité d'écriture

En classe, j'ai vidéoprojeté ces différentes ressources ; les élèves peuvent ensuite les retrouver facilement au moment de l'exercice d'écriture dont les consignes sont différenciées et qui est réalisé sur papier. Papier et ordinateur sont ici complémentaires.
