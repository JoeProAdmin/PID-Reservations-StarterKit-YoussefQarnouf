# PID Réservations - Starter Kit (Youssef Qarnouf)

##  Description

Projet d’intégration ICC 2025 - Application de réservation de spectacles.
Ce projet constitue un **Starter Kit complet** combinant un backend **Java Spring Boot 3** et un frontend **Angular 17**.
Il sert de **base de développement** pour le projet complet *PID Réservations 2025*.

Le Starter Kit met en place les fondations techniques et une architecture professionnelle prête à être étendue.

---

##  Architecture du projet

| Couche              | Technologie             | Rôle                                            |
| ------------------- | ----------------------- | ----------------------------------------------- |
| **Backend**         | Spring Boot 3 (Java 17) | Fournit l’API REST pour la gestion des artistes |
| **Frontend**        | Angular 17              | Interface de visualisation des artistes         |
| **Base de données** | MySQL                   | Stockage des données                            |
| **ORM**             | JPA / Hibernate         | Mapping objet-relationnel                       |
| **IDE utilisés**    | IntelliJ IDEA           | Développement complet                           |
| **Versioning**      | Git & GitHub            | Suivi et publication du code                    |

---

##  Fonctionnalités du Starter Kit

- Structure complète d’un projet **Spring Boot / Angular**
- Exemple d’entité `Artist` avec CRUD simplifié
- API REST accessible via `/api/artists`
- Intégration de base MySQL
- Code prêt à être enrichi (ajout de modules ou entités)

---

##  Objectif pédagogique

Ce projet a pour but de fournir une **base technique propre** pour le cours *Projet d’Intégration Développement (PID)*.
Il permet aux étudiants de se concentrer sur le **développement fonctionnel**, sans perdre de temps sur la configuration initiale.

Objectifs :

* Créer un projet Java + Angular cohérent
* Comprendre la liaison REST entre frontend et backend
* Préparer le socle technique d’une application modulaire
* Travailler avec GitHub et Maven dans un contexte professionnel

---

##  Structure du projet

### Backend (`PID-Reservations-Backend`)

* Langage : Java 17
* Framework : Spring Boot 3
* Accès : [http://localhost:8080/api/artists](http://localhost:8080/api/artists)
* Commande :

  ```bash
  cd PID-Reservations-Backend
  mvn spring-boot:run
  ```

### Frontend (`PID-Reservations-Frontend`)

* Framework : Angular 17
* Commande :

  ```bash
  cd PID-Reservations-Frontend
  npm install
  npm start
  ```
* Accès : [http://localhost:4200](http://localhost:4200)

---

##  Bonnes pratiques incluses

* Organisation modulaire du code
* Séparation claire **Frontend / Backend**
* Utilisation d’`application.properties` pour la configuration
* Respect des conventions Angular et Spring Boot
* Architecture prête pour le déploiement futur (Docker, CI/CD)

---

##  Release actuelle

**Version : v1.0.0 – Starter Kit Fonctionnel**

* API de base opérationnelle
* Liaison Angular ↔ Spring Boot prête
* Exemple de table MySQL : `artists`

---

##  Auteur

**Youssef Qarnouf**
Institut des Carrières Commerciales (ICC) - Année académique 2025-2026
Cours : Projet d’Intégration Développement (PID)
GitHub : [JoeProAdmin](https://github.com/JoeProAdmin)

---

##  Licence

Projet académique distribué à des fins d’apprentissage.
Toute réutilisation pédagogique est autorisée avec mention de l’auteur.

---



