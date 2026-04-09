# 📚 EduConnect API

EduConnect est une API REST développée avec Laravel pour une plateforme e-learning.  
Elle permet aux enseignants de créer et gérer des cours, aux étudiants de s’y inscrire et de les suivre, et à l’administrateur de gérer les utilisateurs et les rôles.

---

## 🚀 Fonctionnalités principales

### 👨‍🏫 Enseignant
- Créer un cours
- Modifier ou supprimer ses cours
- Consulter ses cours

### 🎓 Étudiant
- Voir tous les cours disponibles
- S’inscrire à un cours
- Accéder à ses cours

### 🛠️ Administrateur
- Gérer les utilisateurs
- Attribuer les rôles (admin, professeur, etudiant)
- Contrôler les accès

---

## 🔐 Authentification & Sécurité
- Authentification via **Laravel Sanctum**
- Gestion des rôles via un champ `role` dans la table users (admin, professeur, etudiant)
- Contrôle d’accès géré manuellement dans les contrôleurs
- Protection des routes avec middleware (`auth:sanctum`)

---

## 📡 API
EduConnect fournit une API REST sécurisée permettant :
- 🔐 L’authentification des utilisateurs 
- 📚 La gestion des cours 
- 🎓 L’inscription des étudiants 
- 🛠️ L’administration des utilisateurs et des rôles

---

## ⚙️ Stack technique
- Laravel
- Laravel Sanctum
- MySQL

---

## 👩‍💻 Réalisé par

- **Housna Fathi** – Développeuse web Full-Stack  
