# Skill : Mémoire du cristal

## Objectif

Garantir la continuité temporelle, matérielle et mémorielle de chaque diamant bleu de l'Âge Premier.

## Règle du sixième diamant

En 2036, Nunael fracture le cristal bleu en sept diamants dans le Jardin. Le sixième est confié à la Chambre des Possibles, qui le dépose en 1473 av. J.-C. dans une carrière d'Assouan. Il traverse ensuite l'Histoire par transmission humaine : Hatchepsout, les prêtresses d'Hathor, puis les héritiers de la lignée jusqu'à Hildegarde. Cette boucle temporelle est unique et ne peut être modifiée sans décision explicite de Danoë.

## Fonctions

### `verifier_etat_diamant(numero, date, porteur)`
- **Entrées** : numéro du diamant, date de scène, porteur prévu.
- **Sorties** : état, localisation, détenteur compatible et conflit éventuel.

### `tracer_transmission_diamant(numero, depart, arrivee)`
- **Entrées** : numéro du diamant, porteur de départ, porteur d'arrivée, événement de passage.
- **Sorties** : chaîne de possession, savoir transmis, période lacunaire à documenter.

### `evaluer_manifestation_majeure(porteur, menace, cout)`
- **Entrées** : porteur, menace, effet recherché, coût proposé.
- **Sorties** : manifestation compatible, épuisement temporaire et séquelles sans destruction automatique.

## Propriétaire et validateurs
- **@memoire-des-lieux** (production)
- **@danoe** (validation canonique)
- **@histoire** (validation chronologique)