# 📊 MyDashboard — Vue.js 3

## 🧩 Description du projet

**MyDashboard** est une application web monopage développée avec **Vue.js 3**.  
Elle permet à un utilisateur de créer un **tableau de bord personnel interactif** comprenant :

- un profil utilisateur
- une liste d’activités
- des statistiques en temps réel
- une persistance des données via `localStorage`

Ce projet est conçu comme un **TP pédagogique pour le Jour 1** du module Vue.js.

---

## 🎯 Objectifs pédagogiques

À la fin de ce projet, l’étudiant doit être capable de :

- Comprendre le fonctionnement de Vue.js 3
- Manipuler des données réactives (`ref`, `computed`, `watch`)
- Utiliser la syntaxe de template Vue (`v-model`, `v-if`, `v-for`)
- Créer une interface interactive sans manipulation directe du DOM
- Sauvegarder et restaurer des données avec `localStorage`

---

## 🛠️ Technologies utilisées

- **Vue.js 3**
- **Composition API**
- **Vite**
- **TypeScript**
- **HTML / CSS**
- **localStorage (navigateur)**

> ❌ Aucun backend  
> ❌ Aucun router  
> ❌ Aucun store global (Pinia)

---

## 📁 Structure du projet

```txt
my-dashboard/
├── public/
├── src/
│   ├── assets/
│   │   └── main.css        # Style dark minimal
│   ├── App.vue             # Composant principal
│   ├── main.ts             # Point d’entrée Vue
│   └── types.ts            # Types TypeScript (Activity, Category)
├── index.html
├── package.json
└── vite.config.ts
