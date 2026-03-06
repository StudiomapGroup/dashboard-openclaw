# MVP Dashboard – README

Bienvenue sur le MVP Dashboard pilotage (markdown, version crash-proof et extensible) :

## Structure des fichiers
- **missions_du_jour.md** : Toutes les missions dues aujourd’hui (+ overdue), tri/priorité/heure
- **backlog.md** : Missions non planifiées, triables par catégorie/priorité/effort
- **now_working_on.md** : Carte “mission en cours” (focus principal actuel, 1 seule à la fois)
- **log_activites.md** : Journal complet : ajout/avancement, statuts, changements, tokens, etc.
- **analytics.md** : Statistiques : temps/statut, tokens consommés, ratio avancement/effort…

Mise à jour et log automatique à chaque action (cycle Dory-proof : tout passe par des fichiers crash-safe).

Les sections sont prêtes à être éditées, filtrées, dupliquées ou couplées plus tard à une UI web/mobile.

---

**Utilisation MVP** :
- Renseigne une mission (ex : ajout dans backlog.md, promotion en cours, modification d’état)
- Mets à jour avancement/tokens dans analytics.md à chaque étape
- Toute action/manip doit générer (aussi) une ligne dans log_activites.md
- Utilise now_working_on.md pour focus (toujours UNE mission active)

---

Prêt à l’emploi, tu peux ouvrir/modifier/exploiter ces fichiers sur n’importe quel éditeur markdown en local ou sur le VPS. On pourra automatiser/exporter en web ensuite rapidement.

---

Besoin d’aide sur le workflow ? Demande “mode d’emploi Dashboard” !
