# 🌍 GéoQuiz — Capitales du monde

Quiz interactif pour réviser les capitales des pays du monde, avec des funfacts après chaque question.

## Démo

Accessible via GitHub Pages à l'URL de votre repo.

## Fonctionnalités

- **2 modes** : Pays → Capitale ou Capitale → Pays
- **15 questions** tirées aléatoirement parmi 46 pays
- **Funfact** affiché après chaque réponse
- **3 palettes** :
  - 🍷 **Chrome détecté** → palette bordeaux/marron automatique
  - ☀️ **Thème clair** (défaut sur les autres navigateurs)
  - 🌙 **Thème bleu nuit** (bascule avec le bouton en haut à droite)

## Structure

```
├── index.html                  # Application quiz
└── pays_capitales_funfacts.csv # Données (46 pays, capitales, funfacts)
```

## Déploiement GitHub Pages

1. Pushez les deux fichiers à la racine du repo
2. Settings → Pages → Source : **main branch / root**
3. Le site est disponible sur `https://<user>.github.io/<repo>`

## Données

Le CSV contient pour chaque pays : nom, capitale administrative, et un funfact.