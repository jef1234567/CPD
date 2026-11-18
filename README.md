# COPD – Parcours d’apprentissage (livraison 1)

Webapp pédagogique bilingue (français / anglais) d’accompagnement à l’apprentissage de la **COPD** (*Comprehensive Operations Planning Directive*) de l’OTAN, au niveau opératif, pour les stagiaires de l’**EdG** et de l’**EEM**. Construite sur le modèle de [MaisDot](https://github.com/jef1234567/maisdot) (même charte et même logique d’étapes).

Outil pédagogique : il ne se substitue ni au COPD ni à l’AJP-5 en vigueur.

## Utilisation

- **En ligne** : https://jef1234567.github.io/CPD/ (GitHub Pages, branche `main`).
- **Hors ligne** : ouvrir `index.html` dans un navigateur (fichier unique, sans dépendance).

Chaque étape se travaille en trois onglets : **Comprendre**, **S’entraîner** (quiz corrigé, étape validée à partir de 70 %), **Appliquer** (gabarits). Les saisies restent dans le navigateur (localStorage) ; sauvegarde et reprise en `.json`, impression / PDF.

## Sources

Uniquement des sources ouvertes, citées sous chaque bloc (module « Sources » de l’application) : AJP-5 Ed. B (gov.uk), fiche « AJP-5 bite size doctrine », articles en accès ouvert (Chiriac 2022, Fazekas 2022, Szabadföldi et Négyesi 2023, Marco Olivera 2023), CIMIC Handbook.

Le texte du **COPD V3.0 (2021)** n’a pas été trouvé en diffusion publique officielle : il n’a pas été utilisé. Les points qu’on n’a pas pu vérifier sont affichés dans des encadrés **« À compléter »**, à renseigner par l’instructeur.

## Structure

```
index.html   application complète (HTML, CSS, JS ; contenu dans le tableau M, sources dans SRC)
```

## Feuille de route

- [x] Livraison 1 : cadre (versions, phases stratégiques, 7 activités AJP-5), phases opératives 1 à 6, quiz, gabarits, fil rouge VIENNE (contexte), bilingue FR/EN
- [ ] Compléter les encadrés « À compléter » à partir du COPD V3.0
- [ ] Élever VIENNE au niveau opératif (QG opératif AZUR, directive stratégique, MRO)
- [ ] Examen blanc, vidéos, appli installable (PWA), autres langues
