# Présentation : Kanban et Scrumban

## Introduction
L’objectif de cette présentation est d’expliquer le fonctionnement de la méthode Kanban dans un contexte réel d’équipe projet puis de montrer comment cette approche a évolué vers un modèle hybride appelé Scrumban.
Nous analyserons l’origine de la méthode  ses principes  son fonctionnement concret  ses forces et ses limites  avant d’établir une comparaison structurée avec Scrumban

---

# I. La méthode Kanban

## 1. Origine et contexte
La méthode Kanban trouve son origine dans les années 1950 au sein de l’entreprise Toyota Elle s’inscrit dans la philosophie du Lean Manufacturing, visant à optimiser les flux de production et à réduire les gaspillages.
Dans les années 2000, David J. Anderson adapte ces principes au développement logiciel et aux environnements de gestion de projet.

Kanban répond principalement aux problématiques suivantes
* Surcharge de travail 
* Accumulation de tâches en parallèle 
* Retards fréquents 
* Manque de visibilité sur l’avancement 
* Goulets d’étranglement non identifiés 

---

## 2. Principes fondamentaux
Kanban repose sur six pratiques principales
1. Visualiser le travail 
2. Limiter le travail en cours (WIP – Work In Progress) 
3. Gérer le flux 
4. Rendre explicites les règles du processus 
5. Mettre en place des boucles de feedback 
6. S’améliorer en continu 

La logique centrale est une logique de flux continu fondée sur un système « pull » (flux tiré) : une tâche n’entre dans le processus que lorsqu’il y a de la capacité disponible

---

## 3. Fonctionnement concret et Processus

### a) Le flux de travail : Du Backlog à la livraison
L’outil central est le tableau Kanban Contrairement aux idées reçues, il ne se limite pas à "À faire / En cours / Terminé". Pour refléter la réalité du processus, les étapes sont plus détaillées :
* **Backlog :** Le réservoir de toutes les demandes 
* **À faire (To Do) :** On "récupère" (pull) les tâches du backlog pour s'engager à les traiter.
* **En cours (Développement) :** L'action principale.
* **Revue (Code Review / QA) :** Étape de validation indispensable.
* **Terminé (Done).**

