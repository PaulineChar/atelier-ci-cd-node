# 🧪 Atelier CI/CD – Construire son premier pipeline

Un petit projet pour mettre en place une intégration continue simple avec GitHub Actions ou GitLab CI/CD.

## 🕒 Durée estimée : 60 min  
## 👥 Mode : individuel ou binôme  
## 🧰 Prérequis : compte GitHub ou GitLab, Node.js installé (si local)

---

## Comandes utiles

### 📦 Installation

```bash
npm ci
```

### 🚀 Lancer le lint

```bash
npm run lint
```

### ✅ Lancer les tests

```bash
npm test
```

---

## 🎯 Objectif
Mettre en place une CI/CD simple sur un projet fourni en Node.js ou React :

- ✅ Installer les dépendances
- 🔬 Lancer les tests
- 🎯 Vérifier le linting
- 🌟 (bonus) Ajouter un badge de statut ou une notification Slack

## 📄 Étape 1 : Créer le fichier de pipeline
### GitHub → `.github/workflows/ci.yml`
### GitLab → `.gitlab-ci.yml`

## 📛 Étape 2 : Vérifier que le pipeline se déclenche lors d'un événement pertinent

## 🌟 Bonus – Challenge complémentaire

- 🔰 Ajouter un **badge de statut** dans le README
- 📣 Ajouter une **notification Slack (ou autre)** (GitHub : via webhook, GitLab : via intégration)

---

## 📋 Validation

✅ Si le pipeline s’exécute et affiche toutes les étapes comme “passed” : mission réussie !  
🌟 Si un badge ou une notif est en place : bonus 🌈
