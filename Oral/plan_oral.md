# Présentation : Kanban et Scrumban

## Introduction

L’objectif de cette présentation est d’expliquer le fonctionnement de la méthode Kanban dans un contexte réel d’équipe projet,  
-------------SCRUM  
puis de montrer comment cette approche a évolué vers un modèle hybride appelé Scrumban.

Nous analyserons l’origine des méthodes, leurs principes, leur fonctionnements, leur forces et leur limites, avant d’établir une comparaison structurée entre les trois méthodes.

---

# I. La méthode Kanban

## 1. Origine et contexte

Le mot « Kanban » vient du japonais, il signifie « panneau ». La méthode est née dans les usines Toyota dans les années 1940, dans le cadre du Système de Production Toyota. Elle s’inscrit dans la philosophie du Lean Manufacturing, visant à optimiser les flux de production et à réduire les gaspillages. L'idée centrale : ne produire que ce qui est demandé, au moment où s’est demandé — on ne fabrique un article que lorsque le poste suivant en a besoin.

Dans les années 2000, David Anderson a adapté ce concept au développement logiciel, créant la « méthode Kanban » telle qu'on la connaît aujourd'hui.

Kanban répond principalement aux problématiques suivantes :

- surcharge de travail  
- accumulation de tâches en parallèle  
- retards fréquents  
- manque de visibilité sur l’avancement  
- goulets d’étranglement non identifiés  

---

## 2. Principes fondamentaux

Kanban repose sur six pratiques principales :

### 1. Visualiser le travail  
Toutes les tâches sont représentées sur un tableau divisé en colonnes, chaque colonne correspondant à une étape du processus.

### 2. Limiter le travail en cours (WIP – Work In Progress)  
On fixe un nombre maximum de tâches autorisées dans chaque colonne.

### 3. Gérer le flux  
L'objectif est que les cartes se déplacent de façon fluide et régulière à travers le tableau. On cherche à éviter les blocages et les files d'attente.

### 4. Rendre explicites les règles du processus  
Chaque colonne doit avoir une définition claire : quand est-ce qu'une tâche peut y entrer ? Quand peut-elle en sortir ? Ces règles évitent les ambiguïtés.

### 5. Mettre en place des boucles de feedback  
EXPLIQUER

### 6. S’améliorer en continu  
Kanban encourage l'équipe à analyser régulièrement ses performances et à améliorer son processus de façon incrémentale.

La logique centrale est une logique de flux continu fondée sur un système « pull » : une tâche n’entre dans le processus que lorsqu’il y a de la capacité disponible.

Kanban ne repose pas sur des itérations fixes, mais sur une optimisation permanente du temps de livraison.

---

## 3. Fonctionnement concret

### a) Le Kanban board

Lecture du tableau : Chaque carte représente une tâche. Elle commence à gauche avec « À faire », avance vers la droite au fur et à mesure de sa progression, et se retrouve dans « Terminé » une fois livrée.

L’outil central qu'est le tableau Kanban est structuré en colonnes représentant les étapes du processus :

- À faire  
- En cours (avec limite WIP)  
- En test  
- Terminé  

Chaque colonne peut comporter une limite de travail en cours. Lorsqu’une colonne atteint sa limite, aucune nouvelle tâche ne peut y entrer tant qu’une autre n’en est pas sortie.

Cette règle permet d’éviter la surcharge et de mettre en évidence les blocages.

-------------------SCHÉMA

---

### b) Les indicateurs de performance

Kanban repose sur des métriques centrées sur le flux :

- **Lead Time** : Durée totale entre le moment où une tâche est créée (demandée) et le moment où elle est livrée (terminée). C'est la métrique principale de Kanban.  
- **Cycle Time** : Durée entre le moment où une équipe commence à travailler sur une tâche et le moment où elle est terminée. Différent du Lead Time qui inclut aussi le temps d'attente initial.  
- **Throughput** : Nombre de tâches terminées par unité de temps (par exemple, 5 tâches par semaine). Indicateur de la productivité de l'équipe.  
- **Diagramme de flux cumulatif (Cumulative Flow Diagram)**  

Ces indicateurs permettent d’identifier les ralentissements et d’améliorer le processus.

--- 

## 4. Exemple concret d’application

Prenons l’exemple d’une équipe développant une application mobile.

### Semaine 1 :
- 6 demandes dans le backlog  
- Limite WIP fixée à 3  
- 2 fonctionnalités livrées  

Un blocage est identifié en phase de test. L’équipe décide alors d’ajuster la répartition des tâches pour fluidifier cette étape.

### Semaine 2 :
- Amélioration du cycle time  
- Diminution des tâches en attente  
- Meilleure anticipation des goulots d’étranglement  

Cet exemple illustre le principe d’amélioration continue propre à Kanban.

