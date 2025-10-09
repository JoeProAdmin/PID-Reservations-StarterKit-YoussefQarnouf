# PID Réservations - Starter Kit (Youssef Qarnouf)

## Description
Projet d’intégration ICC 2025 - Application de réservation de spectacles.  
Ce projet constitue un **Starter Kit complet** combinant un backend Java Spring Boot 3 et un frontend Angular 20.  
Il sert de base de développement pour le projet complet PID Réservations.

## Architecture
- **Backend :** Spring Boot 3 (Java 17) - API REST pour la gestion des artistes  
- **Frontend :** Angular 20 - Interface de visualisation des artistes  
- **Base de données :** MySQL via JPA/Hibernate  

## Objectif
Fournir une architecture claire, modulaire et évolutive pour un environnement académique professionnel.

## Technologies utilisées
| Couche | Technologie | Rôle |
|--------|--------------|------|
| Backend | Spring Boot 3 | Développement de l’API REST |
| Frontend | Angular 20 | Interface dynamique |
| Base de données | MySQL | Stockage des données |
| IDE | IntelliJ IDEA / VS Code | Développement |
| Versioning | Git & GitHub | Suivi et publication du code |

## Instructions d’exécution

### 1. Lancer le backend
```bash
cd PID-Reservations-Backend
mvn spring-boot:run
Accès : http://localhost:8080/api/artists

Accès à l’API : http://localhost:8080/api/artists

2. Lancer le frontend

Dans un second terminal, exécute les commandes suivantes :

cd PID-Reservations-Frontend
ng serve -o


Accès à l’interface : http://localhost:4200

Auteur

Youssef Qarnouf
Institut des Carrières Commerciales (ICC) – Année académique 2025-2026
Cours : Projet d’Intégration – Développement (PID)

Release officielle : v1.0.0 – Starter Kit Fonctionnel
