# LiCorneEvent

Site vitrine statique en HTML/CSS/JS pour une agence fictive de location de licornes magiques.

## Présentation

`index.html` présente un site une page (one-page) inspiré d'une agence événementielle féerique :
- Section HERO avec animation, titre, sous-titre et CTA
- Catalogue de licornes avec cartes produits et filtres visuels
- Sections Événements, Fonctionnement, Témoignages, Galerie, Tarifs, FAQ et Contact
- Footer avec liens et réseaux sociaux

## Points techniques

- Structure 100% statique dans un seul fichier `index.html`
- Styles intégrés dans une balise `<style>` pour un prototypage rapide
- JavaScript embarqué pour :
  - curseur personnalisé
  - accordéon FAQ interactif
  - gestion des boutons de filtre
  - animations d'apparition au scroll
  - effet de box-shadow du menu au scroll

## Design et UX

- Palette douce et pastel avec accents dorés et violets
- Typographie mixant `Playfair Display`, `Cormorant Garamond` et `DM Sans`
- Animations légères pour un rendu élégant et vivant
- Responsive design adapté aux tablettes et mobiles

## Contenu principal

- `#catalogue` : cartes de licornes avec nom, description, tags et prix
- `#events-wrapper` : cas d'usage (anniversaire, mariage, EVJF)
- `#how` : étapes de réservation en 4 phases
- `#temoignages` : avis clients fictifs
- `#galerie` : défilement en boucle d'éléments visuels
- `#tarifs` : 3 offres (Féerique, Enchantée, Royale)
- `#faq` : questions fréquentes avec accordéon
- `#contact` : formulaire de contact et informations de contact

## Déploiement

Ouvrez `index.html` dans un navigateur pour visualiser le site. Aucun serveur ou dépendance n'est nécessaire.

## Améliorations possibles

- Externaliser le CSS et le JS dans des fichiers séparés
- Ajouter un vrai formulaire fonctionnel avec envoi côté serveur
- Remplacer les icônes emoji par des images et illustrations personnalisées
- Ajouter des animations plus complexes et un préchargement
- Améliorer l'accessibilité (focus, labels explicitement liés, alt, etc.)