---

## 5. Forces et limites de Kanban

### Forces

- Simplicité de mise en place : pas de rôles ni de réunions imposées  
- Excellent pour les flux de travail continus (support, maintenance, opérations)  
- Visualisation immédiate de l'état du travail  
- Flexibilité totale : les priorités peuvent changer à tout moment  
- Permet d'identifier rapidement les blocages et goulots d'étranglement  

---------DEFINIR GOULOT D'ÉTRANGLEMENT

### Limites

- Moins adapté aux projets avec des délais fixes et des livrables définis à l'avance  
- Sans discipline, les limites WIP peuvent être ignorées, perdant l'effet bénéfique  
- Peu de structure pour la planification à long terme  
- Ne prévoit pas de rétrospective formelle (amélioration continue moins structurée)  

---

# II. Scrum

## 1. Qu'est-ce que c'est ?

Scrum est un cadre de travail, créé par Jeff Sutherland et Ken Schwaber dans les années 1990. Il organise le travail en cycles courts et répétables appelés « sprints », avec des rôles et des réunions bien définis.

---

## 2. Les 3 rôles de Scrum

- **Product Owner**  
Représente le client. Il définit les priorités et gère le Product Backlog.  

- **Scrum Master**  
Facilite le processus Scrum. Il retire les obstacles et protège l'équipe.  

- **Équipe de développement**  
Équipe auto-organisée qui réalise le travail. Généralement 3 à 9 personnes.

📌 **Product Owner (PO)** : Personne responsable de définir ce que l'équipe doit construire et dans quel ordre. Elle représente les intérêts des utilisateurs et du métier.  

📌 **Scrum Master (SM)** : Garant du bon déroulement du processus Scrum. Il aide l'équipe à s'améliorer et supprime les obstacles (blocages techniques, organisationnels…).

---

## 3. Les livrables de Scrum

- **Product Backlog** : Liste ordonnée de toutes les fonctionnalités, améliorations et corrections souhaitées pour le produit. C'est la « liste de courses » du projet, gérée par le Product Owner.

- **Sprint Backlog** : Liste des tâches que l'équipe s'engage à réaliser pendant un sprint donné. C'est un sous-ensemble du Product Backlog sélectionné en début de sprint.

- **Incrément** : Version fonctionnelle et potentiellement livrable du produit, produite à la fin de chaque sprint. Chaque incrément s'ajoute aux précédents.

- **User Story** : Description courte d'une fonctionnalité du point de vue de l'utilisateur. Format standard :  
« En tant que [rôle], je veux [action] afin de [bénéfice] ».

- **Points d'histoire (Story Points)** : Unité de mesure abstraite représentant la complexité d'une tâche, et non sa durée. L'équipe vote ensemble pour estimer chaque tâche.

---

## 4. Avantages et limites de Scrum

### ✅ Avantages

- Structure claire avec rôles, réunions et livrables bien définis  
- Livraison régulière de valeur à chaque sprint  
- Forte implication des parties prenantes via les Sprint Reviews  
- Amélioration continue intégrée via les rétrospectives  
- Excellent pour les projets avec des objectifs évolutifs mais des délais définis  

### ⚠️ Limites

- Lourdeur des cérémonies pour les petites équipes ou projets simples  
- Difficile d'intégrer des tâches urgentes en cours de sprint  
- Nécessite une bonne maîtrise de la méthode (risque de « Scrum Theater »)  
- Estimation en story points difficile à appréhender au début  

📌 **Scrum Theater** : Situation où une équipe applique les rituels de Scrum en surface (réunions, sprints…) sans en comprendre l'esprit, sans bénéficier réellement de la méthode.

---

# III. Scrumban : le modèle hybride

## 1. Définition et origine

Scrumban est une méthode hybride combinant la structure des sprints et des rôles de Scrum avec la visualisation et les limites WIP de Kanban. Elle offre flexibilité et prévisibilité.

Le Scrumban est apparu en 2008, popularisé par Corey Ladas dans son livre « Scrumban ». Il est né d'un besoin réel : permettre aux équipes pratiquant Scrum de migrer progressivement vers Kanban, ou à l'inverse, d'ajouter de la structure à leur Kanban.

---

## 2. Comment fonctionne Scrumban ?

### Ce que Scrumban emprunte à Scrum

- Des itérations (sprints) optionnelles ou raccourcies pour cadencer le travail  
- La planification périodique des priorités  
- Les rétrospectives pour l'amélioration continue  
- Un backlog priorisé de tâches  

### Ce que Scrumban emprunte à Kanban

- Un tableau visuel avec colonnes et cartes  
- Des limites WIP sur les colonnes (optionnel mais recommandé)  
- Un flux de travail continu : pas besoin d'attendre la fin d'un sprint pour livrer  
- La méthode du flux tiré : on commence une nouvelle tâche quand de la capacité est disponible  

