---
layout: ../../layouts/MarkdownPostLayout.astro
title: Mon deuxième article de blog
author: Apprenti Astro
description: "Après avoir appris Astro, je ne pouvais plus m'arrêter !"
image:
    url: "https://docs.astro.build/assets/arc.webp"
    alt: "Le logo Astro sur un fond sombre avec un arc de cercle dégradé violet."
pubDate: 2022-07-08
tags: ["astro", "blogging", "apprentissage en public", "réussites"]
---
Après une première semaine réussie d'apprentissage d'Astro, j'ai décidé d'en faire un peu plus. J'ai écrit et importé un petit composant de mémoire !

```html title="index.html" del={"1. Je supprime cette ligne":2-3} ins={"2. Pour ajouter celle là":4-5} {7}
<p>test</p>

<p>Je met ici un peu de code</p>

<p>Je met ici un peu de code de Vincent</p>

<div class="test">
    Essai de vincent
</div>
```