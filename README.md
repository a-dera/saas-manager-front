# SaaS Manager Frontend

SaaS Manager est une application web open source conçue pour aider les entreprises à gérer leurs applications SaaS, leurs abonnements clients, et leurs finances de manière centralisée et efficace.

## 🌟 Fonctionnalités

- **Gestion des Applications SaaS**
  - Suivi des versions et états des services
  - Métriques de performance
  - Gestion des configurations

- **Gestion des Clients**
  - Profils clients détaillés
  - Gestion des abonnements
  - Système de facturation automatisé

- **Suivi Financier**
  - Tableau de bord des revenus
  - Rapports financiers
  - Prévisions et analyses

## Diagramme de classe
![class_diagram](/class_diagram.png)

## 🚀 Technologies

- **Backend**: AdonisJS
- **Frontend**: Nuxt.js
- **Base de données**: PostgreSQL
- **Déploiement**: Replit via GitHub Actions

## 📋 Prérequis

- Node.js (v16 ou supérieur)
- PostgreSQL
- Git

## Structure du projet
```bash
saas-manager/
├── backend/                 # AdonisJS Backend
│   ├── app/
│   │   ├── Controllers/    # Contrôleurs de l'application
│   │   ├── Models/        # Modèles de données
│   │   ├── Services/      # Services métier
│   │   └── Middleware/    # Middleware personnalisés
│   ├── config/            # Configuration AdonisJS
│   ├── database/
│   │   ├── migrations/    # Migrations de base de données
│   │   └── seeds/        # Seeds pour les données initiales
│   └── tests/            # Tests unitaires et d'intégration
│
├── frontend/               # Nuxt.js Frontend
│   ├── assets/           # Ressources statiques
│   ├── components/       # Composants Vue.js
│   ├── layouts/         # Layouts de l'application
│   ├── pages/           # Pages de l'application
│   ├── plugins/         # Plugins Nuxt.js
│   └── store/           # State management Vuex
│
├── .github/              # Configuration GitHub Actions
│   └── workflows/       # Workflows CI/CD
```

## 🛠 Installation

1. Cloner le dépôt
```bash
git clone https://github.com/votre-username/saas-manager.git
cd saas-manager
```

2. Installation des dépendances Backend
```bash
cd backend
npm install
cp .env.example .env
# Configurer les variables d'environnement dans .env
node ace migration:run
```

3. Installation des dépendances Frontend
```bash
cd ../frontend
npm install
cp .env.example .env
# Configurer les variables d'environnement dans .env
```

## 🚀 Démarrage

1. Lancer le Backend
```bash
cd backend
npm run dev
```

2. Lancer le Frontend
```bash
cd frontend
npm run dev
```

## 🧪 Tests

```bash
# Backend tests
cd backend
npm run test

# Frontend tests
cd frontend
npm run test
```

## 🤝 Contribution

Les contributions sont les bienvenues ! Voici comment vous pouvez contribuer :

1. Fork le projet
2. Créez votre branche de fonctionnalité (`git checkout -b feature/AmazingFeature`)
3. Committez vos changements (`git commit -m 'Add some AmazingFeature'`)
4. Push vers la branche (`git push origin feature/AmazingFeature`)
5. Ouvrez une Pull Request

## 📄 Licence

Ce projet est sous licence MIT - voir le fichier [LICENSE.md](LICENSE.md) pour plus de détails.

## 👥 Contact

Pour toute question ou suggestion, n'hésitez pas à ouvrir une issue sur GitHub.
