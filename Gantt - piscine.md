# 📅 Planification du Projet – Construction de la Piscine

## 🔎 Données de départ

- **Date de lancement du chantier :** 12 février 2026  
- **Durée totale calculée (chemin critique) :** 50 jours ouvrés  

---

# 🛣️ Analyse du Réseau et Chemin Critique

Le planning comporte plusieurs branches parallèles qui convergent vers les phases finales du projet.

## 🔴 Chemin critique (durée maximale)

**A → F → G → D → E → J → K → M**

Durée totale :

5 + 6 + 5 + 8 + 9 + 6 + 8 + 3 = **50 jours**

➡ Ce chemin détermine la durée totale du projet.  
➡ Tout retard sur l’une de ces tâches entraîne automatiquement un retard global.

---

## 🟡 Branche secondaire – Canalisations

**A → B → C → D**

Durée jusqu’à D :

5 + 2 + 4 = 11 jours

Le chemin critique (A + F + G) atteint D au **jour 16**.

➡ Cette branche dispose donc d’une **marge de 5 jours**.

### 📌 En cas de retard de C (+6 jours)

Nouvelle durée de C = 10 jours  

5 + 2 + 10 = 17 jours

La tâche D ne pourrait alors démarrer qu’au **jour 17** au lieu de 16.

👉 **Conséquence : +1 jour sur la durée totale du projet.**  
La branche des canalisations devient alors le nouveau chemin critique.

---

## 🟡 Branche secondaire – Sonorisation

**G → H → I → J**

Durée cumulée :

4 + 5 = 9 jours

En parallèle, la branche critique (D + E) nécessite :

8 + 9 = 17 jours

➡ La sonorisation possède donc une **marge de 8 jours**.

### Conclusion

Supprimer la tâche I (5 jours) ne modifierait pas la date finale, car le dallage (J) doit attendre la fin de l’étanchéité (E).

---

# 📆 Comparaison des scénarios de travail

Durée totale : **50 jours ouvrés**

---

## Cas 1 : Travail du lundi au vendredi (5 jours/semaine)

Samedis et dimanches non travaillés.

| Mois | Jours travaillés | Cumul |
|------|------------------|--------|
| Février (du 12 au 28) | 12 jours | 12 |
| Mars | 22 jours | 34 |
| Avril | 16 jours restants | 50 |

**📌 Date de fin : Mercredi 22 avril 2026 (au soir)**

---

## Cas 2 : Travail du lundi au samedi (6 jours/semaine)

Seul le dimanche est chômé.

| Mois | Jours travaillés | Cumul |
|------|------------------|--------|
| Février (incluant samedis) | 15 jours | 15 |
| Mars | 26 jours | 41 |
| Avril | 9 jours restants | 50 |

**📌 Date de fin : Vendredi 10 avril 2026 (au soir)**

---

# 📝 Réponses aux Questions du PDF

## 1️⃣ Date de mise en eau

- **5 jours/semaine :** 22 avril 2026  
- **6 jours/semaine :** 10 avril 2026  

Dans les deux cas, la contrainte d’arrêt en août est respectée.

---

## 2️⃣ Impact du retard sur la tâche C

Oui, le retard impacte le délai global.

- Avant retard : D démarre au jour 16.
- Après retard : D démarre au jour 17.

➡ Le projet prend **1 jour de retard**, car la tâche D appartient au chemin critique.

---

## 3️⃣ Suppression de la sonorisation sous-marine

Supprimer la tâche I ne permettrait **aucun gain de temps**.

Elle dispose d’une marge de 8 jours et n’appartient pas au chemin critique.

✔ Cela peut réduire les coûts.  
❌ Cela n’accélère pas la livraison.

---

# 🎯 Synthèse Managériale

- Le projet dure **50 jours ouvrés**.
- Les tâches stratégiques à surveiller sont : **F, G et E**.
- Un retard sur les canalisations devient critique au-delà de 5 jours.
- Supprimer la sonorisation n’est pas une solution efficace pour gagner du délai.
