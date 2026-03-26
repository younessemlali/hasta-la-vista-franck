# 🎉 Hasta La Vista, Franck!

Livre d'or interactif pour le départ de Franck — Randstad Solutions Clients.

## 🚀 Déploiement GitHub Pages

### Étapes

1. **Créer un dépôt GitHub** (public ou privé)
   - Aller sur [github.com/new](https://github.com/new)
   - Nom suggéré : `hasta-la-vista-franck`
   - Laisser vide (ne pas initialiser avec README)

2. **Uploader les fichiers**
   ```bash
   git init
   git add .
   git commit -m "🎉 Livre d'or Franck"
   git branch -M main
   git remote add origin https://github.com/TON_USERNAME/hasta-la-vista-franck.git
   git push -u origin main
   ```

3. **Activer GitHub Pages**
   - Aller dans Settings → Pages
   - Source : `Deploy from a branch`
   - Branch : `main` / `/ (root)`
   - Cliquer **Save**

4. **Accéder à l'app** (après ~1 minute)
   ```
   https://TON_USERNAME.github.io/hasta-la-vista-franck/
   ```

## 📁 Structure des fichiers

```
franck-app/
├── index.html        ← Application principale
├── slide-01.jpg      ← Diapos (01 à 69)
├── slide-02.jpg
├── ...
├── slide-69.jpg
└── README.md
```

## ✨ Fonctionnalités

- Navigation par boutons ← →
- Raccourcis clavier (flèches, Espace)
- Swipe tactile sur mobile
- Bande de miniatures cliquables
- Barre de progression
- Mode plein écran au clic
- Préchargement des slides adjacentes

---

*Fait avec ❤️ pour Franck*
