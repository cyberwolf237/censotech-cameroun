# CensoTech Cameroun 🇨🇲
### Application de recensement intelligent des ressources éducatives
**TP INF232 — Collecte et analyse descriptive des données**

---

## 🚀 Guide de déploiement sur Vercel (GRATUIT — 5 minutes)

### ÉTAPE 1 — Créer un compte GitHub (si tu n'en as pas)
1. Va sur https://github.com
2. Clique **Sign up** → entre ton email, un mot de passe, un pseudo
3. Valide ton email

---

### ÉTAPE 2 — Créer un nouveau dépôt sur GitHub
1. Une fois connecté sur GitHub, clique sur **"New"** (bouton vert en haut à gauche)
2. Dans **"Repository name"** tape : `censotech-cameroun`
3. Laisse tout le reste par défaut
4. Clique **"Create repository"**

---

### ÉTAPE 3 — Mettre les fichiers sur GitHub
Tu as 2 options :

#### Option A — Interface web (le plus simple, pas besoin d'installer Git)
1. Dans ton dépôt vide, clique **"uploading an existing file"**
2. Glisse-dépose les 3 fichiers : `index.html`, `vercel.json`, `README.md`
3. En bas clique **"Commit changes"**

#### Option B — Via Git (terminal)
```bash
# Dans le dossier du projet :
git init
git add .
git commit -m "CensoTech Cameroun - INF232 TP"
git branch -M main
git remote add origin https://github.com/TON-PSEUDO/censotech-cameroun.git
git push -u origin main
```

---

### ÉTAPE 4 — Déployer sur Vercel
1. Va sur https://vercel.com
2. Clique **"Sign Up"** → choisit **"Continue with GitHub"** (important !)
3. Autorise Vercel à accéder à ton GitHub
4. Dans le dashboard Vercel, clique **"Add New..." → "Project"**
5. Tu vois ton dépôt `censotech-cameroun` → clique **"Import"**
6. Vercel détecte tout automatiquement grâce au `vercel.json`
7. Clique **"Deploy"** → attends 1-2 minutes
8. 🎉 TON LIEN : `https://censotech-cameroun.vercel.app`

---

## ✉️ Email à envoyer au professeur

**À :** rollinfrancis28@gmail.com  
**Objet :** INF232 — TP Application de collecte de données en ligne

```
Monsieur le Professeur,

Veuillez trouver ci-dessous le lien de mon application de collecte
et d'analyse descriptive des données, développée dans le cadre du TP INF232 :

🔗 https://censotech-cameroun.vercel.app

Application : CensoTech Cameroun
Secteur : Recensement des ressources éducatives nationales

Fonctionnalités :
- Formulaire de collecte de données (12 champs par fiche)
- Statistiques descriptives automatiques (moyennes, ratios, pourcentages)
- Visualisation graphique par région et par type d'établissement
- Tableau de bord interactif avec indicateurs en temps réel
- Export des données en CSV et JSON
- Données persistantes (localStorage)

Cordialement,
[Votre nom]
```

---

## 📋 Fonctionnalités de l'application

| Module | Description |
|--------|-------------|
| Tableau de bord | KPIs nationaux + graphiques en barres |
| Collecte | Formulaire de 12 champs par établissement |
| Statistiques | Graphiques Chart.js + analyse descriptive |
| Régions | Vue par région avec indicateurs de couverture |
| Données | Tableau complet de toutes les fiches |
| Export | CSV, JSON, impression |

---

## 🛠️ Technologies utilisées
- **HTML5 / CSS3 / JavaScript** (vanilla — aucun framework à installer)
- **Chart.js** (graphiques interactifs)
- **Google Fonts** (DM Sans)
- **localStorage** (persistance des données sans serveur)
- **Vercel** (hébergement statique gratuit)

---

*INF232 — Université de Yaoundé — 2025*