*(Ajouter un visuel : Image d'un tableau Kanban détaillé avec les colonnes Backlog, To Do, Dev, Review, Done)* 

### b) Les règles explicites : DoR et DoD
Pour fluidifier le passage d'une colonne à l'autre, on rend les règles explicites :
* **DoR (Definition of Ready) :** Les critères requis pour qu'une tâche puisse *entrer* dans une étape (ex: le ticket a une description claire avant de passer en "À faire").
* **DoD (Definition of Done) :** Les critères requis pour *terminer* une étape (ex: les tests sont validés avant de passer en "Revue").

### c) La limitation du WIP (Work In Progress)
Le WIP représente l'ensemble du travail en cours Son but principal est de **garantir la fluidité** et d'éviter les goulots d'étranglement.
* La limite est souvent calculée en fonction du nombre de personnes (ex: une limite de WIP globale ou par colonne de 3 tâches pour une équipe de 4 personnes).
* **Conséquence :** Si la limite est atteinte, l'équipe ne commence pas de nouvelle tâche. Les membres doivent s'entraider pour terminer ce qui est en cours, favorisant ainsi l'intelligence collective 

---

## 4. Artefacts, Indicateurs et Exemple concret

### a) Les indicateurs de flux (Métriques)
* **Lead Time :** temps total entre la demande et la livraison
* **Cycle Time :** temps nécessaire pour traiter une tâche une fois commencée.
* **Throughput (Débit) :** nombre d’éléments livrés sur une période donnée.
* **Diagramme de flux cumulatif (CFD) :** permet de visualiser les blocages instantanément.

### b) L'importance du Débit (Throughput) et la prévisibilité
* **Graphique 1 : Livraison non régulière.** Des pics et des creux. Signifie que le flux est bloqué puis relâché d'un coup. Difficile de faire des prévisions.
* **Graphique 2 : Livraison régulière.** Le rythme est constant. 

**Pourquoi c'est utile ?** Si on a un débit régulier (ex: 5 tâches par semaine) et un backlog de 20 tâches, on peut mathématiquement estimer la date d'arrivée du projet dans 4 semaines. Kanban permet donc une excellente prévisibilité.

*(Ajouter un visuel : Graphiques comparatifs de débit)* 

### c) Exemple d’application sur 2 semaines
*Ici, on illustre la vie d'une équipe sur une courte période* 39].
* **Semaine 1 :** 6 demandes dans le backlog. L'équipe respecte son WIP de 3, mais s'aperçoit que les tâches s'accumulent à l'étape "Revue". Le Cycle Time augmente.
* **Action :** L'équipe se réunit (boucle de feedback) et décide que les développeurs aideront temporairement à la revue pour débloquer la colonne.
* **Semaine 2 :** Retour à un flux régulier, amélioration du débit.

---

## 5. Forces et limites de Kanban

### Forces
* **Réactivité et Agilité :** Adaptation continue aux changements sans attendre la fin d'un cycle
* Mise en place sans rupture (on part de l'existant).
* Idéal pour la maintenance, le support et les flux continus
* Rend les blocages immédiatement visibles (grâce au WIP).

### Limites et Dérives 
* **Moins structurant que Scrum :** Pas de réunions imposées (planning, rétro), ce qui demande une **grande maturité et discipline** de l'équipe pour ne pas tomber dans l'anarchie
* La gestion fine des limites WIP est difficile à calibrer au début.

---

# II. Scrumban : le modèle hybride

## 1. Définition et origine
Scrumban apparaît vers 2008 pour aider les équipes Scrum qui souhaitent introduire plus de fluidité dans leur fonctionnement, souvent pour des projets complexes ou de maintenance.

## 2. Pourquoi Scrumban est apparu
Scrum vient combler certaines frustrations de Kanban :
* Sprints trop rigides pour intégrer des urgences.
* Effet "tunnel" ou surcharge de validations en toute fin de sprint.

## 3. Fonctionnement de Scrumban
Scrumban prend la structure de l'un et le moteur de l'autre :
* **De Scrum, il garde :** les rôles définis (PO, Scrum Master), un backlog priorisé, les cérémonies régulières (Daily, Rétrospective), et souvent une notion d'itération (planning à court terme) 
* **De Kanban, il intègre :** * **La limite de WIP au sein même du flux du sprint :** Cela empêche les développeurs de tout commencer en même temps en début de sprint.
  * **Le pilotage par le débit (Throughput) :** Au lieu d'utiliser uniquement les points d'effort (vélocité Scrum), l'équipe utilise son débit réel et régulier pour décider combien de tâches elle peut prendre.
  * **Planification "On-Demand" :** On ne planifie pas tout le sprint d'un coup, on tire de nouvelles tâches quand le WIP le permet.

---

# III. Comparaison structurée

*(Ce tableau répond à la consigne de comparer avec Scrum)* 

| Critère | Scrum | Kanban | Scrumban |
|----------|--------|----------|------------|
| **Cadence / Planification** | Sprints fixes et planifiés | Flux continu (On-Demand) | Mixte : cadence Scrum avec flux tiré à l'intérieur |
| **Limitation du WIP** | Indirecte (par la capacité du sprint) | Strictement Obligatoire | Obligatoire sur le tableau |
| **Rôles** | PO, Scrum Master, Développeurs | Non imposés (évolution de l'existant) | Rôles de Scrum généralement conservés |
| **Prévisibilité** | Basée sur la Vélocité (points) | Basée sur le Débit et le Cycle Time | Utilise souvent le Débit plutôt que la vélocité |

---

# IV. Contextes d’utilisation

* **Kanban est particulièrement adapté :** équipes de support, gestion/correction de bugs de production, flux de demandes imprévisibles, environnements très changeants
* **Scrumban est pertinent :** équipes Scrum souhaitant évoluer pour gérer des urgences, contextes avec interruptions fréquentes, ou transition progressive vers du pur Kanban.

---

# Conclusion

Kanban n'est pas qu'un tableau de post-its, c'est un système rigoureux centré sur l’optimisation du flux et la prévisibilité mathématique (grâce au débit). 
Scrumban constitue la passerelle idéale, permettant d’introduire ces puissantes mécaniques de flux dans un cadre Scrum rassurant.
Ces approches ne s’opposent pas ; elles sont complémentaires et répondent à des niveaux de maturité et des typologies de projets différents.

---

# V. Débat et Questions / Réponses

*(10 minutes prévues pour l'échange)* 

**Questions pour lancer le débat avec la classe :** 
1. D'après ce que nous avons vu sur la limite stricte du WIP, pensez-vous que Kanban serait adapté à un projet avec une date de livraison stricte et non négociable ? 
2. Pour ceux qui ont déjà fait des projets scolaires en groupe, quels problèmes le "WIP par personne" aurait-il pu vous éviter ? 
3. Lequel des deux modèles (Kanban ou Scrumban) vous semble le plus facile à mettre en place dans une entreprise très hiérarchisée et pourquoi ? 