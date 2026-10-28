# VDC Engineering — site vitrine statique

Une proposition de refonte premium du site vitrine de VDC Engineering, pensée pour les domaines pharmaceutique, hospitalier et les environnements maîtrisés.

## Voir le site

**Démonstration publique :** https://achraf-saidi.github.io/vdc-engineering/

Le site est également conservé dans le dépôt personnel de GitHub Pages, dans le dossier \`vdc-engineering/\`. Cette copie dans \`website/\` est le code source de la vitrine, séparé de l'application Python existante du dépôt VDC.

## Architecture

- \`index.html\` — structure, sections, contenus et métadonnées.
- \`style.css\` — identité visuelle, responsive, animations CSS.
- \`script.js\` — menu mobile, animations au défilement, compteurs, cartes extensibles.
- \`favicon.svg\` — icône originale.

Sans React, sans serveur, sans compilation : ouvrir \`index.html\` dans un navigateur suffit. Les polices et photographies sont chargées depuis des ressources externes ; une connexion internet est nécessaire pour les afficher.

## Contenus et limites

Les informations viennent du site public de l'entreprise (consulté en octobre 2026) :

- https://www.vdc-engineering.be/
- https://www.vdc-engineering.be/a-propos-de-nous/
- https://www.vdc-engineering.be/gestion-de-projets/
- https://www.vdc-engineering.be/qualificationvalidation/
- https://www.vdc-engineering.be/mise-a-disposition-de-ressources/
- https://www.vdc-engineering.be/contact/

La vitrine utilise des **photos d'illustration**, pas des images de réalisations VDC. Les coordonnées des implantations, certifications et références historiques doivent être vérifiées par l'entreprise avant toute publication commerciale.

Images sous licence Unsplash :
- Cleanroom — TECNIC Bioprocess Solutions : https://unsplash.com/photos/workers-in-protective-suits-inside-a-cleanroom-k2H_b2AEqbg
- Installations industrielles — Haberdoedas : https://unsplash.com/photos/industrial-pipes-and-machinery-inside-a-facility-TWlmgguC8HI

## Contacts et fonctionnalités

Les boutons contact ouvrent \`mailto:info@vdc-engineering.be\` ou le téléphone, car il n'y a **aucun backend** ni formulaire simulant un envoi. La navigation et les animations respectent \`prefers-reduced-motion\` et incluent des attributs d'accessibilité.

## Statut

**Maquette indépendante**, non destinée à remplacer le site officiel sans validation des droits, de l'identité visuelle et des informations. Les moteurs de recherche reçoivent \`noindex,nofollow\` pour éviter toute confusion avec la vitrine officielle.
