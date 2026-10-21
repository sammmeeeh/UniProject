UniProject — Gestion des Projets Universitaires

UniProject est une application web développée dans le cadre d'un projet académique à l'IHEC Carthage. Elle centralise la gestion des projets universitaires en offrant une plateforme permettant aux étudiants de soumettre leurs projets, aux enseignants de les consulter et de commenter, et aux administrateurs de gérer leur validation et leur suivi.

L'application intègre également un chatbot basé sur l'intelligence artificielle pour faciliter la recherche d'informations dans le catalogue des projets.

Problématique:

La gestion traditionnelle des projets universitaires entraîne plusieurs difficultés :

Absence d'un catalogue centralisé des projets.

Difficulté à rechercher et consulter les projets existants.

Manque de visibilité sur le processus de validation.

Absence de notifications et de suivi des commentaires.

Risque de duplication des sujets entre différentes équipes.

Manque d'outils statistiques pour le suivi administratif.

Fonctionnalités principales:

-Gestion des étudiants et des projets

-Inscription et authentification sécurisées.

-Soumission de projets avec métadonnées structurées et fichiers joints (PDF/ZIP, jusqu'à 20 Mo).

-Modification et suppression des projets selon les autorisations.

-Consultation du catalogue et des fiches détaillées.

-Gestion des favoris pour sauvegarder les projets intéressants.

Recherche avancée:

-Recherche par titre, résumé, mots-clés et spécialité.

-Filtrage par année académique, semestre et statut.

-Affichage paginé des résultats.

Workflow de validation:

G-estion du cycle de vie des projets selon les statuts suivants :

BROUILLON → SOUMIS → VALIDÉ / REJETÉ → ARCHIVÉ

Les administrateurs peuvent consulter les projets en attente et gérer leur validation.

Commentaires et notifications:

Ajout de commentaires pour faciliter les échanges entre étudiants et encadrants.

Notifications lors de nouveaux projets ou commentaires.

Suivi des notifications et gestion de leur statut de lecture.

Administration et statistiques:

Gestion des comptes utilisateurs et de leurs accès.

Tableau de bord avec des indicateurs clés sur les projets.

Statistiques par spécialité, année académique et statut.

Export du catalogue au format CSV.

Chatbot IA:

Interaction en langage naturel avec le catalogue de projets.

Réponses contextuelles basées sur les données disponibles.

Intégration de l'API OpenRouter.

Conservation de l'historique des conversations pendant la session.

Sécurité:

Authentification et autorisation avec Spring Security.

Gestion des rôles et des permissions (RBAC).

Hachage des mots de passe avec BCrypt.

Validation des adresses e-mail institutionnelles @ihec.ucar.tn.

Réinitialisation du mot de passe par e-mail avec un lien temporaire.

Technologies utilisées:
Java 17
Spring Boot 3.4.5
Spring MVC
Thymeleaf
Spring Security 6
Spring Data JPA / Hibernate
MySQL 8
