# Portfolio Développeur Next.js

![Next.js](https://img.shields.io/badge/Next.js-14-black?style=for-the-badge&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-10-purple?style=for-the-badge&logo=framer&logoColor=white)
![Sentry](https://img.shields.io/badge/Sentry-black?style=for-the-badge&logo=sentry&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

Ce projet est un portfolio de développeur moderne et performant, conçu pour présenter mes compétences et mes réalisations. Il est construit avec les dernières technologies web pour offrir une expérience utilisateur fluide, un design responsive et des performances optimisées.

## Aperçu

![Aperçu du Portfolio](https://via.placeholder.com/800x400.png?text=Aperçu+du+Portfolio)
*(Remplacez cette image par une capture d'écran ou un GIF de votre portfolio)*

[**Lien vers la démo live**](#) *(Ajoutez le lien vers votre site déployé)*

## 🎯 Fonctionnalités

- **Présentation de Projets :** Une section dédiée pour mettre en valeur mes travaux avec des descriptions, des images et des liens.
- **Expérience Utilisateur Moderne :** Animations fluides et transitions grâce à Framer Motion.
- **Design Responsive :** Entièrement adaptable sur tous les appareils, du mobile au bureau.
- **Accessibilité :** Conçu en gardant à l'esprit les standards d'accessibilité (WCAG).
- **Performances Optimisées :** Temps de chargement rapides grâce au rendu côté serveur (SSR) et à la génération de sites statiques (SSG) de Next.js.
- **Suivi des Erreurs :** Intégration de Sentry pour un monitoring en temps réel des erreurs et des performances en production.

## 🏗️ Stack Technique

Ce projet utilise une stack moderne et robuste pour garantir une base solide et évolutive.

| Catégorie | Technologie | Description |
| --- | --- | --- |
| **Framework** | [Next.js 14 (App Router)](https://nextjs.org/) | Framework React pour la production avec rendu hybride. |
| **Langage** | [TypeScript](https://www.typescriptlang.org/) | Sur-ensemble de JavaScript qui ajoute un typage statique. |
| **Styling** | [Tailwind CSS](https://tailwindcss.com/) | Framework CSS "utility-first" pour un design rapide et personnalisé. |
| **UI (Composants)** | [Aceternity UI](https://ui.aceternity.com/) | Collection de composants innovants et prêts à l'emploi. |
| **UI (Composants)** | [shadcn/ui](https://ui.shadcn.com/) | Composants de base réutilisables et accessibles. |
| **UI (Design System)**| [Origin UI](https://www.origin-ui.com/) | Design system pour une cohérence visuelle. |
| **Animations** | [Framer Motion](https://www.framer.com/motion/) | Bibliothèque d'animation pour React. |
| **Monitoring** | [Sentry](https://sentry.io/) | Suivi des erreurs et des performances applicatives. |
| **Versioning** | [Git](https://git-scm.com/) & [GitHub](https://github.com/) | Système de contrôle de version et plateforme d'hébergement. |

## 🚀 Installation et Lancement Local

Suivez ces étapes pour configurer et lancer le projet sur votre machine locale.

### Prérequis

- [Node.js](https://nodejs.org/en/) (version 18.x ou supérieure)
- [pnpm](https://pnpm.io/installation) (recommandé pour la gestion des paquets)

### 1. Cloner le dépôt

```bash
git clone https://github.com/VOTRE_USERNAME/VOTRE_REPO.git
cd VOTRE_REPO
```

### 2. Installer les dépendances

```bash
pnpm install
```

### 3. Configurer les variables d'environnement

Créez un fichier `.env.local` à la racine du projet et ajoutez les variables nécessaires. Vous pouvez vous baser sur le fichier `.env.example` s'il existe.

```env
# Exemple de variable pour Sentry
SENTRY_DSN=VOTRE_DSN_SENTRY
```

### 4. Lancer le serveur de développement

```bash
pnpm dev
```

Ouvrez [http://localhost:3000](http://localhost:3000) dans votre navigateur pour voir le résultat.

## 📜 Scripts Disponibles

Ce projet inclut plusieurs scripts pour vous aider dans le développement et le déploiement.

| Script | Description |
| --- | --- |
| `pnpm dev` | Lance le serveur de développement avec rechargement à chaud. |
| `pnpm build` | Construit l'application pour la production. |
| `pnpm start` | Démarre un serveur de production après un `build`. |
| `pnpm lint` | Exécute ESLint pour analyser le code et trouver les erreurs. |
| `pnpm test` | Lance les tests (à configurer avec Jest ou Vitest). |

## 📂 Structure du Projet

La structure des dossiers suit les conventions de Next.js avec l'App Router.

```
.
├── .github/              # Workflows GitHub Actions (CI/CD)
├── .vscode/              # Paramètres de l'éditeur VS Code
├── public/               # Fichiers statiques (images, polices)
├── src/
│   ├── app/              # Routes, pages et layouts (App Router)
│   │   ├── api/          # Routes d'API
│   │   ├── (components)/ # Composants partagés pour les pages
│   │   ├── layout.tsx    # Layout principal
│   │   └── page.tsx      # Page d'accueil
│   ├── components/       # Composants globaux de l'application
│   │   ├── ui/           # Composants de base (ex: shadcn/ui)
│   │   └──aceternity/    # Composants Aceternity UI
│   ├── lib/              # Fonctions utilitaires, hooks
│   ├── styles/           # Fichiers de style globaux
│   └── types/            # Définitions de types TypeScript
├── .eslintrc.json        # Configuration ESLint
├── .gitignore            # Fichiers ignorés par Git
├── next.config.mjs       # Configuration de Next.js
├── package.json          # Dépendances et scripts du projet
├── postcss.config.js     # Configuration PostCSS
├── tailwind.config.ts    # Configuration Tailwind CSS
├── tsconfig.json         # Configuration TypeScript
└── README.md             # Ce fichier
```

## 🤝 Contributing

Les contributions sont les bienvenues ! Si vous souhaitez améliorer ce projet, veuillez suivre ces étapes :

1.  Forker le projet
2.  Créer une nouvelle branche (`git checkout -b feature/AmeliorationIncroyable`)
3.  Commit vos changements (`git commit -m 'Ajout de AmeliorationIncroyable'`)
4.  Push vers la branche (`git push origin feature/AmeliorationIncroyable`)
5.  Ouvrir une Pull Request

## 📄 License

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de détails.
