# Skill : Cristal des Schattenjägers

## Objectif

Tracer l'évolution du sixième diamant bleu à chaque porteur terrestre et identifier son détenteur, son état, ses pouvoirs cumulatifs et ses fragilités héritées à une époque donnée.

## Source de vérité

Le registre `../continuity/registre-sixieme-diamant.md` est la source opérationnelle pour toute possession, transition et empreinte. En cas de conflit, consulter ensuite `../bible/chronologie-generale.md`, `../continuity/tracking-objets.md` et `memoire-du-cristal.md`.

## Règles

- Le registre concerne exclusivement le sixième diamant bleu de la lignée terrestre.
- Chaque ligne de possession possède un début, une fin connue ou ouverte, un détenteur, une localisation et un statut de preuve.
- Une période sans détenteur identifié renvoie `INCONNU`, jamais un porteur inventé.
- Chaque Schattenjäger hérite de tous les pouvoirs et de toutes les fragilités inscrits avant lui dans le diamant.
- Chaque porteur découvre une aptitude unique, enracinée dans sa personnalité et ses actes ; elle s'ajoute aux pouvoirs antérieurs.
- Chaque aptitude unique imprime un défaut ou un coût durable. Cette fragilité s'ajoute au legs transmis et ne disparaît pas avec le porteur.
- Une nouvelle empreinte est cumulative : elle ne supprime aucun pouvoir ni aucune fragilité antérieure.
- Toute transmission exige une cause narrative, un itinéraire plausible et la validation de Danoë.
- Les cristaux des archanges, notamment le troisième diamant de Tomyris, sont hors périmètre.

## Fonctions

### `trouver_porteur_a_date(date, lieu=None)`
- **Entrées** : date historique normalisée, lieu facultatif.
- **Sorties** : détenteur ou statut `INCONNU`, localisation connue, intervalle de possession, statut historique et contradictions éventuelles.

### `tracer_transformation_cristal(porteur, evenement, date, pouvoir_unique, fragilite)`
- **Entrées** : porteur, événement, date, aptitude unique découverte, fragilité ou coût durable.
- **Sorties** : pouvoir et fragilité ajoutés, état du diamant, héritages cumulés et mise à jour requise du registre.

### `lister_empreintes_a_date(date)`
- **Entrées** : date historique normalisée.
- **Sorties** : ensemble cumulatif des pouvoirs et fragilités disponibles à cette date, avec leur porteur d'origine et leur niveau de certitude.

### `evaluer_heritage_cumulatif(candidat, date, enjeu)`
- **Entrées** : futur porteur, date, enjeu narratif et aptitudes personnelles.
- **Sorties** : pouvoirs hérités, fragilités héritées, pouvoir unique plausible, coût correspondant et garde-fous éthiques.

### `valider_transition_schattenjager(source, cible, date, itineraire)`
- **Entrées** : détenteur sortant, cible, date, itinéraire géographique, motif de transmission.
- **Sorties** : transition compatible, lacune à conserver ou contradiction canonique.

### `enregistrer_lacune(debut, fin, dernier_etat_connu)`
- **Entrées** : bornes de période, dernier détenteur et dernière localisation certains.
- **Sorties** : entrée `INCONNU` documentée, questions ouvertes et contraintes pour une future révélation.

## Propriétaires et validateurs
- **@memoire-des-lieux** (propriétaire du registre)
- **@danoe** (arbitrage canonique)
- **@histoire** (dates, routes et vraisemblance)
- **@suspens** (révélation contrôlée des périodes lacunaires)