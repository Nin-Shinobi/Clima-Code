# 🌦️ Clima‑Code

Des prévisions météo élégantes, rapides et simples à utiliser. ✨

<p align="center">
  <img alt="Clima-Code banner" src="https://img.shields.io/badge/Clima--Code-Weather%20App-00B6FF?style=for-the-badge&logo=icloud&logoColor=white" />
  <img alt="status" src="https://img.shields.io/badge/Status-Actif-success?style=for-the-badge" />
  <img alt="license" src="https://img.shields.io/badge/License-MIT-informational?style=for-the-badge" />
  <img alt="made with" src="https://img.shields.io/badge/Made%20with-HTML%2FCSS%2FJS-ff69b4?style=for-the-badge" />
</p>
<p align="center">
  <img alt="Aperçu de l'interface Clima‑Code" src="./Clima-code.png" width="900" />
</p>

---

## 📑 Sommaire
- 🚀 [Aperçu](#-aperçu)
- 🧩 [Fonctionnalités](#-fonctionnalités)
- 🗂️ [Structure du projet](#️-structure-du-projet)
- 🛠️ [Technologies](#️-technologies)
- ⚙️ [Installation](#️-installation)
- ▶️ [Utilisation](#️-utilisation)
- 🔧 [Configuration](#-configuration)
- 🧪 [Bonnes pratiques](#-bonnes-pratiques)
- 🤝 [Contribuer](#-contribuer)
- 🐛 [Signaler un bug](#-signaler-un-bug)
- 📜 [Licence](#-licence)

---

## 🚀 Aperçu
Clima‑Code est une application web front‑end qui permet de consulter la météo actuelle et/ou les prévisions d'une ville. Tout est en **HTML**, **CSS** et **JavaScript** vanilla pour un déploiement ultra‑simple (aucun backend requis).

> Astuce: Idéal pour un hébergement statique (GitHub Pages, Netlify, Vercel, etc.).

## 🧩 Fonctionnalités
- 🌍 Recherche météo par ville
- ⏱️ Affichage rapide et réactif
- 📱 Design responsive
- 🎨 Thème propre et lisible
- 🌡️ Détails essentiels (température, conditions, etc.)

## 🗂️ Structure du projet
```
Clima-Code/
  ├─ index.html     # Page principale
  ├─ style.css      # Styles de l’interface
  └─ main.js        # Logique de l’app (fetch, UI, événements)
```

## 🛠️ Technologies
- **HTML5**
- **CSS3** (Flexbox/Grid, responsive)
- **JavaScript** (ES6+)
- Optionnel: **API météo** (ex. OpenWeather) si vous avez ajouté une intégration

## ⚙️ Installation
Aucune installation compliquée. Deux options:

1) Ouvrir directement le fichier:
- Téléchargez le repo
- Ouvrez `index.html` dans votre navigateur

2) Utiliser un petit serveur local (recommandé):
- Via l’extension VS Code « Live Server »
- ou en CLI, par exemple:
```bash
# Node.js (http-server)
npx http-server -p 5173 .
# ou Python 3
python -m http.server 5173
```
Ensuite visitez `http://localhost:5173`.

## ▶️ Utilisation
- Saisissez une ville dans le champ de recherche (si présent)
- Validez pour afficher la météo
- Ajustez selon les options de l’interface

## 🔧 Configuration
Selon votre implémentation dans `main.js`:
- Renseignez votre clé d’API si le code le prévoit (ex: `const API_KEY = "..."`)
- Vérifiez l’URL de l’API et les unités (Celsius/Metric)
- Adaptez les sélecteurs DOM si vous modifiez la structure HTML

## 🧪 Bonnes pratiques
- Vérifiez les erreurs réseau (statuts HTTP, timeouts)
- Gérez les cas limites (ville introuvable, champs vides)
- Mettez en cache les dernières requêtes si nécessaire
- Respectez les quotas/limitations de l’API utilisée

## 🤝 Contribuer
Les contributions sont les bienvenues!
1. Forkez le repo
2. Créez une branche: `git checkout -b feat/ma-super-feature`
3. Commitez: `git commit -m "feat: ajoute ma super feature"`
4. Poussez: `git push origin feat/ma-super-feature`
5. Ouvrez une Pull Request ✨

## 🐛 Signaler un bug
- Ouvrez un ticket avec:
  - **Étapes de reproduction**
  - **Résultat attendu vs observé**
  - **Environnement** (OS, navigateur, versions)

## 🏷️ Tags
`#weather` `#javascript` `#frontend` `#vanillaJS` `#html` `#css` `#responsive` `#meteo` `#webapp`

## 📸 Captures (optionnel)
Ajoutez vos screenshots ou GIFs ici pour illustrer l’UI.

## 📜 Auteur
- **Auteur** : [𝕹𝖎𝖓_𝕾𝖍𝖎𝖓𝖔𝖇𝖎🥷🏾]
- **GitHub** : [@Nin-Shinobi](https://github.com/Nin-Shinobi)
- **Repository** : [Clima-Code](https://github.com/Nin-Shinobi/Clima-Code.git)
---

Fait avec ❤️ pour la météo.
