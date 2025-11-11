# Stop Watch ⏱️

Un chronomètre moderne et élégant avec une interface intuitive et design professionnel.

## 🌐 Voir le projet en direct

**[Cliquez ici pour voir le projet en live](https://maxroe66.github.io/stop-watch/)**

## ✨ Fonctionnalités

- ✅ Démarrer le chronomètre
- ✅ Arrêter le chronomètre
- ✅ Réinitialiser le chronomètre
- ✅ Affichage en format MM:SS
- ✅ Interface responsive et moderne
- ✅ Animations fluides
- ✅ Design professionnel avec dégradés
- ✅ Boutons colorés avec effects au hover

## 🛠️ Technologies utilisées

- **HTML5** - Structure
- **CSS3** - Styling avec animations, gradients et glassmorphism
- **JavaScript (Vanilla)** - Logique du chronomètre

## 📂 Structure du projet

```
stop-watch/
├── index.html       # Structure HTML
├── styles.css       # Styles et animations
├── script.js        # Logique JavaScript
└── README.md        # Documentation
```

## 🎨 Caractéristiques du design

- Dégradé violet élégant en arrière-plan
- Affichage du temps avec effet glassmorphism (fond semi-transparent avec flou)
- **Boutons stylisés** avec dégradés de couleur :
  - **Start** : Vert (démarrer)
  - **Stop** : Rouge/Orange (arrêter)
  - **Reset** : Noir (réinitialiser)
- Animations au survol des boutons
- Design responsive (mobile, tablette, desktop)
- Typography élégante avec monospace pour l'affichage du temps

## 🚀 Comment utiliser

1. Ouvrez [le site en live](https://maxroe66.github.io/stop-watch/)
2. Cliquez sur **"Start"** pour démarrer
3. Cliquez sur **"Stop"** pour arrêter
4. Cliquez sur **"Reset"** pour réinitialiser à 00:00

## 🧠 Concepts JavaScript couverts

- Variables et états
- Fonctions
- setInterval et clearInterval
- Calculs mathématiques (modulo, division)
- Formatage de nombre avec padStart
- DOM manipulation et événements
- Gestion du timing et des intervalles

## ⚙️ Comment ça marche

```javascript
// Le chronomètre incrémente chaque 100ms
setInterval(timer, 100);

// Conversion en minutes et secondes
const minutes = Math.floor(secondsElapsed / 60);
const seconds = secondsElapsed % 60;

// Affichage au format MM:SS
time.innerHTML = `${padStart(minutes)}:${padStart(seconds)}`;
```

## 📝 Détails techniques

- **Précision** : Mise à jour toutes les 100ms
- **Format d'affichage** : MM:SS (avec zéros à gauche)
- **Gestion d'état** : Variables `secondsElapsed` et `interval`
- **Contrôles** : Start/Stop/Reset

## 🎯 Prochaines améliorations possibles

- [ ] Affichage des centièmes de seconde (MM:SS:MS)
- [ ] Chrono avec tours (lap times)
- [ ] Sauvegarde des meilleurs temps
- [ ] Sonnerie/notification à la fin
- [ ] Partage des résultats
- [ ] Thème dark/light

---

**Auteur:** maxroe66  
**Date:** Novembre 2025
