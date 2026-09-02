# Portfolio — GitHub Pages

## Structure
- `index.html` — page principale du portfolio
- `assets/thumbnails/` — exemples de miniatures YouTube
- `videos/` — dossier prévu pour les vidéos du portfolio

## Ajouter une vidéo
Place le fichier `.mp4` dans `videos/`, puis ajoute un bloc vidéo dans la section `data-canva-panel="videos"` de `index.html`.

Format recommandé : MP4 / H.264 vidéo / AAC audio.

Exemple :
```html
<video class="portfolio-video" controls playsinline preload="metadata">
  <source src="videos/mon-montage.mp4" type="video/mp4">
</video>
```

Le portfolio conserve les catégories : **MES SERVICES**, **Véhicules d’Exception**, **Vidéos** et **Miniature Youtube**.

L’expérience affichée est **6+ Années d’expérience**.
