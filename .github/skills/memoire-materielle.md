# Skill : Mémoire matérielle

## Objectif

Assurer la continuité des lieux, artefacts et objets-signaux qui traversent plusieurs époques de la saga.

## Fonctions

### `tracer_relique(objet, evenement)`
- **Entrées** : identité de l'objet, date, lieu, détenteur, état, événement narratif.
- **Sorties** : chaîne de possession, état mis à jour, conflits de continuité, questions ouvertes.

### `suivre_permanence_lieu(site, periodes)`
- **Entrées** : site, jalons chronologiques, transformations connues.
- **Sorties** : chronologie du lieu, éléments permanents, usages successifs, transitions à justifier.

### `verifier_transition_materielle(depart, arrivee)`
- **Entrées** : état antérieur et état projeté d'un objet ou lieu.
- **Sorties** : transition valide, causalité manquante ou contradiction canonique.

## Propriétaire et validateurs
- **@memoire-des-lieux** (production)
- **@histoire** (validation historique)
- **@danoe** (validation canonique finale)

## Checklist
- [ ] La localisation est-elle connue ou explicitement inconnue ?
- [ ] Chaque changement d'état possède-t-il une date et une cause ?
- [ ] La transmission respecte-t-elle la chronologie du canon ?
- [ ] Le statut historique du lieu est-il séparé de sa fonction romanesque ?