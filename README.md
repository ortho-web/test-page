# Cabinet d'Orthodontie

Site statique (HTML/CSS/JS) pour un cabinet d'orthodontie, prêt pour un hébergement simple (GitHub Pages, Netlify, etc.).

- Images chargées depuis Internet (Unsplash)
- Menu mobile, défilement fluide et mise en avant de la section active
- Formulaire de contact côté client ouvrant votre messagerie (mailto)
- Sections essentielles: Urgences, Guides, Galerie avant/après, Avis Google, RDV (Doctolib), FAQ

Ouvrez `index.html` dans un navigateur pour voir la page.

Configuration optionnelle:
- Doctolib: dans `script.js`, renseignez `CONFIG.doctolibUrl` avec l’URL de votre page Doctolib.
- Avis Google: renseignez `CONFIG.googleApiKey` et `CONFIG.googlePlaceId` pour charger les avis en direct. Sans cela, des avis statiques sont affichés (fallback).
