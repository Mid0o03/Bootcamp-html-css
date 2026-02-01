# News Clone - Site d'Actualités

Ce projet est une reproduction de la page d'accueil d'un site d'actualités modern. Il met l'accent sur la mise en page structurée grâce à **CSS Grid** et l'utilisation de variables CSS pour un code maintenable.

![Aperçu du projet](./images/preview.png)
> *Note : Ajoutez une capture d'écran du résultat final ici nommée `preview.png` dans le dossier `images`.*

## 📰 Fonctionnalités & Design

Le design reprend les codes des sites de presse en ligne :

- **Mise en page Grid complexe** : Une structure asymétrique avec une "Main Story" proéminente, une barre latérale ("Trending") et des cartes en bas de page.
- **Header "Sticky"** : La navigation reste accessible lors du scroll.
- **Typographie & Couleurs** : Utilisation d'une palette sobre (Gris/Blanc) rehaussée par un rouge vif (`#ea0808`) pour les appels à l'action et les tags.
- **Effets visuels** :
  - Survol élégant sur les cartes (translation verticale).
  - Dégradé sombre sur l'image principale pour garantir la lisibilité du titre.

## 🛠 Techniques Utilisées

- **CSS Grid** : Pour la structure globale de la page (Template Areas).
- **Flexbox** : Pour les alignements internes (Navigation, Cartes).
- **CSS Variables** : Pour une gestion centralisée des couleurs (`--primary-red`, `--dark-bg`, etc.).
- **Responsive** : Design fluide s'adaptant à la largeur.

## 🚀 Structure du Projet

```bash
/04-news-clone
  ├── index.html      # Structure sémantique
  ├── style.css       # Styles (Grid, Flexbox, Variables)
  ├── images/         # Assets graphiques
  └── README.md       # Documentation
```

## 📝 Auteur

Projet réalisé dans le cadre du Bootcamp Front-End.
