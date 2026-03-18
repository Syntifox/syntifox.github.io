# 🎓 Portfolio BTS SIO SISR

Portfolio professionnel pour l'épreuve BTS SIO option **SISR** (Solutions d'Infrastructure, Systèmes et Réseaux), hébergé gratuitement sur **GitHub Pages**.

---

## 🚀 Déploiement sur GitHub Pages (gratuit)

### Étape 1 — Créer un dépôt GitHub

1. Connectez-vous sur [github.com](https://github.com)
2. Cliquez sur **"New repository"** (bouton vert en haut à droite)
3. Nommez le dépôt : `votre-username.github.io` *(remplacez `votre-username` par votre nom d'utilisateur GitHub)*
4. Cochez **"Public"**
5. Cliquez **"Create repository"**

### Étape 2 — Uploader les fichiers

**Option A — Via l'interface web GitHub (plus simple) :**
1. Dans votre nouveau dépôt, cliquez **"uploading an existing file"**
2. Glissez-déposez tous les fichiers du portfolio
3. Cliquez **"Commit changes"**

**Option B — Via Git en ligne de commande :**
```bash
git clone https://github.com/votre-username/votre-username.github.io
cd votre-username.github.io
# Copiez tous les fichiers du portfolio ici
git add .
git commit -m "Initial portfolio commit"
git push origin main
```

### Étape 3 — Activer GitHub Pages

1. Dans votre dépôt, allez dans **Settings** → **Pages**
2. Source : **"Deploy from a branch"**
3. Branch : **main** → **/root** (root)
4. Cliquez **Save**

⏳ Attendez 1-2 minutes, puis votre site sera en ligne sur :
**`https://votre-username.github.io`**

---

## 📁 Structure du projet

```
portfolio/
├── index.html              # Page principale (accueil, projets, stages, veille, contact)
├── css/
│   └── style.css           # Feuille de style principale
├── js/
│   └── main.js             # Interactions et animations
├── assets/
│   ├── cv.pdf              # ⚠️ À AJOUTER : Votre CV en PDF
│   ├── rapport-stage-1.pdf # ⚠️ À AJOUTER : Rapport stage 1
│   └── rapport-stage-2.pdf # ⚠️ À AJOUTER : Rapport stage 2
├── projets/
│   ├── ad.html             # Fiche projet Active Directory
│   ├── pfsense.html        # Fiche projet pfSense
│   ├── proxmox.html        # Fiche projet Proxmox
│   ├── audit.html          # Fiche projet Audit sécurité
│   └── reseau.html         # Fiche projet Infrastructure réseau
├── fiches/
│   ├── fiche-ad.html       # Fiche activité E5 — AD
│   ├── fiche-pfsense.html  # Fiche activité E5 — pfSense
│   ├── fiche-proxmox.html  # Fiche activité E5 — Proxmox
│   ├── fiche-audit.html    # Fiche activité E5 — Audit
│   ├── fiche-reseau.html   # Fiche activité E5 — Réseau
│   └── fiche-zabbix.html   # Fiche activité E5 — Zabbix
├── veille/
│   ├── ransomware-2025.html
│   ├── kubernetes.html
│   └── wifi7.html
├── veille.html             # Page liste veille technologique
├── tableau-synthese.html   # Tableau synthèse E5 complet
└── README.md               # Ce fichier
```

---

## ✏️ Personnalisation — À faire OBLIGATOIREMENT

### 1. Informations personnelles dans `index.html`

Remplacez toutes les occurrences de :
- `[Prénom NOM]` → votre prénom et nom
- `PN` (initiales dans le logo) → vos initiales
- `[Nom du lycée]` → le nom de votre établissement
- `[Ville]` → votre ville
- `[filière]` → votre filière de bac
- `votre@email.fr` → votre adresse email
- `votre-profil` dans le lien LinkedIn
- `votre-github` dans le lien GitHub

### 2. Contenu à adapter

- **Projets** : Remplacez les 5 projets par vos vraies réalisations
- **Compétences** : Ajustez les niveaux (barres de progression)
- **Stages** : Mettez vos vrais employeurs, missions, durées
- **Veille** : Remplacez par vos vraies veilles technologiques
- **Tableau E5** : Listez vos vraies activités professionnelles

### 3. Fichiers à ajouter dans `assets/`

- `cv.pdf` — Votre CV au format PDF
- `rapport-stage-1.pdf` — Rapport de stage 1
- `rapport-stage-2.pdf` — Rapport de stage 2
- `photo.jpg` *(optionnel)* — Votre photo de profil

### 4. Créer les sous-pages

Pour chaque projet, créez un fichier dans `projets/` en partant du template ci-dessous :

```html
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <title>Projet : Active Directory — Portfolio BTS SIO SISR</title>
  <link rel="stylesheet" href="../css/style.css" />
</head>
<body>
  <!-- Contenu de la fiche projet -->
</body>
</html>
```

---

## 📋 Checklist avant l'épreuve E5

- [ ] Toutes les informations personnelles sont renseignées
- [ ] CV téléchargeable depuis la page d'accueil
- [ ] Au moins 5 fiches d'activités professionnelles complètes
- [ ] Tableau de synthèse E5 complet et à jour
- [ ] Au moins 3 articles de veille technologique
- [ ] Rapports de stage disponibles en téléchargement
- [ ] Site testé sur mobile, tablette et ordinateur
- [ ] Liens de navigation fonctionnels
- [ ] URL GitHub Pages fonctionnelle et partageable

---

## 🔗 URL de votre site

Une fois déployé : `https://votre-username.github.io`

---

## 🛠️ Technologies utilisées

- **HTML5** — Structure sémantique
- **CSS3** — Variables CSS, Grid, Flexbox, animations
- **JavaScript** — Vanilla JS (aucune dépendance externe)
- **Google Fonts** — DM Sans + DM Mono
- **GitHub Pages** — Hébergement gratuit

---

*Portfolio conçu pour le BTS SIO option SISR — Hébergement 100% gratuit via GitHub Pages*
