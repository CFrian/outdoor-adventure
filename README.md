# Outdoor-adventure — Exercice HTML/CSS

Objectif : **reproduire le même site** que la démo en utilisant **uniquement HTML et CSS** (pas de framework, pas de CMS, pas de builder).

Site de référence : https://websitedemos.net/outdoor-adventure-02/

---

## Contraintes (nouvelles consignes)

- **HTML + CSS uniquement**
- Structure HTML **simple et sémantique** (`header`, `nav`, `main`, `section`, `article`, `footer`…)
- Site **responsive** (mobile → desktop)
- Utiliser **flex** et/ou **grid**
- Privilégier les dimensions relatives (**%**, **vw/vh**, **rem**) plutôt que des px partout

---

## Livrables attendus

Un dépôt GitHub contenant au minimum :

- `index.html` (page d’accueil)
- `style.css`
- un dossier `assets/` (images, icônes…)
- autres pages : `about.html`, `services.html`, `projects.html`, `contact.html`…

> Le but principal est de **reproduire fidèlement le site** et son comportement responsive.

---

## Phase 1 — Observation & découpage

1. Faites des captures (desktop + mobile) de la page de référence.
2. Repérez les blocs principaux (layout + composants).
3. Listez :
   - typographies (polices, tailles, graisses)
   - couleurs
   - espacements
   - comportements responsive (breakpoints, empilements, alignements)

---

## Phase 2 — Développement par blocs (home)

Pour vous entraîner, la page d’accueil peut être développée bloc par bloc :

- **navbar**  
  Logo (lien), menu (`ul/li/a`) et bouton. Utilisez `display:flex` pour le positionnement.  
  Observez le comportement sur différentes largeurs d’écran (menu qui se compacte / se réorganise).

- **footer**  
  Contenu centré, espacement vertical régulier (padding). Utilisez des balises adaptées.

- **header (hero)**  
  Fond en image avec **background fixed**.  
  Les titres sont centrés, avec une ligne décorative. Attention au positionnement.

- **banner**  
  Contenu globalement centré, image décalée sur le côté.

- **section Upcoming Events**  
  Contenu centré, cartes côte à côte puis empilées en mobile.

- **section Explore The World fixed**  
  Nouveau fond fixed, contenu décalé sur la droite.

- **section Upcoming Tours & Destination**  
  Bloc plus complexe : texte + galerie d’images. À gérer en flex ou grid.  
  Observez bien la version mobile.

---

## Phase 3 — Intégration complète

1. Assemblez tous les blocs dans `index.html`.
2. Nettoyez la structure (évitez les `div` inutiles).
3. Harmonisez :
   - variables CSS (couleurs, espacements, tailles)
   - classes cohérentes
   - media queries (2 breakpoints suffisent souvent)

---

## Conseils de structure

Arborescence recommandée :

```
.
├── index.html
├── about.html
├── ----
├── style.css
└── assets/
    ├── images/
    └── icons/
```



## Rendu

- Poussez votre code sur GitHub (commits réguliers).
- Ajoutez une courte section en bas du README :
  - difficultés rencontrées
  - choix techniques (flex/grid, breakpoints…)
  - ce qui manque éventuellement

---

## Points d’attention

- Vous pouvez récupérer des ressources (images, couleurs, typos) depuis la démo.
- La démo est construite avec Wordpress/Elementor : **ne copiez pas** la structure HTML du site source.
  Faites une structure **plus simple** et sémantique.
- Pensez au responsive dès le début (mobile-first recommandé).
