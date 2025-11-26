# 📦 Fichiers pour GitHub Pages

Ce dossier contient tous les fichiers nécessaires pour déployer l'application SaaS Pro sur GitHub Pages.

## 📁 Fichiers Inclus

| Fichier | Description |
|---------|-------------|
| `index.html` | Page de login (Username: dominator / Password: dominator123) |
| `dashboard.html` | Dashboard de gestion de produits |
| `settings.html` | Page de configuration TikTok API |
| `terms.html` | Conditions d'utilisation |
| `privacy.html` | Politique de confidentialité |
| `.nojekyll` | Désactive le traitement Jekyll de GitHub Pages |

## 🚀 Déploiement sur GitHub Pages

### Étape 1 : Créer le Repository

1. Aller sur : https://github.com/new
2. Nom : `saaspro--legal` (ou votre nom de repository)
3. Visibilité : **Public** (requis pour GitHub Pages gratuit)
4. Cliquer **"Create repository"**

### Étape 2 : Uploader les Fichiers

**Option A : Via l'Interface GitHub**

1. Aller sur votre repository : `https://github.com/sambickeita/saaspro--legal`
2. Cliquer **"Add file"** → **"Upload files"**
3. Glisser-déposer **TOUS** les fichiers de ce dossier :
   - `index.html`
   - `dashboard.html`
   - `settings.html`
   - `terms.html`
   - `privacy.html`
   - `.nojekyll`
4. Cliquer **"Commit changes"**

**Option B : Via Git (Recommandé)**

```bash
# Cloner le repository
git clone https://github.com/sambickeita/saaspro--legal.git
cd saaspro--legal

# Copier les fichiers
cp ../github-pages/* .

# Commit et push
git add .
git commit -m "Initial commit - SaaS Pro TikTok Integration"
git push origin main
```

### Étape 3 : Activer GitHub Pages

1. Aller dans **Settings** : `https://github.com/sambickeita/saaspro--legal/settings/pages`
2. **Source** : `Deploy from a branch`
3. **Branch** : `main` (ou `master`) / `root` (ou `/`)
4. Cliquer **"Save"**
5. Attendre 2-3 minutes

### Étape 4 : Vérifier

Votre site sera disponible sur :
```
https://sambickeita.github.io/saaspro--legal/
```

---

## ✅ Checklist de Déploiement

- [ ] Repository GitHub créé (public)
- [ ] Tous les fichiers HTML uploadés
- [ ] Fichier `.nojekyll` inclus
- [ ] GitHub Pages activé
- [ ] Site accessible sur l'URL GitHub Pages
- [ ] Test du login (dominator / dominator123)
- [ ] Test de l'ajout de produit
- [ ] Test de la configuration API

---

## 🔗 Configuration TikTok Developer Portal

Une fois le site déployé, configurer dans TikTok Developer Portal :

| Champ | URL |
|-------|-----|
| **Website URL** | `https://sambickeita.github.io/saaspro--legal/` |
| **Terms of Service** | `https://sambickeita.github.io/saaspro--legal/terms.html` |
| **Privacy Policy** | `https://sambickeita.github.io/saaspro--legal/privacy.html` |

---

## 🎬 Pour la Vidéo Démo

Utiliser l'URL GitHub Pages (pas localhost) :
```
https://sambickeita.github.io/saaspro--legal/
```

**Identifiants de connexion :**
- Username : `dominator`
- Password : `dominator123`

---

## 📝 Notes

- **Mode Client-Only** : Aucun backend requis
- **BYOK** : Les clés TikTok sont saisies par l'utilisateur
- **Stockage Local** : Produits et clés stockés dans le navigateur
- **Sécurité** : Clés effacées à la fermeture du navigateur

---

**Tous les fichiers sont prêts pour le déploiement ! 🚀**

