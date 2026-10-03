# Projet de Fin d’Études - Orchestrate

## 1. Présentation de l’application et du besoin

Au sein des **orchestres amateurs**, l’organisation des répétitions, concerts, événements et des tâches logistiques nécessite une coordination importante entre les musiciens, le chef et les membres du comité.

Aujourd’hui, ces informations sont souvent dispersées entre différents outils : messageries, emails, réseaux sociaux, calendriers, dossier Drive partagé ou fichiers Excel. Cette fragmentation complique le suivi des présences, la communication interne et l’organisation des événements.

**Orchestrate** a pour ambition de proposer une application spécialement conçue pour les musiciens amateurs. L’objectif est de centraliser les informations essentielles au fonctionnement d’un orchestre tout en offrant une expérience simple, moderne et accessible à des utilisateurs ayant des niveaux de compétence numérique variés.

Contrairement aux outils de gestion trop généraux ou aux solutions professionnelles trop complexes, Orchestrate cherche à trouver un équilibre entre simplicité d’utilisation et richesse fonctionnelle. Le projet s’adresse avant tout aux harmonies, fanfares et orchestres amateurs qui souhaitent moderniser leur organisation.

À terme, la plateforme doit devenir un véritable outil de coordination permettant d’améliorer la communication, la participation des membres et l’efficacité organisationnelle des orchestres amateurs.

---

## 2. Objectifs

- Centraliser les informations importantes d’un orchestre
- Simplifier l’organisation des événements et répétitions
- Améliorer le suivi des présences
- Faciliter la répartition des tâches logistiques et des partitions
- Renforcer l’implication des musiciens grâce à des mécanismes de participation et de gamification

---

## 3. Étude de l’existant

