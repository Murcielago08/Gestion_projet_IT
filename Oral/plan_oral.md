# Présentation : Kanban et Scrumban

## Introduction

L’objectif de cette présentation est d’expliquer le fonctionnement de la méthode Kanban dans un contexte réel d’équipe projet, puis de montrer comment cette approche a évolué vers un modèle hybride appelé Scrumban.

Nous analyserons l’origine de la méthode, ses principes, son fonctionnement concret, ses forces et ses limites, avant d’établir une comparaison structurée avec Scrumban.

---

# I. La méthode Kanban

## 1. Origine et contexte

La méthode Kanban trouve son origine dans les années 1950 au sein de l’entreprise Toyota. Elle s’inscrit dans la philosophie du Lean Manufacturing, visant à optimiser les flux de production et à réduire les gaspillages.

Dans les années 2000, David J. Anderson adapte ces principes au développement logiciel et aux environnements de gestion de projet.

Kanban répond principalement aux problématiques suivantes :

- surcharge de travail  
- accumulation de tâches en parallèle  
- retards fréquents  
- manque de visibilité sur l’avancement  
- goulets d’étranglement non identifiés  

---

## 2. Principes fondamentaux

Kanban repose sur six pratiques principales :

1. Visualiser le travail  
2. Limiter le travail en cours (WIP – Work In Progress)  
3. Gérer le flux  
4. Rendre explicites les règles du processus  
5. Mettre en place des boucles de feedback  
6. S’améliorer en continu  

La logique centrale est une logique de flux continu fondée sur un système « pull » : une tâche n’entre dans le processus que lorsqu’il y a de la capacité disponible.

Kanban ne repose pas sur des itérations fixes, mais sur une optimisation permanente du temps de livraison.

---

## 3. Fonctionnement concret

### a) Le Kanban board

L’outil central est le tableau Kanban, généralement structuré en colonnes représentant les étapes du processus, par exemple :

- À faire  
- En cours (avec limite WIP)  
- En test  
- Terminé  

Chaque colonne peut comporter une limite de travail en cours. Lorsqu’une colonne atteint sa limite, aucune nouvelle tâche ne peut y entrer tant qu’une autre n’en est pas sortie.

Cette règle permet d’éviter la surcharge et de mettre en évidence les blocages.

---

### b) Les indicateurs de performance

Kanban repose sur des métriques centrées sur le flux :

- Lead Time : temps total entre la demande et la livraison  
- Cycle Time : temps nécessaire pour traiter une tâche une fois commencée  
- Throughput : nombre d’éléments livrés sur une période donnée  
- Diagramme de flux cumulatif (Cumulative Flow Diagram)  

Ces indicateurs permettent d’identifier les ralentissements et d’améliorer le processus.

---

## 4. Exemple concret d’application

Prenons l’exemple d’une équipe développant une application mobile.

Semaine 1 :
- 6 demandes dans le backlog  
- Limite WIP fixée à 3  
- 2 fonctionnalités livrées  

Un blocage est identifié en phase de test. L’équipe décide alors d’ajuster la répartition des tâches pour fluidifier cette étape.

Semaine 2 :
- Amélioration du cycle time  
- Diminution des tâches en attente  
- Meilleure anticipation des goulots d’étranglement  

Cet exemple illustre le principe d’amélioration continue propre à Kanban.

---

## 5. Forces et limites de Kanban

### Forces

- Grande flexibilité (revoir le therme)
- Adaptation facile à l’organisation existante  
- Idéal pour les activités de maintenance et de support  
- Amélioration progressive sans transformation brutale  
- Rapididté de feedback

### Différence entre les autres framework

- Moins structurant que d’autres frameworks(vraiment une limite ?)
- Absence de cadre temporel fixe (pas de cycle en V)
- Une discipline sur les limites WIP  

---

# II. Scrumban : le modèle hybride

## 1. Définition et origine

Scrumban est une approche hybride combinant les principes de Scrum et de Kanban.

Il apparaît vers 2008 lorsque certaines équipes Scrum souhaitent introduire plus de flexibilité dans leur fonctionnement.

---

## 2. Pourquoi Scrumban est apparu

Certaines équipes Scrum rencontrent les difficultés suivantes :

- rigidité des sprints  
- difficulté à intégrer des urgences  
- surcharge en fin de sprint  
- multiplication des cérémonies  

Kanban apporte des solutions centrées sur la gestion du flux et la limitation du travail en cours. Scrumban permet donc d’introduire ces mécanismes sans abandonner complètement la structure Scrum.

---

## 3. Fonctionnement de Scrumban

Scrumban conserve généralement :

- un backlog priorisé  
- des rôles définis (Product Owner, équipe)  
- des réunions régulières  
- Temporalité de sprints

Il introduit :

- des limites WIP  
- un pilotage par les métriques de flux  
- une plus grande flexibilité dans l’introduction des tâches  
- des itérations parfois assouplies ou supprimées  

Scrumban représente donc une transition entre un cadre structuré et un modèle orienté flux continu.

---

# III. Comparaison structurée

| Critère | Scrum | Kanban | Scrumban |
|----------|--------|----------|------------|
| Organisation du travail | Sprints fixes | Flux continu | Objectif de livraison de valeur |
| Limitation du WIP | Non obligatoire | Obligatoire | Obligatoire |
| Rôles définis | Oui | Non imposés | Oui |
| Gestion des urgences | Complexe en cours de sprint | Flexible | Plus flexible |

Kanban privilégie l’optimisation du flux.  
Scrum privilégie la structure itérative.  
Scrumban cherche un équilibre entre les deux.

---

# IV. Contextes d’utilisation

### Kanban est particulièrement adapté :

- aux équipes de support gestion correction bug Prod
- aux environnements instables  
- aux projets avec flux continu de demandes  

### Scrumban est pertinent :

- pour des équipes Scrum souhaitant évoluer  
- dans des contextes complexe/avec interruptions fréquentes  
- lorsqu’un équilibre entre cadre et flexibilité est nécessaire  

---

# Conclusion

Kanban est une méthode centrée sur l’optimisation du flux et la limitation du travail en cours. Elle offre une grande flexibilité et favorise l’amélioration continue.

Scrumban constitue une évolution hybride permettant d’introduire les pratiques Kanban dans un cadre Scrum existant.

Ces approches ne s’opposent pas ; elles répondent à des besoins organisationnels différents et peuvent être complémentaires selon le contexte du projet.