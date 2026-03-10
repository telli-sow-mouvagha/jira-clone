# 🚀 Jira Clone

> **⚠️ Statut :** En cours de développement (Phase 1 : Architecture & Setup)

Un clone de l'application de gestion de projet Agile Jira, développé pour consolider les fondamentaux de l'architecture Front-End moderne et la gestion d'état. 

## 🛠️ Stack Technique

Ce projet s'appuie sur une stack moderne  :

* **Framework :** [Next.js 14](https://nextjs.org/) 
* **Langage :** [TypeScript](https://www.typescriptlang.org/) 
* **Runtime/Package Manager :** [Bun](https://bun.sh/) (choisi pour la rapidité d'exécution et d'installation) 
* **Styling :** [Tailwind CSS](https://tailwindcss.com/) 
* **UI Components :** [Shadcn UI](https://ui.shadcn.com/) (Composants "Headless" entièrement personnalisables)

## 🏗️ État Actuel du Projet

L'application est actuellement dans sa phase d'initialisation architecturale. Ce qui est déjà implémenté :

- **Initialisation de l'environnement :** Configuration stricte de Next.js 14 avec Bun en remplacement de Node/npm traditionnel.
- **Architecture "Feature-Based" :** Mise en place d'une structure de dossiers modulaire (séparation par domaines métiers) pour garantir la scalabilité.
- **Système de Design (UI) :** Intégration de TailwindCSS couplé à Shadcn UI. Des composants de base (comme les boutons personnalisés) ont été instanciés et testés pour valider le contrôle total sur le design system.

## 🎯 Prochains Objectifs

- Intégration de l'interface globale (Layouts, Sidebar, Navigation).
- Mise en place du routing système.
- Gestion des entités de base (Création, édition et suppression de tickets/tasks).
- Intégration d'une base de données backend (Backend-as-a-Service).

## 🚀 Lancer le projet en local

Si vous souhaitez faire tourner l'interface actuelle sur votre machine :

1. **Cloner le repository :**
   ```bash
   git clone https://github.com/VOTRE_NOM/jira-clone.git
   cd jira-clone
Installer les dépendances (via Bun ou Node) :
Lancer le serveur de développement :
Ouvrez http://localhost:3000 dans votre navigateur pour voir le résultat.
