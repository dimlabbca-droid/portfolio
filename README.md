# Dimitri Labbe Portfolio

Portfolio personnel bilingue français / anglais de Dimitri Labbe.

## Contenu

- Page principale: `index.html`
- Images: `images/`
- Videos: `videos/`
- CV telechargeable: `assets/Dimitri_Labbe_Resume.pdf`
- Page cachee pour carte contact: `carte-dimitri/`
- Configuration Netlify headers: `_headers`
- Robots noindex pour la page carte contact: `robots.txt`

## Lancer le site en local

Comme le site est statique, il peut etre ouvert directement dans un navigateur:

```bash
open index.html
```

Ou avec un serveur local:

```bash
python3 -m http.server 8080
```

Puis ouvrir:

```text
http://localhost:8080
```

## Deploiement

Le site peut etre depose sur GitHub puis connecte a Netlify.

Pour GitHub Pages, garder le fichier `.nojekyll` afin que les fichiers statiques soient servis correctement.

## Page carte contact

La page cachee pour le QR code est:

```text
https://dimlabb.netlify.app/carte-dimitri/
```

Elle redirige vers le fichier vCard:

```text
carte-dimitri/Dimitri-Labbe.vcf
```
