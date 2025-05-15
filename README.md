# 💼 Portfolio - FLORIANE DEUGOUE

Bienvenue sur mon portfolio personnel, réalisé avec **Next.js** et **Tailwind CSS**.  
Ce site me permet de présenter mes compétences, mes projets, et de faciliter le contact avec les recruteurs ou collaborateurs.

---

## 🚀 Technologies utilisées

- [Next.js](https://nextjs.org/) – Framework React pour les sites modernes
- [Tailwind CSS](https://tailwindcss.com/) – Framework CSS utilitaire
- [TypeScript](https://www.typescriptlang.org/) – Typage optionnel utilisé dans le projet
- Git & GitHub – Versionnage et hébergement
- GitHub Pages – Pour la mise en ligne gratuite du site

---

## 🔗 Démo en ligne

👉 [Accéder au site](https://floradeugoue.github.io/mon_portfolio)

## 📁 Structure du projet

```
mon_portfolio/
├── app/
│   ├── page.tsx             # Page d’accueil (one-page)
│   ├── layout.tsx           # Layout global (header, footer)
│   └── globals.css          # Styles globaux + Tailwind
│
├── components/              # Composants réutilisables
│   ├── Navbar.tsx
│   ├── HeroSection.tsx
│   ├── AboutSection.tsx
│   ├── ServicesSection.tsx
│   ├── PortfolioSection.tsx
│   └── ContactSection.tsx
│
├── public/                  # Images, favicon, etc.
│   └── images/
│
├── styles/                  # (Optionnel) Fichiers CSS personnalisés
│
├── tailwind.config.js       # Configuration Tailwind
├── postcss.config.js        # Configuration PostCSS
├── tsconfig.json            # Configuration TypeScript
├── package.json             # Dépendances et scripts
└── README.md                # Ce fichier
```

## 🛠️ Installation

1. Clone ce dépôt :
```bash
git clone https://github.com/floradeugoue/mon_portfolio.git
cd mon_portfolio
```

2. Installe les dépendances :
```bash
npm install
```

3. Lance le serveur de développement :
```bash
npm run dev
```

4. Accède à l'application dans ton navigateur :
```
http://localhost:3000
```

## 🔗 Navigation dans la page

Chaque section est une ancre HTML :
- `#accueil`
- `#a-propos`
- `#services`
- `#portfolio`
- `#contact`

> Exemple : `http://localhost:3000/#contact` fait défiler jusqu’à la section Contact.

## 📦 Déploiement

Tu peux déployer ce portfolio sur :
- [Vercel](https://vercel.com) (recommandé pour Next.js)
- Netlify
- GitHub Pages (avec adaptations)

## ✨ À venir

- Mode sombre
- Animations avec Framer Motion
- Formulaire de contact fonctionnel avec EmailJS ou autre
- Version mobile optimisée

## 🧑‍💻 Auteur

Développé par **[Floriane Deugoue]**  
Contact : [gmail](kamenideugoue22@gmail.com)
linkedin : [linkedin](https://www.linkedin.com/in/deugoue-floriane)
github : [github](https://github.com/floradeugoue)
