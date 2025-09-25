# 🎴 ScoreKeeper

## 📱 But de l’application

ScoreKeeper est une application mobile **React Native + TypeScript** permettant de **compter les points** dans différents jeux de cartes traditionnels :

-   Tarot
-   Belote
-   Coinche

Elle ne remplace pas le jeu : son but est uniquement de **faciliter la gestion des scores**.

---

## ✨ Fonctionnalités prévues

-   Compter les points en fin de manche
-   Gérer la rotation du donneur (belote/coinche)
-   Calculer automatiquement les scores finaux selon les règles officielles
-   Gérer les contrats (coinche, surcoinche, tarot garde/garde sans/garde contre)
-   Suivre les annonces (belote/rebelote, carrés, etc.)
-   Historique des parties
-   Export/partage des scores

---

## 🎨 Style et accessibilité

-   L’interface est entièrement stylisée via un **système de thèmes** (`clair` et `sombre`).
-   Les couleurs et styles passent par un hook unique : `useTheme`.

---

## 🔮 Roadmap

-   [ ] MVP Tarot simple
-   [ ] Ajout Belote
-   [ ] Ajout Coinche
-   [ ] Gestion avancée des annonces et contrats
-   [ ] Historique + export CSV/PDF
