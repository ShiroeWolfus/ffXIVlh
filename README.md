# FFXLH - Final Fantasy XIV : Log Horizon

## Présentation

FFXLH est un portail communautaire pour les joueurs de Final Fantasy XIV, proposant actualités, guides, événements et ressources autour du jeu. Le projet est une Single Page Application (SPA) en JavaScript moderne, avec une architecture modulaire et des données simulées en JSON.

## Fonctionnalités principales

- Accueil dynamique avec dernières news, événements et guides.
- Navigation sans rechargement de page (SPA).
- Composants réutilisables (Header, Footer, Cards).
- Données chargées dynamiquement depuis des fichiers JSON.
- Responsive design (Bootstrap).
- Prévu pour être facilement migré vers un framework moderne (Angular, React).

## Structure du projet

```
index.html
assets/
  css/
    main.css
    components/
  js/
    main.js
    components/
      Header.js
      Footer.js
      Router.js
    pages/
      HomePage.js
      guide.js
      knowledge.js
    services/
  images/
  data/
    news.json
    events.json
    guide.json
components/
  header.html
  footer.html
  news-card.html
pages/
  about.html
  community.html
  ...
```

## Installation & Lancement

1. Cloner le dépôt
2. Ouvrir `index.html` dans un navigateur moderne

## Développement

- Les composants JS sont dans `assets/js/components/`
- Les pages dynamiques sont dans `assets/js/pages/`
- Les données sont dans `assets/data/`
- Le routage est géré par `assets/js/components/Router.js`

## Roadmap

### Phase 1 : Stabilisation
- Uniformisation des noms de fichiers et structure.
- Refactoring du Router et des composants principaux.
- Centralisation de la gestion des données.

### Phase 2 : Fonctionnalités
- Navigation SPA complète.
- Gestion des erreurs et feedback utilisateur.
- Pagination et recherche.

### Phase 3 : Qualité
- Ajout de tests unitaires.
- Mise en place des outils de qualité de code.
- Documentation complète.

### Phase 4 : UI/UX
- Amélioration du responsive.
- Thème sombre/clair.
- Animations et finitions graphiques.

### Phase 5 : Déploiement
- Script de build.
- Documentation pour contributeurs.
- Publication et maintenance.

## Contribution

1. Forkez le projet
2. Créez une branche (`feature/ma-fonctionnalite`)
3. Commitez vos modifications
4. Ouvrez une Pull Request

## Licence

Projet open-source à but non commercial, inspiré de l’univers FFXIV.

---

**Contact** : Shiroe Wolfus
