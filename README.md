# Cinimaty Careers


![image](https://github.com/user-attachments/assets/db9f826d-f532-4688-8c65-c96aa5e74c6b)


**Cinimaty Careers** est une application de gestion des offres d'emploi et des candidatures. Elle offre une expérience utilisateur fluide pour les candidats et des outils puissants pour les administrateurs, tout en exploitant des technologies modernes comme Next.js et Tailwind CSS.

---

## 🌟 Fonctionnalités principales

### 1. **Consultation des Offres d'Emploi**
- **Affichage des offres** : Liste des offres disponibles via une API tierce.
- **Recherche et filtrage** :
  - Recherche par titre, localisation, type de contrat, etc.
- **Pagination** : Gestion fluide des pages pour une expérience utilisateur optimale.

### 2. **Gestion des Candidatures**
- **Compte utilisateur** :
  - Création de compte.
  - Connexion avec authentification sécurisée.
- **Postuler à une offre** :
  - Envoi de candidatures directement depuis l'application.
- **Suivi des candidatures** :
  - Statuts disponibles : En attente, Acceptée, Refusée.

### 3. **Administration**
- **Gestion des candidatures reçues** :
  - Visualisation des détails des candidatures.
  - Ajout de notes sur une candidature.
  - Mise à jour du statut.

---

## 🔧 Technologies utilisées

### Frontend
- **Framework** : [Next.js](https://nextjs.org/) avec SSR (Server-Side Rendering).
- **UI** : [Tailwind CSS](https://tailwindcss.com/) pour un design moderne et réactif.

### Backend
- **Base de données** : MongoDB avec Mongoose ou PostgreSQL.
- **Authentification** : JSON Web Token (JWT) ou services tiers.
- **API RESTful** : Gestion des conventions standards et pagination.

### Outils supplémentaires
- **Gestion d'état** : React Context ou Redux.
- **CI/CD** : Pipelines automatisés avec GitHub Actions ou GitLab CI.
- **Tests API** : Tests E2E avec Jest et Supertest.
- **Documentation** : Swagger pour une documentation claire de l'API.

---

## 🚀 Installation et utilisation

### Prérequis
- Node.js (version 16 ou supérieure)
- MongoDB ou PostgreSQL configuré.

### Étapes d'installation

1. Clonez le dépôt :
   ```bash
   git clone https://github.com/yassineelmiri/Cinimaty_Careers.git
   cd Cinimaty_Careers
   ```

2. Installez les dépendances :
   ```bash
   npm install
   ```

3. Configurez les variables d'environnement :
   - Créez un fichier `.env` à la racine avec les informations suivantes :
     ```env
     DATABASE_URL=your_database_connection_string
     JWT_SECRET=your_jwt_secret
     API_URL=http://localhost:3000/api
     ```

4. Démarrez l'application en mode développement :
   ```bash
   npm run dev
   ```

5. Accédez à l'application sur [http://localhost:3000](http://localhost:3000).

---

## 🧪 Tests

- Lancer les tests unitaires et E2E :
  ```bash
  npm run test
  ```

---

## 📖 Documentation API

La documentation complète de l'API est disponible via Swagger. Une fois le serveur en marche, accédez à :
[http://localhost:3000/api-docs](http://localhost:3000/api-docs)

---

## 🤝 Contribution

Les contributions sont les bienvenues ! Pour contribuer :
1. Forkez le projet.
2. Créez une branche pour vos modifications :
   ```bash
   git checkout -b feature/nom-fonctionnalite
   ```
3. Soumettez une Pull Request.

---

## 📝 Licence

Ce projet est sous licence [MIT](./LICENSE).

---

## 📧 Contact

Pour toute question ou suggestion, contactez-moi à : miriyassine123@gmail.com
