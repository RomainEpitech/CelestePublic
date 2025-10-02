# Changelog

Toutes les modifications notables de ce projet seront documentées dans ce fichier.

Le format est basé sur [Keep a Changelog](https://keepachangelog.com/fr/1.0.0/)
et ce projet adhère à [Semantic Versioning](https://semver.org/lang/fr/).

---

## [0.1.0] - 2025-07-31

### Ajouté

#### ⚙️ Backend & DevOps

- Initialisation du backend avec **Laravel**.
- Intégration de **MySQL** pour la base de données.
- Mise en place complète de l’environnement **Docker** avec configuration via `.env`.
- Fichiers de configuration :
  - `nginx.conf` pour le reverse proxy.
  - `Makefile` pour les tâches de build & déploiement.
  - Scripts `bin/` pour la sauvegarde, restauration et récupération en cas de désastre.
- Fichier `CONTRIBUTORS.md` pour le suivi des collaborateurs.
- Création de templates `.github/` pour :
  - Rapport de bugs (`bug_report.md`)
  - Feedback et suggestions (`gameplay_feedback.md`)

#### 🖥️ Frontend - Client Launcher React

- Initialisation du client avec **React** (JavaScript Ready).
- Intégration de :
  - `TailwindCSS` pour le design.
  - `react-router-dom` pour la navigation.
  - `i18next` + `react-i18next` pour la traduction multilingue.
  - `zustand` pour la gestion d'état.
  - `lucide-react` pour les icônes SVG dynamiques.
- Design du **formulaire de connexion** (Login).
- Support de la **localisation dynamique** (FR/EN).
- Détection automatique de langue utilisateur.

---

## [Unreleased]

- Authentification Laravel Sanctum.
- Système de création de personnage.
- Modélisation base de donnée classes.
- Intégration du moteur de jeu côté client.
- Système d'inventaire et base de données pour objets/artéfacts.
- Interface joueur (UI HUD) en cours de réflexion.