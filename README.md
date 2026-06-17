# TaskMate - Application de Gestion de Tâches
## Description Générale
TaskMate est une application Android conçue pour faciliter la gestion de projets et de tâches. Elle vise à résoudre les problèmes de coordination et de communication au sein des équipes en offrant une plateforme centralisée pour créer, assigner et suivre les tâches. Avec TaskMate, les utilisateurs peuvent gérer leurs projets de manière efficace, améliorer la productivité et renforcer la collaboration.

## Fonctionnalités Principales
- **Création de Projets** : Les utilisateurs peuvent créer de nouveaux projets en spécifiant le titre, la description et en sélectionnant les membres de l'équipe à impliquer.
- **Gestion de Tâches** : Pour chaque projet, les utilisateurs peuvent créer des tâches spécifiques, les assigner à des membres de l'équipe et suivre leur progression.
- **Sélection et Assignation d'Utilisateurs** : L'application permet de sélectionner des utilisateurs pour les projets et les tâches, facilitant ainsi la collaboration et la communication.
- **Envoi d'Emails** : Lorsqu'un utilisateur est ajouté à un projet, l'application envoie automatiquement un email pour le notifier, assurant que tous les membres de l'équipe soient informés.
- **Intégration avec Firebase** : TaskMate utilise Firebase pour la gestion des utilisateurs, le stockage des données et l'analyse, offrant ainsi une infrastructure robuste et scalable.

## Technologies Utilisées
- **Kotlin** : L'application est développée en Kotlin, profitant ainsi de la concision et de la sécurité de ce langage.
- **Gradle Kotlin DSL** : La configuration du projet est gérée à l'aide de Gradle Kotlin DSL, offrant une syntaxe plus concise et lisible.
- **Firebase** : L'application utilise Firebase pour l'authentification des utilisateurs, le stockage des données (Firebase Firestore) et l'analyse.

## Guide d'Installation Rapide
1. **Cloner le Dépôt** : Clonez le dépôt Git de TaskMate sur votre machine locale.
2. **Configurer Firebase** : Téléchargez le fichier `google-services.json` de votre projet Firebase et placez-le dans le dossier `app` de votre projet.
3. **Exécuter Gradle** : Exécutez la commande `./gradlew build` pour compiler et construire le projet.
4. **Lancer l'Application** : Déployez et lancez l'application sur un appareil Android ou un émulateur pour commencer à utiliser TaskMate.