📌 **Flux tiré (Pull System)** : Système où une nouvelle tâche n'est démarrée que lorsque l'équipe a de la capacité disponible (une case se libère). Opposé au flux poussé où on assigne le travail de l'extérieur.

---

## 3. La planification à la demande

L'une des caractéristiques clés du Scrumban est la planification déclenchée par le niveau de remplissage du backlog actif, plutôt qu'à date fixe.

⚡ **Règle de déclenchement de la planification**

En Scrumban, la réunion de planification est déclenchée quand le nombre de tâches disponibles dans le backlog tombe en dessous d'un seuil défini (ex. : moins de 3 tâches restantes). On ne planifie que lorsque c'est nécessaire.

Exemple : si votre équipe fixe le seuil à 5 tâches et que le backlog actif n'en a plus que 4, une réunion de planification est automatiquement convoquée.

---

## 4. Le tableau Scrumban

Le tableau Scrumban est plus élaboré qu'un tableau Kanban simple, car il intègre une zone « prête » (ready) qui joue le rôle du Sprint Backlog :

| BACKLOG   | PRÊT      | ANALYSE     | DEV      | TEST     | LIVRÉ        | BLOQUÉ     |
|------------|------------|--------------|----------|----------|--------------|------------|
| Feature B  | Feature A  | Bug fix #3   | Login UI | Paiement | Page accueil |            |
| Feature C  | Feature D  |              |          | API test |              | DB connect |
| Feature E  |            |              |          |          |              |            |


La colonne « Prêt » contient les tâches prioritaires sélectionnées et prêtes à être développées — l'équivalent du Sprint Backlog en Scrum. La colonne « Bloqué » signale les tâches qui ne peuvent pas avancer pour une raison externe.

---

## 5. Avantage et limites de Scrumban

### ✅ Avantages

- Idéal pour une transition progressive entre Scrum et Kanban  
- Flexibilité accrue par rapport à Scrum pur  
- Maintient une structure suffisante pour éviter le chaos  
- Adapté aux équipes avec à la fois des projets planifiés et des demandes urgentes imprévues  
- Favorise la livraison continue sans sacrifier la vision long terme  

### ⚠️ Limites

- Moins standardisé : peut créer de la confusion si les règles ne sont pas clarifiées  
- Nécessite une équipe mature qui comprend bien les deux méthodes parents  
- Risque de « cherry-picking » : prendre le mauvais de chaque méthode plutôt que le bon  
- Moins de littérature et de certifications disponibles  

---

# IV. Comparatif

## Tableau récapitulatif

| Critère | Kanban | Scrum | Scrumban |
|----------|---------|--------|-----------|
| Itérations | Non (flux continu) | Oui (sprints) | Optionnel |
| Rôles définis | Non | Oui (PO, SM, Dev) | Minimal |
| Réunions imposées | Non | Oui (Daily, Retro…) | Légères |
| Limite en-cours (WIP) | Oui (obligatoire) | Non | Oui |
| Changements en cours | Autorisés | Non (attendre sprint) | Partiellement |
| Planification | Au fil de l'eau | Par sprint | Périodique |
| Mesuré par | Lead time, WIP | Vélocité | Les deux |
| Idéal pour | Support, ops, flux | Projets structurés | Transition, hybride |

---

## 1. Comment choisir ?

### 🗂️ Choisissez Kanban si…

- Votre travail est imprévisible  
- Vous gérez un flux continu  
- Pas de délai fixe  
- Équipe support / ops  

### 🏃 Choisissez Scrum si…

- Projet avec délais définis  
- Besoin de structure forte  
- Équipe dédiée au projet  
- Livraisons régulières prévues  

### 🔀 Choisissez Scrumban si…

- Mélange de projets et flux  
- Transition entre méthodes  
- Flexibilité + structure  
- Équipe expérimentée  

---

# V. Contextes d’utilisation

### Kanban est particulièrement adapté :

- aux équipes de support  
- aux environnements instables  
- aux projets avec flux continu de demandes  

### Scrumban est pertinent :

- pour des équipes Scrum souhaitant évoluer  
- dans des contextes avec interruptions fréquentes  
- lorsqu’un équilibre entre cadre et flexibilité est nécessaire  

---

# Conclusion

Kanban est une méthode centrée sur l’optimisation du flux et la limitation du travail en cours. Elle offre une grande flexibilité et favorise l’amélioration continue.

Scrumban constitue une évolution hybride permettant d’introduire les pratiques Kanban dans un cadre Scrum existant.

Ces approches ne s’opposent pas ; elles répondent à des besoins organisationnels différents et peuvent être complémentaires selon le contexte du projet.