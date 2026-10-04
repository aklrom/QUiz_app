# 🎯 Application de Quiz Interactif (SEA)

Une application web dynamique de quiz permettant de tester ses connaissances avec un système de score, un classement des meilleurs joueurs et des jokers pour aider l'utilisateur.

---

## 🛠️️ Technologies Utilisées

* **HTML5** : Structure de l'interface utilisateur
* **CSS3** : Design responsive et animations
* **JavaScript (ES6+)** : Logique du jeu, gestion du score, jokers et classement
* **JSON** : Stockage et structuration de la base de questions (`questions.json`)

---

## ✨ Fonctionnalités Principales

* **Système de Score & Points :** Calcul en temps réel des points accumulés au fil des bonnes réponses.
* **Jokers d'Aide :** Possibilité d'utiliser des jokers pour faciliter la résolution des questions difficiles.
* **Classement (Leaderboard) :** Affichage des meilleurs scores pour challenger les utilisateurs.
* **Chargement Dynamique :** Lecture des questions depuis un fichier local `questions.json`.

---

## 📂 Structure du Dépôt

```text
.
├── index.html        # Structure principale du jeu
├── index.css         # Styles et mise en page
├── index.js          # Logique JS (score, jokers, classement, événements)
└── questions.json    # Banques de données des questions et réponses

```

---

## 🚀 Lancer le Projet

1. **Cloner le dépôt :**
```bash
git clone [https://github.com/aklrom/SEA.git](https://github.com/aklrom/SEA.git)
cd SEA

```


2. **Ouvrir le projet :**
Ouvrez le fichier `index.html` directement dans votre navigateur, ou utilisez l'extension **Live Server** sur Visual Studio Code (recommandé pour le chargement fluide du fichier JSON).

---

## 📝 Apprentissages & Notions Abordées

* Manipulation asynchrone pour charger des données externes (`fetch` / JSON)
* Manipulation dynamique du DOM en JavaScript
* Gestion de l'état du jeu (score, jokers restants, index de la question)
* Stockage et affichage de données structurées (classement)

```

```
