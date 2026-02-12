# Microservice Utilisateurs & Authentification

## Description
Ce microservice assure l’authentification centralisée et la gestion complète des utilisateurs de la plateforme.

Ce service est développé dans le cadre du cours **Applications Web Distribuées**.

## Responsabilités
- Création et gestion des comptes utilisateurs
- Authentification via JWT (access & refresh tokens)
- Gestion des rôles et permissions (RBAC)
- Sécurisation des endpoints
- Fournisseur d’authentification pour les autres microservices

## Technologies
- NestJS
- TypeScript
- MongoDB
- Passport.js
- JWT

## Choix Techniques
- Architecture modulaire et scalable
- Flexibilité du schéma MongoDB selon les rôles utilisateurs
- Performances élevées pour l’authentification fréquente
