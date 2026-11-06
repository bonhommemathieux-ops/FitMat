# FitMat

PWA (Progressive Web App) de suivi sport personnel.

## Fonctionnalites

- Programme hebdo 7 seances configurable (S1 a S4 progression)
- Fiches techniques detaillees par exercice (position, mouvement, erreurs, securite)
- Timer integre pour les temps de repos et gainage
- Suivi poids + tour de taille avec graphique evolution
- Historique des seances + statistiques (total, serie, semaine courante)
- Profil utilisateur personnalisable (age, taille, pathologies)
- Stockage local uniquement (localStorage) - zero envoi de donnees

## Installation

### iPhone / iPad
1. Ouvre l'URL dans Safari
2. Bouton Partage > "Sur l'ecran d'accueil"
3. L'app apparait comme une vraie application

### Android
1. Ouvre l'URL dans Chrome
2. Menu > "Ajouter a l'ecran d'accueil"

## Technique

- Vanilla HTML/CSS/JS
- Service Worker pour fonctionnement offline
- localStorage pour la persistance
- GIFs d'exercices depuis Exercise Gym GIFs DB (via jsDelivr CDN)
- Images de secours depuis free-exercise-db (yuhonas)

