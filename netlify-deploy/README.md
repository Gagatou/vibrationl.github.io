# Vibration'L — Déploiement Netlify

## 📦 Contenu du dossier

- `index.html` — Le site complet, prêt à publier
- `vibration-l-logo.png` — Le logo (à ajouter manuellement)
- `README.md` — Ce fichier

## 🚀 Instructions de déploiement

### ÉTAPE 1 : Ajouter l'image du logo

1. Copie le fichier `vibration-l-logo.png` depuis `C:\Users\agathe.eydoux\VibrationL\`
2. Colle-le dans ce dossier `netlify-deploy\` (à côté du `index.html`)

### ÉTAPE 2 : Créer un compte Netlify

1. Va sur https://www.netlify.com
2. Clique **"Sign up"**
3. Crée un compte gratuit (avec Gmail ou GitHub)

### ÉTAPE 3 : Uploader le site

1. Dans Netlify, clique **"Add new project"** → **"Deploy manually"**
2. **Drag & drop le dossier `netlify-deploy` complet** (ou sélectionne les 2 fichiers)
3. Attend que Netlify finisse (2-3 secondes)
4. Tu auras une URL type : `https://[nom-aléatoire].netlify.app`

### ÉTAPE 4 : Rediriger depuis Wix (pour garder le SEO)

1. Va sur ton site Wix : https://vibrationl.wixsite.com/vibrationl
2. Ouvre **Paramètres** → **Domaine & publication**
3. Cherche **"Redirection 301"** ou **"URL Redirect"**
4. Crée une redirection de `https://vibrationl.wixsite.com/vibrationl` vers ta nouvelle URL Netlify
5. Clic **Sauvegarder**

### ÉTAPE 5 : Vérifier dans Google Search Console

1. Va sur https://search.google.com/search-console
2. Ajoute ton nouveau domaine Netlify
3. Soumets le sitemap
4. Google va indexer la nouvelle version (ça prend 24-48h)

## ✅ Vérification

Une fois live, vérifie que :
- [ ] Le logo s'affiche bien en héros
- [ ] Tous les boutons WhatsApp fonctionnent
- [ ] Les images WIX se chargent
- [ ] Le design est responsive (mobile/tablet/desktop)
- [ ] Les liens internes fonctionnent

## 🔧 Support

Si tu as des questions pendant le déploiement, dis-moi à quelle étape tu bloques !

Bonne chance ! 🌙✨
