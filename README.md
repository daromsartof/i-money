# iMoney - Application de Gestion de Budget Personnel

Une application de gestion de budget inspirée de YNAB (You Need A Budget) construite avec React et Express.js.

## Fonctionnalités

- Méthode de budgétisation "donnez un emploi à chaque dollar"
- Suivi des dépenses en temps réel
- Planification budgétaire personnalisée
- Rapports et analyses détaillés
- Gestion des objectifs d'épargne
- Interface utilisateur moderne et responsive

## Structure du Projet

```
imoney/
├── client/          # Frontend React
│   ├── src/
│   │   ├── components/  # Composants réutilisables
│   │   ├── pages/      # Pages de l'application
│   │   ├── features/   # Fonctionnalités Redux
│   │   ├── services/   # Services API
│   │   └── utils/      # Utilitaires
│   └── package.json
│
└── server/          # Backend Express.js
    ├── src/
    │   ├── controllers/  # Contrôleurs
    │   ├── models/      # Modèles Mongoose
    │   ├── routes/      # Routes API
    │   ├── middleware/  # Middleware
    │   └── config/      # Configuration
    └── package.json
```

## Installation

1. Cloner le dépôt
2. Installer les dépendances :
   ```bash
   # Backend
   cd server
   npm install

   # Frontend
   cd client
   npm install
   ```

## Démarrage

1. Démarrer le serveur backend :
   ```bash
   cd server
   npm run dev
   ```

2. Démarrer le client frontend :
   ```bash
   cd client
   npm run dev
   ```

## Technologies Utilisées

- Frontend :
  - React
  - Material-UI
  - Redux Toolkit
  - React Router
  - Recharts

- Backend :
  - Express.js
  - MongoDB avec Mongoose
  - JWT pour l'authentification
  - Cors
  - Morgan pour le logging
