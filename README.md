# Portfolio Professionnel - Aurélien Thébault

Portfolio professionnel moderne créé avec HTML, CSS (Tailwind) et JavaScript.

## 🚀 Fonctionnalités

- ✨ Design moderne et responsive
- 🎨 Animations fluides et élégantes
- 📱 Compatible mobile, tablette et desktop
- 🌙 Navigation smooth avec indicateur de section active
- 💼 Section projets avec filtres et hover effects
- 📧 Formulaire de contact fonctionnel
- 🎯 Barres de progression pour les compétences
- 🔝 Bouton "retour en haut" animé
- 🎮 Easter egg Konami Code

## 📋 Sections

1. **Hero** - Introduction avec photo de profil et liens sociaux
2. **À propos** - Présentation détaillée et statistiques
3. **Compétences** - Front-end, Back-end et Outils avec barres de progression
4. **Projets** - Galerie de projets avec technologies utilisées
5. **Contact** - Formulaire de contact et informations
6. **Footer** - Liens rapides et newsletter

## 🛠️ Technologies utilisées

- **HTML5** - Structure sémantique
- **Tailwind CSS** - Framework CSS utilitaire
- **JavaScript Vanilla** - Interactivité
- **Font Awesome** - Icônes
- **Google Fonts (Inter)** - Typographie

## 📦 Structure des fichiers

```
Portfolio_Aurélien_Thébault/
│
├── index.html          # Page principale
├── style.css           # Styles personnalisés et animations
├── script.js           # Fonctionnalités JavaScript
└── README.md           # Documentation
```

## 🎨 Personnalisation

### Couleurs principales

Les couleurs peuvent être modifiées dans la configuration Tailwind (dans index.html) :

```javascript
colors: {
    primary: '#3b82f6',      // Bleu principal
    secondary: '#1e40af',    // Bleu secondaire
    dark: '#0f172a',         // Couleur sombre
}
```

### Contenu à modifier

1. **Photo de profil** : Remplacer `https://via.placeholder.com/150` par votre photo
2. **Images de projets** : Remplacer les placeholders dans la section projets
3. **Informations personnelles** : Nom, titre, description, coordonnées
4. **Liens sociaux** : GitHub, LinkedIn, email
5. **Compétences** : Adapter les technologies et pourcentages
6. **Projets** : Ajouter vos propres projets

### Ajouter un nouveau projet

```html
<div
  class="bg-white rounded-lg overflow-hidden shadow-lg hover:shadow-2xl transition-all duration-300 transform hover:-translate-y-2"
>
  <div class="relative overflow-hidden group">
    <img
      src="votre-image.jpg"
      alt="Nom du projet"
      class="w-full h-64 object-cover"
    />
    <div
      class="absolute inset-0 bg-primary bg-opacity-90 opacity-0 group-hover:opacity-100 transition-opacity"
    >
      <div class="text-center">
        <a
          href="#"
          class="inline-block bg-white text-primary px-6 py-2 rounded-lg"
        >
          <i class="fas fa-eye mr-2"></i>Voir
        </a>
        <a
          href="#"
          class="inline-block bg-white text-primary px-6 py-2 rounded-lg"
        >
          <i class="fab fa-github mr-2"></i>Code
        </a>
      </div>
    </div>
  </div>
  <div class="p-6">
    <h3 class="text-xl font-bold text-gray-900 mb-2">Nom du projet</h3>
    <p class="text-gray-600 mb-4">Description du projet</p>
    <div class="flex flex-wrap gap-2">
      <span class="px-3 py-1 bg-blue-100 text-blue-700 rounded-full text-sm"
        >Tech 1</span
      >
      <span class="px-3 py-1 bg-green-100 text-green-700 rounded-full text-sm"
        >Tech 2</span
      >
    </div>
  </div>
</div>
```

## 🚀 Déploiement

### Sur Laragon (local)

Votre portfolio est déjà accessible localement via Laragon :

- URL : `http://localhost/Portfolio_Aurélien_Thébault`

### Hébergement en ligne

1. **GitHub Pages** (Gratuit)

   - Créer un repository GitHub
   - Uploader les fichiers
   - Activer GitHub Pages dans les settings

2. **Netlify** (Gratuit)

   - Créer un compte Netlify
   - Drag & drop le dossier du portfolio
   - Site déployé en quelques secondes

3. **Vercel** (Gratuit)
   - Créer un compte Vercel
   - Connecter votre repository GitHub
   - Déploiement automatique

## 📱 Responsive

Le portfolio est entièrement responsive et s'adapte à toutes les tailles d'écran :

- 📱 Mobile (< 640px)
- 📱 Tablette (640px - 1024px)
- 💻 Desktop (> 1024px)

## ⚡ Performance

- Chargement rapide avec CDN
- Images optimisées
- Animations CSS performantes
- Code JavaScript optimisé avec debounce

## 🔧 Améliorations futures possibles

- [ ] Mode sombre
- [ ] Multilingue (FR/EN)
- [ ] Blog intégré
- [ ] Galerie photos
- [ ] Témoignages clients
- [ ] Intégration API pour le formulaire
- [ ] Analytics (Google Analytics)
- [ ] SEO optimisé

## 📞 Contact

- Email : contact@exemple.com
- LinkedIn : [Votre profil]
- GitHub : [Votre profil]

## 📄 Licence

Ce projet est libre d'utilisation pour votre portfolio personnel.

---

**Créé avec ❤️ par Aurélien Thébault**
