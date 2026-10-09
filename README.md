# Nom du projet : Élan Fitness

Migration d'un site one-page vers un site multipage. Pages à réaliser : Accueil, Programmes, À propos et Contactez-nous.

## 🛠️ Stack technologique

* **HTML5 :** Architecture sémantique.
* **CSS3 :** Système de mise en page (Flexbox, marges, espacements, couleurs...).
* **Déploiement :** GitHub Pages

## 🗺️ Architecture de l'information (Plan du site)

* **Accueil (`./index.html`) :** La page d'accueil (landing page).
* **À propos (`./about.html`) :** Présentation et mission de l'entreprise.
* **Programmes (`./services.html`) :** Programmes d'entraînement et tarif de chaque formule.
* **Contact (`./contact.html`) :** Formulaire de contact.

## 🚀 Lancement en local

1. Clonez ce dépôt ou téléchargez l'archive ZIP.
2. Ouvrez le dossier du projet dans un éditeur de texte tel que [VS Code](https://visualstudio.com).
3. Ouvrez `index.html` directement dans un navigateur web, ou utilisez l'extension Live Server dans VS Code pour visualiser les mises à jour en temps réel.

## 🎨 Règles de design et de code

* **Architecture CSS :** Le style global, la navigation et les pieds de page se trouvent dans `./style.css`, et le style spécifique au formulaire de contact se trouve dans `./style-contact.css`.
* **Conventions de nommage :** Utilisez des minuscules pour l'ensemble des noms de fichiers (ex. `a-propos.html`).
* **Composants sémantiques :** Veillez à ce que toutes les nouvelles pages intègrent les balises de structure `<header>`, `<nav>`, `<main>` et `<footer>`.

## 🏗️ Structure

```
Elan-Fitness/
│
├── index.html                 # Page d'accueil, page officielle.
├── README.md                  # Documentation du projet et instructions d'installation.
├── a-propos.html/             # Sous-dossiers pour les pages internes (à propos, programmes, contact).
├── programmes.html/
├── contact.html/
├── styles.css                # Feuille de style globale partagée entre les pages.
├── style-contact.css         # Feuille de style dédiée au formulaire de la page contact.
│
└── img/                      # Médias
├── logo.png/             # Photo
└── ...                   # Photos, icônes, logos
```

## 🤔 Q & R

1. Qu'est-ce que la méthode Agile, quel est l'un de ses frameworks, et comment cela fonctionne-t-il ?
  * Scrum est l'un des frameworks Agiles. Il structure le travail en cycles courts et limités dans le temps (généralement de 1 à 4 semaines) appelés sprints.
  * Rôles Scrum :
  * Product Owner : Gère le backlog produit, priorise les fonctionnalités et veille à ce que l'équipe crée un maximum de valeur métier.
  * Scrum Master : Agit comme un coach pour l'équipe, facilite les événements Scrum et élimine les blocages.
  * Équipe de développement : Un groupe auto-organisé et pluridisciplinaire qui conçoit, teste et livre le travail.


2. Qu'est-ce que HTML, qu'est-ce que CSS, à quoi servent-ils, et que sont les balises HTML ?
  * Le HTML construit la structure et ajoute du contenu à un site web, tandis que le CSS gère le design, la mise en page et l'apparence visuelle globale.
  `Considérez le HTML comme le squelette ou la charpente d'une maison, et le CSS comme la peinture, la décoration intérieure et le style qui la rendent attrayante (le JS correspond aux mouvements)`.
  * `<!DOCTYPE html><html><head></head><body><></></body></html>`


3. Que signifie SEO et quels sont ses 3 piliers ?
  * Le SEO (Search Engine Optimisation), ou optimisation pour les moteurs de recherche, est une pratique visant à améliorer la structure, le contenu et le positionnement d'une page ou d'un site web.
   * Les piliers du SEO sont au nombre de 3 : le SEO on-page, le SEO off-page et le SEO technique.
   * SEO on-page :
    * Titre optimisé, nom de domaine explicite et accrocheur, méta-description, respect de la hiérarchie des titres (headings).
 
 
   * SEO off-page :
    * Backlinks (sites web de confiance), link baiting (votre site devient une référence pour les autres).
   
   
   * SEO technique (Infrastructure) :
    * Vitesse de chargement (2-3s), certificat SSL (https://), responsive design (indexation Mobile-First).


4. Qu'est-ce que l'UX/UI, à quoi cela sert-il, et pourquoi est-ce important avant de commencer à écrire du code ?
  1. UX/UI
    * UX : (User Experience / Expérience utilisateur), l'expérience vécue par un utilisateur lorsqu'il consulte le site web, du début à la fin.
    * UI : (User Interface / Interface utilisateur), l'apparence d'un site web. Tout ce que l'œil peut voir : hiérarchie des informations, typographie, boutons, couleurs, images et icônes...


  2. La décomposition séquentielle des étapes par lesquelles passe un design UI/UX :
    * Recherche & Stratégie (Les fondations - Recherche utilisateur - Personas utilisateurs - Carte d'empathie) -> Architecture de l'information & Planification (Zoning - Wireframes) -> Design interactif & visuel (Prototypes - Design UI) -> Tests & Validation (Tests d'utilisabilité - Ajustements itératifs) -> Passation & Implémentation (Handoff design - QA design)


5. Qu'est-ce que le responsive design, et que vaut-il mieux développer en premier : la version mobile ou la version ordinateur de bureau/portable ? Pourquoi ?
  * Le responsive design est une méthode de conception web permettant aux pages d'adapter automatiquement leur mise en page aux mobiles (s'adapte à n'importe quel écran).
    * Il est préférable de développer la version mobile en premier car :
      1. Indexation Mobile-First de Google.
      2. Meilleures performances.
      3. L'appareil le plus utilisé est le mobile (priorité).
      4. Plus facile à adapter ensuite pour des écrans plus grands.


6. Comment lie-t-on d'autres fichiers à un fichier HTML ?
  * Nous lions d'autres fichiers à un document HTML pour étendre ses fonctionnalités, styliser son apparence et permettre la navigation entre plusieurs pages.
  Par exemple :
   * Lier un fichier CSS dans la balise `<head>` : `<link rel="stylesheet" href="styles.css">`
   * Lier un fichier JS dans `<head>` ou tout en bas de `<body>` : `<script src="/filename.js"></script>`


7. Que signifie WCAG et pourquoi l'accessibilité est-elle importante ?
  * WCAG signifie Web Content Accessibility Guidelines (Règles pour l'accessibilité des contenus Web).
    * Pourquoi l'accessibilité est importante :
      1. Égalité d'accès et droits fondamentaux.
      2. Meilleure convivialité (ergonomie) et SEO.
      L'accessibilité aide les personnes âgées dont les capacités évoluent, les personnes souffrant de blessures temporaires (comme un bras cassé), ainsi que les utilisateurs confrontés à des contraintes situationnelles (comme une forte luminosité extérieure).


8. Que faut-il faire pour être positionné sur les premières pages des moteurs de recherche ?
  * Pour se positionner sur la première page des résultats des moteurs de recherche (comme Google), vous devez optimiser votre site web sur trois domaines fondamentaux : le SEO on-page, le SEO technique et le SEO off-page.


9. Quels sont les rôles du Product Owner, du Scrum Master et de l'équipe ?
  * Product Owner (PO) :
    * Maximiser la valeur du produit résultant du travail de l'équipe Scrum.
      1. Agit comme le lien entre le client et l'équipe.
      2. Définit et communique la vision ainsi que la feuille de route (roadmap) du produit.
      3. Décide des dates de livraison et accepte ou rejette les incréments de travail terminés.


* Scrum Master (SM) :
  * Le « Comment » et le processus (coaching Agile et facilitation).
    1. Facilite et anime les événements clés de Scrum (Sprint Planning, Daily Standups, Reviews et Rétrospectives).
    2. Supprime les obstacles qui ralentissent la progression de l'équipe.
    3. Coache l'équipe et la protège des perturbations externes.


* Équipe (développeurs) :
  * L'équipe est responsable du développement de l'application web.
    1. Estime la charge de travail et respecte les délais.
    2. Construit l'incrément : conçoit, code, teste et livre un incrément de produit à chaque sprint.
    3. Collabore : s'entraide et partage ses compétences au sein du groupe.


10. Que se passe-t-il à chaque fin de sprint ?
  * À la fin de chaque sprint, deux réunions obligatoires doivent être organisées pour clôturer les événements afin d'inspecter le travail accompli et d'améliorer le processus (la Sprint Review et la Sprint Retrospective).
