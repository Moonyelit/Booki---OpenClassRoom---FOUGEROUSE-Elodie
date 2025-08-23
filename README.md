# 🏨 Booki - Site de Réservation d'Hébergements

![Booki Logo](./images/logo/Booki.png)

## 📋 Description du projet

**Booki** est une maquette statique d'un site de réservation d'hébergements et d'activités. Ce projet d'intégration HTML/CSS a été développé dans le cadre de la formation **Développeur d'application JavaScript React** d'OpenClassrooms.

### 🎯 Objectifs
- Intégrer une maquette statique responsive à partir de designs Figma
- Créer une interface visuelle adaptative (desktop, tablette, mobile)
- Maîtriser HTML5 sémantique et CSS3 moderne (Grid, Flexbox)
- Respecter les standards W3C et l'accessibilité web

## 🚀 Fonctionnalités

### ✅ **Interface complète**
- **Header** avec navigation fonctionnelle (ancres vers sections)
- **Barre de recherche** visuelle (interface uniquement)
- **Système de filtres** visuels avec effets hover
- **Section hébergements** avec cartes stylisées
- **Section populaires** mise en avant
- **Section activités** avec cartes interactives
- **Footer** informatif (liens non fonctionnels)

### ✅ **Design responsive**
- **Desktop** (≥1024px) : Interface Desktop first et adapté au format 1440px et plus
- **Tablette** (768px-1024px) : Adaptation intermédiaire
- **Mobile** (<768px) : Interface mobile-first

### ✅ **Fonctionnalités actives**
- **Navigation par ancres** : Liens header vers sections Hébergements/Activités
- **Effets hover** : Interactions visuelles sur cartes et boutons
- **Responsive design** : Adaptation automatique selon l'écran
- **Accessibilité** : Labels, contrastes et structure sémantique

## 🛠️ Technologies utilisées

### **Frontend**
- **HTML5** - Structure sémantique
- **CSS3** - Styles et responsive design
- **Google Fonts** - Police Raleway
- **Font Awesome** - Iconographie

### **Outils de développement**
- **Git/GitHub** - Versionning et collaboration
- **VS Code** - Environnement de développement
- **Validateurs W3C** - Contrôle qualité

## 📱 Aperçu responsive

### Desktop (1024px - 1440px)
- Navigation horizontale avec ancres fonctionnelles
- Hébergements et populaires côte à côte
- Grille d'activités 4 colonnes
- Bouton "Rechercher" avec texte (visuel uniquement)

### Tablette (1024px)
- Sections empilées verticalement
- Populaires en grille 3 colonnes
- Activités avec hauteur fixe

### Mobile (320px-767px)
- Navigation en colonnes (ancres fonctionnelles)
- Bouton recherche devient icône loupe (visuel uniquement)
- Populaires avant hébergements
- Layout entièrement vertical

## 📂 Structure du projet

```
Booki/
├── index.html              # Page principale
├── css/
│   └── style.css          # Feuille de styles complète
├── images/
│   ├── logo/              # Logo Booki
│   ├── hebergements/      # Images des hébergements
│   └── activites/         # Images des activités
└── README.md              # Documentation du projet
```

## 🎨 Choix techniques

### **CSS Grid & Flexbox**
```css
/* Grille hébergements */
.hebergements-cards {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 30px;
}

/* Layout responsive populaires */
.populaires-cards {
  display: flex;
  flex-direction: column;
}
```

### **Variables CSS**
```css
:root {
  --main-color: #0065fc;
  --main-color-hover: #0056d3;
  --main-bg-color: #f2f2f2;
  --filter-bg-color: #deebff;
  --black-color: #000000;
  --white-color: #ffffff;
  --grey-color: #d9d9d9;
}
```

### **Media Queries optimisées**
```css
/* Tablette */
@media (max-width: 1023px) { ... }

/* Mobile */
@media screen and (max-width: 767px) { ... }
```

## ✅ Validation et conformité

### **Standards respectés**
- ✅ **HTML5 valide** (Validateur W3C)
- ✅ **CSS3 valide** (Validateur W3C)
- ✅ **Sémantique web** (balises appropriées)
- ✅ **Accessibilité WCAG** (contrôles, labels)

### **Bonnes pratiques**
- ✅ Hiérarchie des titres (H1 → H2 → H3)
- ✅ Images optimisées avec `object-fit`
- ✅ Transitions fluides et micro-interactions
- ✅ Code maintenable et documenté

## 🔧 Installation et utilisation

### **Cloner le projet**
```bash
git clone https://github.com/Moonyelit/Booki---OpenClassRoom---FOUGEROUSE-Elodie.git
cd Booki---OpenClassRoom---FOUGEROUSE-Elodie
```

### **Visualiser la maquette**
1. Ouvrir `index.html` dans votre navigateur
2. Ou utiliser un serveur local (Live Server, etc.)
3. Tester les différentes résolutions avec les DevTools

### **Fonctionnalités testables**
- **Navigation** : Cliquer sur "Hébergements" ou "Activités" dans le header
- **Responsive** : Redimensionner la fenêtre pour voir les adaptations
- **Hover effects** : Survoler les cartes, boutons et filtres

## 📊 Performances

### **Optimisations réalisées**
- Images dimensionnées appropriées
- CSS optimisé sans redondances
- Fonts preconnectées pour Google Fonts
- Animations GPU-accelerated

### **Compatibilité**
- ✅ Chrome/Edge (dernières versions)
- ✅ Firefox (dernières versions) 
- ✅ Safari (dernières versions)
- ✅ Responsive design testé

## 🎓 Compétences développées

### **HTML/CSS avancé**
- Maîtrise de CSS Grid et Flexbox
- Media queries et responsive design
- Sémantique web et accessibilité
- Optimisation des performances

### **Méthodologie**
- Découpage et analyse de maquettes
- Versioning avec Git/GitHub
- Validation et contrôle qualité
- Debug avec les DevTools

## 👩‍💻 Auteur

**Élodie FOUGEROUSE**  
Étudiante Développeur d'application JavaScript React - OpenClassrooms

### 🔗 Liens utiles
- [Repository GitHub](https://github.com/Moonyelit/Booki---OpenClassRoom---FOUGEROUSE-Elodie)
- [Démo en ligne](#) *(à ajouter si déployé)*

## 📝 Contexte pédagogique

**Formation :** Développeur d'application JavaScript React - OpenClassrooms  
**Projet :** P2 - Créez la page d'accueil d'une agence de voyage avec HTML & CSS  

### **Critères d'évaluation**
- ✅ Intégration pixel-perfect des maquettes Figma
- ✅ Code HTML/CSS sémantique et valide (W3C)
- ✅ Responsive design 3 breakpoints fonctionnels
- ✅ Compatibilité navigateurs modernes
- ✅ Performance et accessibilité optimisées

### **Limitations du projet**
- **Maquette statique** : Pas de backend ou base de données
- **Navigation limitée** : Seules les ancres header sont fonctionnelles
- **Formulaires visuels** : Recherche et filtres sans traitement
- **Liens factices** : Footer et cartes sans redirection

---

## 📄 Licence

Ce projet est réalisé dans un cadre pédagogique pour OpenClassrooms.

---

**💡 Ce README présente un projet d'apprentissage démontrant la maîtrise des fondamentaux du développement web front-end.**