Comparons **Orchestrate** avec deux applications populaires auprès des orchestres : [Spond](https://help.spond.com/app/fr/articles/121230-a-propos-de-l-application-spond) et [Konzertmeister](https://konzertmeister.app/fr). On pourrait aussi parler d’applications de calendrier en groupe, comme [FamilyWall](https://www.familywall.com/).

---

### Spond

**Spond** facilite l’organisation des activités de groupe. Elle permet de planifier des événements, d’envoyer des invitations, de suivre les présences et de communiquer efficacement avec les membres. Grâce à ses fonctionnalités comme les rappels automatiques, les sondages et le partage de photos, Spond simplifie la coordination entre les organisateurs et les participants.

<img width="333" height="592" alt="image" src="https://github.com/user-attachments/assets/d8fb497e-05a6-45be-868d-2822ba719035" />

<img width="333" height="592" alt="image" src="https://github.com/user-attachments/assets/720900b6-1a03-4a51-aa42-921d63beb380" />

<img width="333" height="592" alt="image" src="https://github.com/user-attachments/assets/142c443e-66f2-4ce4-8841-a8d8ec4683d5" />

---

### Konzertmeister

**Konzertmeister** est une application conçue pour les orchestres, chœurs et ensembles professionnels. Elle aide à planifier les répétitions, gérer les présences et centraliser les informations logistiques. C’est un outil efficace pour les grandes structures, mais parfois trop complexe pour les musiciens amateurs.

<img width="333" height="592" alt="image" src="https://github.com/user-attachments/assets/d461bd65-2908-481d-998f-b641e19da186" />

<img width="333" height="592" alt="image" src="https://github.com/user-attachments/assets/aea25651-da4a-436e-8568-ca9c244085db" />

<img width="333" height="592" alt="image" src="https://github.com/user-attachments/assets/fd0ed758-c655-47e3-995d-e0c658a4b854" />

---

### Points forts et points faibles

| Application        | Points forts | Points faibles |
|--------------------|--------------|----------------|
| **Spond**          | - Application simple et conviviale<br>- Systèmes de notifications et de présences efficaces | - Interface générique, sans identité musicale<br>- Gestion des tâches limitée |
| **Konzertmeister** | - Spécialement pensée pour les orchestres<br>- Gestion précise des plannings et des instruments | - Interface complexe, peu adaptée aux amateurs<br>- Moins accessible sur mobile |

---

### Ce qu’Orchestrate apporte

**Orchestrate** combine la simplicité et la convivialité de Spond, avec la structure musicale et la rigueur de Konzertmeister. D’autres fonctionnalités sont rajoutées pour éviter de devoir jongler entre les e-mails, les messages et les fichiers Excel, et donc pouvoir tout faire à un seul endroit.

---

## 4. Public cibles et personae

**Orchestrate** s’adresse principalement aux orchestres amateurs, composés de musiciens passionnés. Ces ensembles ont besoin d’un outil simple et efficace pour organiser leurs concerts, leurs événements, gérer les présences…

L’objectif est donc de fournir une application qui facilite la communication, la planification et la coordination au sein d’un orchestre amateur, tout en étant agréable à utiliser, même pour des utilisateurs peu familiers avec le numérique.

Afin de mieux comprendre les besoins des utilisateurs d’Orchestrate, plusieurs personae représentatifs ont été imaginés. Ils incarnent différents rôles clés au sein d’une harmonie : le chef, le président (ou les autres membres du comité) et les musiciens.

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
- **attribuer des partitions** aux musiciens ou **avoir un aperçu** de leurs choix afin que la répartition soit équilibrée dans l’orchestre
- **consulter la liste des présences** afin d’anticiper et adapter les répétitions

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

### Eline, 22 ans, étudiante, trompettiste dans 2 harmonies et social media manager

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

---

## 5. Fonctionnalités envisagées

**Orchestrate** est une application complète et intuitive pensée pour simplifier la vie des musiciens amateurs. Elle centralise toutes les informations essentielles : **événements, présences, partitions, tâches et communication**.

Conçue autour d’une interface fluide et collaborative, elle s’adapte à trois profils d’utilisateurs : **chefs, membres du comité et musiciens**. Chaque rôle accède à des fonctionnalités adaptées à ses besoins, dans une interface fluide et claire.

---

### A. Authentification

L’accès à Orchestrate est sécurisé par un système d’authentification. Chaque utilisateur dispose de son propre compte, garantissant la confidentialité et la personnalisation de l’expérience.

**Fonctionnalités incluses :**

- Inscription d’un nouvel utilisateur avec e-mail et mot de passe
- Connexion sécurisée (avec vérification des identifiants)
- Réinitialisation du mot de passe
- Déconnexion manuelle
- Persistance de la session (connexion automatique si déjà authentifié)
- Redirection automatique selon le rôle de l’utilisateur (chef / membre du comité / musicien)

---

### B. Membres d’un groupe

Orchestrate permet de gérer un orchestre et les membres qui le composent.

**Fonctionnalités incluses :**

- Création d’un groupe
- Ajout / modification / suppression de membres
- Attribution de rôles (chef, membre du comité, musicien, rôle supplémentaire (ex : social media manager))
- Profil utilisateur avec photo, instrument(s), contact, etc.

**Rôles concernés :**

- Créateur du groupe : normalement un membre du comité

---

### C. Événements

Fonctionnalité essentielle d’Orchestrate, la gestion des événements permet d’organiser la vie de l’orchestre.

**Fonctionnalités incluses :**

- Création d’un événement : titre, description, lieu, date, horaire, tenue, programme, etc.
- Création de sondages de disponibilité avant de planifier un événement (pour choisir la meilleure date selon les votes des membres)
- Affichage d’un calendrier global des événements
- Consultation des détails d’un événement
- Modification ou suppression d’un événement par les membres du comité ou le chef
- Envoi automatique de rappels avant chaque événement
- Partage de photos et vidéos après un événement

**Rôles concernés :**

- Chef et membres du comité : création et gestion
- Musiciens : consultation et présence

---

### D. Présences

Chaque membre doit confirmer ou refuser sa présence aux différents événements.

**Fonctionnalités incluses :**

- Indication de présence / absence à un événement
- Visualisation du statut de présence de chaque musicien
- Rappels automatiques pour les membres n’ayant pas encore répondu
- Résumé global du taux de participation

**Rôles concernés :**

- Musiciens : déclaration de présence
- Chef : suivi et statistiques de participation

---

### E. Partitions

Orchestrate permet aux musiciens d’indiquer eux-mêmes la ou les partition(s) qu’ils jouent pour chaque morceau. Le chef peut aussi attribuer lui-même les partitions aux musiciens. Cela simplifie la préparation musicale et offre au chef une vision claire de la répartition instrumentale.

**Fonctionnalités incluses :**

- Liste des morceaux joués à un événement
- Indication ou attribution de la / des partition(s) jouée(s) pour chaque morceau
- Consultation de la répartition des voix par le chef et les musiciens

**Rôles concernés :**

- Musiciens : indication de leur(s) voix
- Chef : attribution des partitions et consultation de la répartition

---

### F. Tâches

Chaque événement peut comporter des tâches organisationnelles (préparation de salle, montage d’un chapiteau, bar, vaisselle…).

**Fonctionnalités incluses :**

- Création de tâches par le comité
- Inscription libre des musiciens sur les tâches disponibles
- Rappels automatiques avant l’événement pour les personnes concernées

**Rôles concernés :**

- Membres du comité : création et suivi
- Musiciens : inscription

---

### G. Communication

Pour centraliser les échanges, Orchestrate intègre un système de messagerie.

**Fonctionnalités incluses :**

- Envoi de messages individuels ou groupés
- Notifications push pour les nouveaux messages

---

### H. Notifications et rappels

Le système de notifications garantit une communication fluide entre tous les membres.

**Fonctionnalités incluses :**

- Notifications pour les nouveaux événements
- Rappels automatiques avant une répétition ou un événement
- Notifications pour les nouveaux messages
- Alertes pour les tâches assignées ou à confirmer
- Rappel lors de l’oubli d’indication de présence / absence (par exemple, 3 jours avant l’événement)

---

### I. Paramètres et personnalisation

Orchestrate propose une interface adaptée aux besoins de chaque utilisateur.

**Fonctionnalités incluses :**

- Modification du profil personnel
- Sélection de la langue (FR/EN)
- Choix du thème (clair ou sombre)
- Choix des notifications
- Déconnexion et gestion du compte

---

### J. Rôles et permissions

Les fonctionnalités accessibles varient selon le rôle du membre.

| Rôle                   | Permissions principales                                                            |
|------------------------|------------------------------------------------------------------------------------|
| **Chef**               | Gérer les événements, consulter les présences, attribution et suivi des partitions |
| **Membre du comité**   | Gérer les tâches, membres, événements, communication                               |
| **Musicien**           | Consulter, indiquer sa présence, s’inscrire aux tâches, indiquer ses partitions    |
| **Créateur du groupe** | Crée et configure le groupe, attribue les rôles, gère les accès                    |

---

### K. Gamification et statistiques

La gamification vise à renforcer la motivation et l’engagement des musiciens.

**Objectifs :**

- valoriser les musiciens les plus impliqués
- encourager la régularité aux répétitions et événements
- créer une dynamique positive au sein de l’orchestre
- donner au chef une vision d’ensemble de l’assiduité et de la participation

**Fonctionnalités incluses :**

Côté musiciens :

- attribution automatique de points d’assiduité
- attribution de badges pour certains paliers
- visualisation de leur progression dans leur profil

Côté chef :

- Tableau de bord statistique affichant :
    - le taux de présence par répétition ou événement
    - le classement des musiciens selon leur assiduité
- Possibilité de réinitialiser les scores en début de période

**Rôles concernés :**

- Musiciens : participation, progression, badges
- Chef : consultation des statistiques, suivi des présences

---

### Récapitulatif

| Catégorie            | Description                                                                                       | Rôles concernés   |
|----------------------|---------------------------------------------------------------------------------------------------|-------------------|
| **Authentification** | Création de compte, connexion sécurisée, réinitialisation du mot de passe                         | Tous              |
| **Membres**          | Création et gestion d’un groupe, ajout/suppression de membres, attribution de rôles               | Comité            |
| **Rôles**            | Attribution de permissions spécifiques selon le rôle (chef, comité, musicien, créateur de groupe) | Tous              |
| **Événements**       | Création/modification/suppression d’événements, calendrier global, rappels automatiques           | Tous              |
| **Sondages**         | Proposition de plusieurs dates et vote des membres avant validation d’un événement                | Tous              |
| **Présences**        | Confirmation ou refus de présence, statistiques globales, rappels pour réponse manquante          | Musiciens, chef   |
| **Partitions**       | Attribution et consultation des voix                                                              | Musiciens, chef   |
| **Tâches**           | Création et attribution de tâches, inscription libre des membres, rappels automatiques            | Comité, musiciens |
| **Gamification**     | Attribution de points et badges selon l’assiduité et la participation                             | Musiciens         |
| **Statistiques**     | Tableau de bord global des présences et participation par répétition, événement ou musicien       | Chef              |
| **Communication**    | Envoi de messages individuels ou groupés                                                          | Tous              |
| **Partage média**    | Partage de photos et vidéos après un événement                                                    | Tous              |
| **Notifications**    | Alertes pour événements, messages, tâches ou rappels                                              | Tous              |
| **Paramètres**       | Modification du profil, langue, préférences de notifications, thèmes clair et sombre              | Tous              |
| **Multi-groupes**    | Possibilité de rejoindre plusieurs orchestres avec un seul compte                                 | Tous              |
