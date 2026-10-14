# 🎓 Cahier Numérique Interactif & Résilient — ACHIM

> *« L'éducation numérique accessible, frugale et sans barrière, pensée par un parent pour l'esprit de l'enfant. »*

[![Licence: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PWA](https://img.shields.io/badge/PWA-offline--first-5A0FC8)](https://web.dev/progressive-web-apps/)
[![Langue](https://img.shields.io/badge/langue-FR%20%2F%20Krey%C3%B2l-blue)]()

### 🌐 Application en ligne

👉 **[https://academieachim-cloud.github.io/cahier-achim/](https://academieachim-cloud.github.io/cahier-achim/)**

---

## 📖 Sommaire

- [1. L'accroche personnelle & pédagogique](#1-laccroche-personnelle--pédagogique--pourquoi-ce-projet-est-né)
- [2. Le constat de terrain](#2-le-constat-de-terrain--les-3-verrous-levés-par-lapplication)
- [3. Les fonctionnalités](#3-les-fonctionnalités-au-service-de-la-psychologie-de-lapprentissage)
- [4. Les avantages ciblés](#4-les-avantages-ciblés-selon-lauditoire)
- [5. Conclusion](#5-conclusion)
- [🚀 Installation & utilisation](#-installation--utilisation)
- [🛠️ Technologies](#️-technologies)
- [📄 Licence](#-licence)

---

## 1. L'accroche personnelle & pédagogique : pourquoi ce projet est né

Comme tout parent, je veux le meilleur pour l'éducation de mon fils. Mais en tant que développeur et acteur éducatif, j'ai rapidement fait face à une double réalité, vécue avec acuité dans notre contexte haïtien : **imprimer des cahiers d'exercices en couleur coûte une fortune, et le papier est à usage unique** (une fois rempli, il est consommé).

Pour concevoir un outil réellement adapté à son cerveau et à ses besoins d'apprentissage au CP, je ne me suis pas contenté de coder : **je me suis formé en validant un parcours en Psychologie de l'Apprentissage**. Ce double regard – technique et pédagogique – m'a permis de créer une application qui :

- 🧠 Respecte le rythme de l'enfant
- 🌱 Favorise son autonomie
- 💪 Dédramatise l'erreur
- 💰 Soulage le portefeuille des parents

---

## 2. Le constat de terrain : les 3 verrous levés par l'application

### 💸 Le coût de l'encre et du papier

Éviter les dépenses répétées en impressions couleur et en cahiers jetables. **Le droit à l'erreur redevient gratuit** : on efface, on recommence sans gâcher.

### 🖥️ La contrainte d'infrastructure (pas besoin de TNI)

Dans beaucoup d'écoles, s'équiper d'un Tableau Numérique Interactif (TNI) ou de projecteurs tactiles est hors de budget ou rendu impossible par l'instabilité électrique. **Notre solution s'adapte au matériel existant** :

- Un simple ordinateur portable branché sur un téléviseur standard
- Une tablette
- Le téléphone des parents à la maison

### 📡 L'instabilité du réseau

L'application est conçue en **100 % hors-ligne (PWA)**. Elle fonctionne sans Internet, s'affranchissant totalement des coupures de réseau.

---

## 3. Les fonctionnalités au service de la Psychologie de l'Apprentissage

### 📥 L'import universel

Glissez un PDF ou prenez simplement en photo une feuille d'exercice avec un smartphone pour la transformer instantanément en support interactif.

### 🗣️ L'accessibilité audio (Synthèse Vocale)

Fondée sur le besoin d'autonomie cognitive de l'enfant, cette fonction lui permet de cliquer sur n'importe quelle consigne textuelle pour l'**écouter lue à haute voix**. Idéal pour l'apprentissage de la lecture et le bilinguisme **Français / Kreyòl**.

### ✂️ L'atelier collage et les outils géométriques

Un espace ludique pour stimuler la créativité, manipuler des formes et intégrer les mathématiques par le jeu.

### 📊 Le suivi pédagogique bienveillant

L'application analyse l'activité pour offrir un **retour constructif** et génère un bilan simple exportable en PDF pour les parents ou l'enseignant.

---

## 4. Les avantages ciblés selon l'auditoire

| Auditoire | Bénéfice clé |
|---|---|
| **Parents** | Un soulagement budgétaire direct et l'accompagnement intelligent d'un parent formé aux mécanismes de l'apprentissage. |
| **Écoles** (même sans TNI) | Une conception rigoureuse pensée par quelqu'un qui maîtrise la psychologie de l'enfant, utilisable sur écran standard ou tablette. |
| **Partenaires** | Une innovation frugale alliant rigueur pédagogique, inclusion numérique, écologie et équité sociale. |

---

## 5. Conclusion

> *« L'éducation de nos enfants ne devrait jamais dépendre du prix de l'encre ou de la présence d'un tableau tactile à 3 000 dollars. En combinant la technologie et une vraie compréhension de la psychologie de l'apprentissage, nous prouvons que le numérique éducatif peut enfin être intelligent, accessible et appartenir à tout le monde. »*

---

## 🚀 Installation & utilisation

### Accès direct (GitHub Pages)

👉 **[https://academieachim-cloud.github.io/cahier-achim/](https://academieachim-cloud.github.io/cahier-achim/)**

### Installation comme application (PWA)

**Sur Android (Chrome)** :
1. Ouvre le lien
2. Menu ⋮ → **Installer l'application**

**Sur iPhone (Safari)** :
1. Ouvre le lien
2. Bouton Partager → **Sur l'écran d'accueil**

**Sur ordinateur (Chrome / Edge)** :
1. Ouvre le lien
2. Icône d'installation dans la barre d'adresse

### Utilisation en 5 étapes

1. 📄 **Charge un document** : PDF, image, photo ou lien web
2. ✏️ **Écris, dessine, annote** avec les outils (stylo, formes, gomme…)
3. 🗣️ **Active le mode lecture** pour écouter les consignes à voix haute
4. ✂️ **Colle des images** dans l'atelier collage
5. 📤 **Exporte en PDF** ou **envoie à l'école** en un clic

---

## 🛠️ Technologies

| Composant | Technologie |
|---|---|
| **Frontend** | HTML, CSS, JavaScript (vanilla) |
| **Rendu PDF** | [PDF.js](https://mozilla.github.io/pdf.js/) |
| **Export PDF** | [jsPDF](https://github.com/parallax/jsPDF) |
| **PWA** | Service Worker + Web App Manifest |
| **Stockage local** | IndexedDB + localStorage |
| **Hébergement** | GitHub Pages |
| **Envoi email** | EmailJS *(en cours de configuration)* |

---

## ✨ Fonctionnalités principales

- 📄 Import PDF, images, photos, liens web
- ✏️ 16 outils de dessin (stylo, surligneur, formes géométriques, gomme…)
- 🗣️ Synthèse vocale des consignes (français)
- ✂️ Atelier collage avec découpage d'images
- 📐 Règle, rapporteur, minuteur intégrés
- 📚 Bibliothèque de ressources
- 📊 Fiche de suivi pédagogique automatique
- 💾 Sauvegarde automatique (IndexedDB)
- 📤 Export PDF avec en-tête ACHIM
- 🌙 Thème clair / sombre automatique
- 📱 Installation PWA (fonctionne hors-ligne)

---

## 📄 Licence

Ce projet est sous licence [MIT](LICENSE) — libre d'utilisation, modification et distribution.

---

## 📧 Contact

**École ACHIM** — Année scolaire 2025-2026
📧 academie.achim@gmail.com

---

*Fait avec ❤️ pour l'éducation accessible.*
