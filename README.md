# 🍳 KitchenOS

> **Reprenez le contrôle de votre cuisine.**
> Un assistant culinaire open source, gratuit, sans installation et respectueux de votre vie privée.

![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-stable-blue)
![Size](https://img.shields.io/badge/size-lightweight-orange)

## 📖 À propos

**KitchenOS** n'est pas une énième application de cuisine remplie de publicités, de trackers ou nécessitant un abonnement mensuel. C'est un outil minimaliste et puissant conçu pour tourner directement dans votre navigateur.

L'objectif est simple : fournir un système d'exploitation pour votre nutrition (Recettes, Planning, Courses, Outils) sans dépendre d'un serveur distant.

### ⚡ Pourquoi KitchenOS ?

*   **0% Cloud, 100% Local** : Vos données (recettes, planning) sont stockées dans le `localStorage` de votre navigateur. Rien ne sort de votre appareil.
*   **Zéro Installation** : Pas de `npm install`, pas de compilation complexe. Un simple fichier HTML suffit.
*   **Portable** : Mettez le fichier sur une clé USB, hébergez-le sur GitHub Pages ou gardez-le en local. Il fonctionnera toujours.

## ✨ Fonctionnalités

### 1. 🍲 Gestionnaire de Recettes
*   Créez, éditez et supprimez vos propres recettes.
*   Calcul automatique des temps de préparation et cuisson.
*   Moteur de recherche instantané.
*   *Livré avec 10 recettes de base pour démarrer.*

### 2. 📅 Planning Tactique (15 Jours)
*   Vue glissante sur 2 semaines.
*   Assignation rapide des recettes aux jours de la semaine.
*   Distinction visuelle des week-ends.

### 3. 🛒 Liste de Courses Intelligente
*   **Génération automatique** : Transforme votre planning en liste d'ingrédients en un clic.
*   **Mode Course** : Cochez les articles au supermarché (les articles cochés se grisent).
*   **Nettoyage** : Supprimez les articles achetés en une seule action.

### 4. 🧰 La Boîte à Outils du Chef
*   **Minuteur Persistant** : Continue de tourner même si vous changez d'onglet dans l'application.
*   **Convertisseur Air Fryer** : Adaptez n'importe quelle recette de four traditionnel pour votre Air Fryer (algo : -20°C / temps x0.8).
*   **SOS Substitutions** : Trouvez instantanément par quoi remplacer un ingrédient manquant (ex: "Plus d'œufs ? Utilisez une banane").

## 🚀 Comment l'utiliser ?

### Méthode 1 : Utilisation directe (Recommandée)
1. Téléchargez le fichier `kitchenosapp.html`.
2. Ouvrez-le avec n'importe quel navigateur web moderne (Chrome, Firefox, Safari, Edge).
3. C'est tout. L'application est prête.

### Méthode 2 : Hébergement Statique
Vous pouvez héberger ce projet gratuitement sur GitHub Pages, Vercel ou Netlify.
1. Clonez ce dépôt.
2. Activez GitHub Pages dans les paramètres du dépôt.
3. Pointez la source sur la racine (`/`).

## 🛠️ Stack Technique

KitchenOS prouve qu'on n'a pas besoin d'une usine à gaz pour faire une application moderne.

*   **Core** : HTML5
*   **Logic** : React 18 & ReactDOM (via CDN)
*   **Transpiler** : Babel Standalone (pour le JSX in-browser)
*   **Styling** : Tailwind CSS (via CDN)
*   **Icons** : SVG natifs (pas de librairie lourde)

## 📂 Structure du Projet

```text
/
├── index.html              # Landing page (Présentation du produit)
├── kitchenosapp.html       # L'APPLICATION (Le cœur du système)
├── tutoriel_kitchenso.html # Documentation utilisateur
└── README.md               # Ce fichier
```

## 🤝 Contribuer

Les contributions sont les bienvenues ! Si vous voulez ajouter une fonctionnalité ou corriger un bug :

1. Forkez le projet.
2. Créez votre branche (`git checkout -b feature/AmazingFeature`).
3. Committez vos changements (`git commit -m 'Add some AmazingFeature'`).
4. Push vers la branche (`git push origin feature/AmazingFeature`).
5. Ouvrez une Pull Request.

**Idées d'améliorations :**
*   Export/Import des données (JSON) pour sauvegarder ses recettes.
*   Mode sombre (Dark Mode).
*   Calculateur de portions.

## 📄 Licence

Distribué sous la licence MIT. Voir `LICENSE` pour plus d'informations.

> "La cuisine est le seul endroit où la rébellion se mange."

---
*Fait avec ❤️ et du code propre.*
