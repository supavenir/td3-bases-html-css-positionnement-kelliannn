[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/ed4w044B)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=21151639)
## Bloc 1 — Bases HTML/CSS • Positionnement (TD3)
Durée indicative: 4 h

---

### 🎯 Objectifs
- Approfondir le positionnement CSS (flexbox, colonnes, positionnement, images).
- Structurer des pages en blocs réutilisables (header/main/footer, sections).
- Mettre en pratique une méthodologie Git (branche, Pull Request, code review).
- Publier les livrables et garantir leur qualité (validation W3C).

---

### ✅ Pré‑requis
- Avoir accepté l’assignment « td3 » sur GitHub Classroom.
- Disposer d’une connexion internet et de droits administrateur sur le poste.

---

### 📦 Organisation du repository
- Travailler en local, puis commit/push régulièrement.
- En fin de travaux, ouvrir une Pull Request vers `main` et mentionner `@jcheron` pour la revue.

Chemins de travail pour ce TD:
- HTML: `docs/pages/td3/`
- CSS: `docs/assets/css/td3/`

Arborescence suggérée:
```
docs/
├─ index.html
├─ assets/
│  └─ css/
│     ├─ main.css
│     └─ td3/
│        ├─ conseil-gestion.css
│        └─ web-arena.css
└─ pages/
   └─ td3/
      ├─ conseil-gestion.html
      ├─ about-us.html
      └─ blog.html
```

---

### 📚 Lectures et ressources recommandées
- [Disposition en colonnes (CSS Multi‑column)](https://developer.mozilla.org/fr/docs/Web/CSS/CSS_multicol_layout)
- [Flexbox (guide complet)](https://developer.mozilla.org/fr/docs/Web/CSS/CSS_flexible_box_layout)
- Positionnement:
  - [Guide (concepts et flux)](https://developer.mozilla.org/fr/docs/Learn/CSS/CSS_layout/Positioning)
  - [Référence de la propriété `position`](https://developer.mozilla.org/fr/docs/Web/CSS/position)
- Images:
  - [Images en HTML](https://developer.mozilla.org/fr/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)
  - [`object-fit` (recadrage CSS)](https://developer.mozilla.org/fr/docs/Web/CSS/object-fit)
- [Bases CSS (rappels)](https://developer.mozilla.org/fr/docs/Learn/CSS/First_steps)
- Débogage:
  - [Déboguer le CSS](https://developer.mozilla.org/fr/docs/Learn/CSS/Building_blocks/Debugging_CSS)
  - [Outils de développement (MDN)](https://developer.mozilla.org/fr/docs/Tools)
- Références:
  - [Référence HTML](https://developer.mozilla.org/fr/docs/Web/HTML/Reference)
  - [Référence CSS](https://developer.mozilla.org/fr/docs/Web/CSS/Reference)

Autres supports en français:
- [Microsoft Learn — Parcours Web](https://learn.microsoft.com/fr-fr/training/browse/?terms=web%20development)

### 🧪 Exercices pour s’entraîner
- [Flexbox Froggy (FR)](https://flexboxfroggy.com/#fr)
- [CSS Diner (sélecteurs CSS)](https://flukeout.github.io/)

### 🛠️ Outils
- [ColorZilla (Chrome)](https://www.colorzilla.com/chrome/)
- [ColorZilla (Firefox)](https://www.colorzilla.com/firefox/)
- [Validateur HTML (W3C)](https://validator.w3.org/)
- [Validateur CSS (W3C)](https://jigsaw.w3.org/css-validator/)

---

### 🧪 Travaux à réaliser

#### 1) Jeu — Flexbox Froggy
- S’exercer au positionnement avec Flexbox Froggy.
- Conseil: répartir les niveaux sur plusieurs sessions pour une meilleure assimilation.

---

#### 2) Conseil en gestion — Blocs
À partir de « doc-conseil-gestion-bloc.pdf »:
- Identifier:
  - La structure générale des blocs de la page.
  - Les groupes d’éléments partageant une structure commune.
- Réaliser la structure HTML, puis les styles CSS correspondants.
- Utiliser Font Awesome pour les icônes (équivalences approchantes acceptées).
- Vérifier le rendu régulièrement.

Livrables:
- HTML: `docs/pages/td3/conseil-gestion.html`
- CSS: `docs/assets/css/td3/conseil-gestion.css`

Recommandations:
- Découper en composants (cartes/blocs) et employer des classes réutilisables.
- Utiliser flexbox pour l’alignement et la distribution des blocs.

---

#### 3) Web‑arena — Page « About us » (blocs de page)
À partir de « doc-web-arena-about-us.pdf »:
- Identifier:
  - Les couleurs (via ColorZilla).
  - La structure générale et les éléments communs (cartes, boutons, menus).
- Créer la structure HTML et les styles CSS.
- Police requise: Montserrat.
- Cas particuliers à gérer:
  - Élément de menu actif.
  - État au survol (hover) d’un élément de menu.
  - État au survol (hover) d’un bouton.

Livrables:
- HTML: `docs/pages/td3/about-us.html`
- CSS: `docs/assets/css/td3/web-arena.css`

---

#### 4) Web‑arena — Page Blog (colonnes)
À partir de « doc-web-arena-blog.pdf »:
- Identifier:
  - Les couleurs (ColorZilla).
  - La structure générale en colonnes (ex.: contenu principal + barre latérale).
  - Les groupes d’éléments communs (articles, tags, pagination, etc.).
- Réutiliser/compléter la feuille de style précédente (`web-arena.css`).
- Cas particuliers à gérer:
  - État au survol d’un élément de menu.
  - État au survol d’un tag.
- Structure globale: `header / main / footer`.

Livrables:
- HTML: `docs/pages/td3/blog.html`
- CSS: `docs/assets/css/td3/web-arena.css` (partagée avec la page About)

---

#### 5) Mise à jour de l’index
- Mettre à jour `docs/index.html` afin d’ajouter des liens vers:
  - `conseil-gestion.html`
  - `about-us.html`
  - `blog.html`

Checklist:
- [ ] Liens présents et fonctionnels en local et sur GitHub Pages
- [ ] Titres et courts descriptifs pour chaque page

---

#### 6) Vérifications (qualité)
- Valider le HTML et le CSS avec les validateurs W3C.
- Corriger les erreurs et avertissements (warnings).
- Effectuer un contrôle visuel (desktop, zoom, contrastes).

À consigner dans la Pull Request:
- [ ] Captures d’écran finales
- [ ] Notes sur les écarts résiduels par rapport aux maquettes (le cas échéant)

---

### 💡 Conseils de mise en œuvre
- Commencer par la structure HTML sémantique, puis ajouter les styles.
- Utiliser flexbox pour l’alignement, l’espacement et les colonnes simples.
- Centraliser la palette de couleurs et la typographie via des variables CSS si possible.
- Privilégier les classes réutilisables; limiter le positionnement absolu aux cas nécessaires.
- Rédiger des messages de commit clairs; documenter les choix significatifs dans la description de la PR.

---

### 📤 Récapitulatif des livrables
- `docs/pages/td3/conseil-gestion.html` + `docs/assets/css/td3/conseil-gestion.css`
- `docs/pages/td3/about-us.html` + `docs/assets/css/td3/web-arena.css`
- `docs/pages/td3/blog.html` (même CSS partagée)
- `docs/index.html` mis à jour
- Captures/validations W3C et notes de vérification dans la PR
