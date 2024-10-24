# TP-Spring-Boot-et-Thymeleaf
Ce projet est une application simple de **gestion des utilisateurs** développée avec **Spring Boot** et **Thymeleaf**. Elle permet d'ajouter et de gérer des utilisateurs avec une validation de base.

## Fonctionnalités

- **Ajouter un utilisateur** : Permet d'ajouter des utilisateurs avec un nom et un email.
- **Validation de formulaire** : Le formulaire vérifie les champs obligatoires et le format de l'email.
- **Intégration avec Spring Boot** : Gestion des opérations côté serveur.
- **Thymeleaf** : Moteur de templates pour afficher les pages HTML.
- ## Technologies utilisées

- **Java 21**
- **Spring Boot**
- **Thymeleaf**
- **Maven**
## Utilisation

1. Accéder à `http://localhost:8080/adduser` pour ajouter un utilisateur.
2. Remplir le formulaire avec le nom et l'email.
3. En cas d'erreur (ex. : email invalide), des messages d'erreur s'afficheront sous les champs concernés.

## Structure du projet

- `src/main/java` : Contient le code Java (contrôleurs, services, etc.).
- `src/main/resources/templates` : Contient les templates Thymeleaf (fichiers HTML).
- `src/main/resources/application.properties` : Fichier de configuration de l'application.
