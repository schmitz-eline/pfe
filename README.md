# Projet de Fin d'Études - Orchestrate

## Note d'intention

Au sein des orchestres amateurs, l'organisation des répétitions, concerts, événements et tâches logistiques nécessite une coordination importante entre les musiciens, le chef et les membres du comité.

Aujourd'hui, ces informations sont souvent dispersées entre différents outils : messageries, emails, réseaux sociaux, calendriers, dossier Drive partagé ou fichiers Excel. Cette fragmentation complique le suivi des présences, la communication interne et l'organisation des événements.

Orchestrate a pour ambition de proposer une application mobile, ainsi qu'un site web, spécialement conçus pour les musiciens amateurs. L'objectif est de centraliser les informations essentielles au fonctionnement d'un orchestre tout en offrant une expérience simple, moderne et accessible à des utilisateurs ayant des niveaux de compétence numérique variés.

Contrairement aux outils de gestion trop généraux ou aux solutions professionnelles trop complexes, Orchestrate cherche à trouver un équilibre entre simplicité d'utilisation et richesse fonctionnelle. Le projet s'adresse avant tout aux harmonies, fanfares et orchestres amateurs qui souhaitent moderniser leur organisation.

À terme, la plateforme doit devenir un véritable outil de coordination permettant d'améliorer la communication, la participation des membres et l'efficacité organisationnelle des orchestres amateurs.

---

## Objectifs

- Centraliser les informations importantes d'un orchestre
- Simplifier l'organisation des événements et répétitions
- Améliorer le suivi des présences
- Faciliter la répartition des tâches logistiques
- Renforcer l'implication des musiciens grâce à des mécanismes de participation et de gamification

---

## Fonctionnalités envisagées

| **Catégorie**        | **Description**                                                                                                 | **Rôles concernés** |
|----------------------|-----------------------------------------------------------------------------------------------------------------|---------------------|
| **Authentification** | Création de compte, connexion sécurisée, réinitialisation du mot de passe                                       | Tous                |
| **Membres**          | Création et gestion d’un groupe, ajout/suppression de membres, attribution de rôles                             | Comité              |
| **Rôles**            | Attribution de permissions spécifiques selon le rôle (chef, comité, musicien, créateur de groupe)               | Tous                |
| **Événements**       | Création/modification/suppression d’événements, calendrier global, rappels automatiques                         | Tous                |
| **Sondages**         | Proposition de plusieurs dates et vote des membres avant validation d’un événement                              | Tous                |
| **Présences**        | Confirmation ou refus de présence, statistiques globales, rappels pour réponse manquante                        | Musiciens, chef     |
| **Partitions**       | Le chef attribue les voix et les musiciens peuvent voir, ou les musiciens choisissent et le chef peut consulter | Musiciens, chef     |
| **Tâches**           | Création et attribution de tâches, inscription libre des membres, rappels automatiques                          | Comité, musiciens   |
| **Gamification**     | Attribution de points et badges selon l’assiduité et la participation                                           | Musiciens           |
| **Statistiques**     | Tableau de bord global des présences et participation par répétition, événement ou musicien                     | Chef                |
| **Communication**    | Envoi de messages individuels ou groupés                                                                        | Tous                |
| **Partage média**    | Partage de photos et vidéos après un événement                                                                  | Tous                |
| **Notifications**    | Alertes pour événements, messages, tâches ou rappels                                                            | Tous                |
| **Paramètres**       | Modification du profil, langue, préférences de notifications, thèmes clair et sombre                            | Tous                |
| **Multi-groupes**    | Possibilité de rejoindre plusieurs orchestres avec un seul compte                                               | Tous                |

---

## Personae et user stories

### Bastien, 30 ans, professeur de percussions, chef d’harmonie

<img width="150" height="150" alt="Avatar de Bastien" src="https://github.com/user-attachments/assets/e91cf146-f9ac-4867-9086-a15c6e455450" />

**Rôle :** direction, organisation des répétitions et des concerts

**Besoins :**
- suivi des présences
- suivi des partitions
- communication avec les membres

**User stories :**

En tant que **chef**, je veux :
- **créer et planifier des événements** (concerts, répétitions) afin d’organiser le calendrier musical
- **avoir un aperçu des partitions** des musiciens afin que la répartition soit équilibrée dans l’orchestre
- **consulter la liste des présences** afin d’anticiper les absences et adapter les répétitions

---

### Thomas, 36 ans, agriculteur, président et musicien dans une harmonie

<img width="150" height="150" alt="Avatar de Thomas" src="https://github.com/user-attachments/assets/19dd56e7-7647-4034-adc6-cf70b7bb444a" />

**Rôle :** management, logistique, gestion administrative

**Besoins :**
- planification des événements à venir
- gestion des tâches
- centralisation des informations importantes

**User stories :**

En tant que **président**, je veux :
- **planifier un événement** avec toutes ses informations pratiques (lieu, horaire, tenue, programme) afin que tout soit clair pour les musiciens
- **attribuer et suivre des tâches** afin de répartir le travail efficacement
- **envoyer un message** à tout le groupe afin de communiquer rapidement
- **gérer les membres** (ajouter, supprimer, modifier) afin de tenir le groupe à jour
- **organiser des réunions** mensuelles avec les membres du comité

---

### Eline, 21 ans, étudiante, trompettiste dans 2 harmonies et social media manager

<img width="150" height="150" alt="Avatar d’Eline" src="https://github.com/user-attachments/assets/11daad58-3d5a-418a-9427-b0fc6f8a6acb" />

**Rôle :** musicienne, réseaux sociaux

**Besoins :**
- indication de présence et inscription aux tâches d’un événement
- indication de ce que je joue
- accès à différents groupes depuis un même compte

**User stories :**

En tant que **musicienne**, je veux :
- **voir la liste des événements à venir** afin de planifier ma participation
- **confirmer ou refuser ma présence** afin de prévenir le chef
- **indiquer mes partitions** afin que le chef sache ce que je joue pour chaque morceau ou **consulter** les voix que le chef m’a attribuées
- **m’inscrire à une tâche** (bar, vaisselle, cuisine, etc.) afin de participer à l’organisation
- **changer de groupe** depuis mon compte afin d’accéder à mes différents orchestres

En tant que **social media manager**, je veux :
- **avoir accès aux photos et vidéos** prises pendant les événements pour pouvoir les poster sur les réseaux
- **pouvoir communiquer avec le comité** par rapport aux flyers et à la publicité sur les réseaux sociaux
