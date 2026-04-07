# 🎵 Lyrics & Learn

Outil didactique de traduction de chansons anglophones — phrase par phrase.

**Stack 100% gratuite :**
- 🎤 Paroles : [lyrics.ovh](https://api.lyrics.ovh) — API publique, sans clé
- 🤖 Traduction & analyse : [Gemini 2.0 Flash](https://aistudio.google.com) — free tier généreux (Google AI Studio)

## 🚀 Déploiement

### 1. Push sur GitHub

```bash
git init
git add .
git commit -m "init"
git remote add origin https://github.com/TON-USERNAME/lyrics-learn.git
git push -u origin main
```

### 2. Déployer sur Vercel

- [vercel.com](https://vercel.com) → **Add New Project** → importe le repo
- Aucune variable d'environnement à configurer
- **Deploy** — en ligne en 30 secondes ✅

## 🔑 Clé API Gemini (gratuite)

1. Va sur [aistudio.google.com/app/apikey](https://aistudio.google.com/app/apikey)
2. Crée une clé gratuite (pas de CB requise)
3. Saisis-la dans l'interface au premier lancement
4. Elle est stockée dans ton `localStorage` — jamais envoyée ailleurs

## ✨ Fonctionnalités

- Saisie par titre, artiste, ou les deux
- Paroles réelles récupérées automatiquement
- Traduction ligne par ligne (mode didactique)
- Notes sur l'argot, figures de style et références culturelles
- Contexte historique et musical
- 5 anecdotes par chanson
- Mode "tout afficher"
- Interface sombre, responsive mobile

## 📁 Structure

```
lyrics-learn/
├── index.html    # App complète — zéro dépendance, zéro build
├── vercel.json   # Config Vercel
└── README.md
```
