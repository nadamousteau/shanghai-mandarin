# 上海 · Mandarin App

Application PWA d'apprentissage du mandarin pour Shanghai.

## Installer sur GitHub Pages (5 minutes)

### Étape 1 — Créer le repo
1. Va sur [github.com](https://github.com) → connecte-toi ou crée un compte
2. Clique **New repository**
3. Nom : `shanghai-mandarin` (ou ce que tu veux)
4. Coche **Public**
5. Clique **Create repository**

### Étape 2 — Uploader les fichiers
1. Dans ton nouveau repo, clique **uploading an existing file**
2. Glisse-dépose les 5 fichiers : `index.html`, `manifest.json`, `sw.js`, `icon-192.svg`, `icon-512.svg`
3. Clique **Commit changes**

### Étape 3 — Activer GitHub Pages
1. Dans ton repo → **Settings** → **Pages** (menu gauche)
2. Source : **Deploy from a branch**
3. Branch : **main** → dossier **/ (root)**
4. Clique **Save**
5. Attends 1-2 minutes → ton URL apparaît : `https://TON-USERNAME.github.io/shanghai-mandarin/`

### Étape 4 — Installer sur ton téléphone
**Android (Chrome)** :
1. Ouvre l'URL dans Chrome
2. Menu ⋮ → "Ajouter à l'écran d'accueil"
3. L'app s'installe avec ton icône, s'ouvre en plein écran

**iPhone (Safari)** :
1. Ouvre l'URL dans Safari
2. Partager → "Sur l'écran d'accueil"

### Mettre à jour l'app
Quand je te fournis une nouvelle version :
1. Va dans ton repo GitHub
2. Clique sur `index.html` → icône crayon (éditer)
3. Remplace tout le contenu → **Commit changes**
4. GitHub Pages se met à jour automatiquement en ~1 minute

## Fonctionnalités v3
- SRS (répétition espacée) : chaque mot a son propre intervalle de révision
- 6 modes de jeu : flashcard, MCQ×3, saisie de traduction, reconnaissance vocale
- Countdown Shanghai avec mots/jour nécessaires
- 7 thèmes dont Vie Académique (maths, finance quant, IA)
- Audio intégré (synthèse vocale)
- Fonctionne hors-ligne (service worker)
- Progression sauvegardée localement
