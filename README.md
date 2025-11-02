# Landing Page SCAN 3D

Landing page professionnelle pour SCAN 3D, conçue avec des tokens Figma pixel-perfect.

## 🚀 Fonctionnalités

- **Design Pixel-Perfect** : Correspondance exacte avec le design Figma
- **Tokens Figma** : Utilisation de `variables.css` avec tous les tokens Figma
- **Responsive** : Breakpoints Figma respectés (1440px, 1024px, 768px, 390px)
- **Performance** : Images SVG optimisées avec fallbacks
- **Accessibilité** : Navigation au clavier et ARIA labels

## 📁 Structure du Projet

```
.
├── index.html          # Structure HTML principale
├── styles.css          # Styles CSS avec variables Figma
├── variables.css       # Tokens Figma (couleurs, typographie, espacements)
├── script.js           # Interactivité JavaScript
├── images/             # Images SVG
│   ├── hero-3d-scan.svg
│   ├── model-architectural.svg
│   ├── model-industriel.svg
│   ├── model-artistique.svg
│   └── model-mecanique.svg
└── README.md
```

## 🎨 Tokens Figma

Tous les tokens Figma sont centralisés dans `variables.css` :

- **Couleurs** : HEX exact du Figma (`--color-primary: #6366F1`)
- **Typographie** : Tailles, poids, line-height, letter-spacing
- **Espacements** : Valeurs en px (`--spacing-*`)
- **Border Radius** : Valeurs Figma (`--radius-*`)
- **Shadows** : Styles d'effets Figma (`--shadow-*`)

## 🛠️ Installation

1. Clonez le repository :
```bash
git clone https://github.com/RedBubblyBubble/landing-page.git
cd landing-page
```

2. Ouvrez `index.html` dans votre navigateur ou utilisez un serveur local :
```bash
# Python
python -m http.server 8000

# Node.js
npx serve
```

## 📱 Responsive Breakpoints

- **Desktop** : > 1024px
- **Tablet** : 768px - 1024px
- **Mobile** : 480px - 768px
- **Small Mobile** : < 480px

## 🎯 Sections

1. **Header** : Navigation sticky avec menu mobile
2. **Hero** : Section principale avec CTA
3. **Features** : Grille de fonctionnalités
4. **Gallery** : Galerie de scans 3D
5. **About** : Section à propos
6. **CTA** : Call-to-action
7. **Contact** : Formulaire de contact
8. **Footer** : Liens et informations

## 📝 Notes

- Toutes les valeurs hardcodées ont été remplacées par des variables Figma
- Les couleurs HEX correspondent exactement au design Figma
- Les espacements correspondent aux valeurs Figma Dev Mode
- Les images incluent des fallbacks si elles ne se chargent pas

## 👤 Auteur

**RedBubblyBubble**
- Email: elmessaoudi.soufiane90@gmail.com

## 📄 Licence

Ce projet est open source et disponible sous licence MIT.
