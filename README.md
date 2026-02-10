# CV Interactif - Elsa Laurent

CV web interactif et responsive présentant mon parcours en marketing et communication.

## 🌟 Fonctionnalités

- **3 pages interactives** avec navigation fluide
- **Design moderne** avec animations et transitions
- **100% responsive** - optimisé mobile, tablette et desktop
- **Prêt pour la production** - aucune dépendance externe complexe
- **Performance optimale** - chargement rapide

## 📱 Pages

1. **Présentation** - Profil personnel, coordonnées et motivation
2. **Formations & Compétences** - Parcours académique et compétences clés
3. **Projets & Expériences** - Réalisations professionnelles

## 🚀 Déploiement sur GitHub Pages

### Étape 1 : Créer un repository GitHub

1. Connectez-vous à [GitHub](https://github.com)
2. Cliquez sur le bouton **"New"** pour créer un nouveau repository
3. Nommez-le : `cv-elsa-laurent` (ou le nom de votre choix)
4. Cochez **"Public"**
5. Ne cochez PAS "Add a README file"
6. Cliquez sur **"Create repository"**

### Étape 2 : Uploader les fichiers

**Option A - Via l'interface web (le plus simple) :**

1. Sur la page de votre nouveau repository, cliquez sur **"uploading an existing file"**
2. Glissez-déposez ces deux fichiers :
   - `index.html`
   - `profile.jpg`
3. Cliquez sur **"Commit changes"**

**Option B - Via Git (si vous êtes à l'aise avec la ligne de commande) :**

```bash
git init
git add index.html profile.jpg README.md
git commit -m "Initial commit - CV interactif"
git branch -M main
git remote add origin https://github.com/VOTRE-USERNAME/cv-elsa-laurent.git
git push -u origin main
```

### Étape 3 : Activer GitHub Pages

1. Dans votre repository, cliquez sur **"Settings"** (Paramètres)
2. Dans le menu latéral gauche, cliquez sur **"Pages"**
3. Sous **"Source"**, sélectionnez **"Deploy from a branch"**
4. Sous **"Branch"**, sélectionnez **"main"** et **"/ (root)"**
5. Cliquez sur **"Save"**

### Étape 4 : Accéder à votre site

Après quelques minutes, votre CV sera accessible à l'adresse :
```
https://VOTRE-USERNAME.github.io/cv-elsa-laurent/
```

GitHub affichera l'URL exacte en haut de la page Settings > Pages.

## 🎨 Personnalisation

Le code est entièrement personnalisable. Vous pouvez modifier :

- **Les couleurs** : Variables CSS dans la section `:root` (lignes 10-20)
- **Le contenu** : Textes directement dans le HTML
- **Les animations** : Propriétés CSS des animations
- **La photo** : Remplacez simplement `profile.jpg`

## 📦 Structure des fichiers

```
cv-elsa-laurent/
├── index.html      # Page principale (contient tout le code)
├── profile.jpg     # Photo de profil
└── README.md       # Ce fichier (optionnel pour GitHub Pages)
```

## 🌐 Compatibilité

- ✅ Chrome, Firefox, Safari, Edge (versions récentes)
- ✅ Mobile iOS et Android
- ✅ Tablettes
- ✅ Pas de dépendances externes critiques

## 💡 Utilisation

Une fois déployé, vous pouvez :
- Partager le lien dans vos candidatures
- L'ajouter sur LinkedIn
- Le mettre dans votre signature email
- L'imprimer en PDF depuis le navigateur

## 🔄 Mises à jour

Pour mettre à jour votre CV :
1. Modifiez `index.html` sur votre ordinateur
2. Retournez sur GitHub
3. Cliquez sur `index.html` puis sur l'icône crayon (Edit)
4. Collez votre nouveau code
5. Cliquez sur "Commit changes"

Le site sera automatiquement mis à jour en quelques minutes !

## 📧 Contact

**Elsa Laurent**  
📱 06 99 92 52 49  
🌐 [Votre site web une fois déployé]

---

*Créé avec 💖 - Prêt pour la production*
