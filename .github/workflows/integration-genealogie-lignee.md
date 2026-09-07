# Workflow : Intégration d'un noeud de généalogie

## Déclencheur

Utiliser ce workflow lorsqu'une page de généalogie, une frise éditoriale ou une archive propose un nouveau personnage, un rôle de Schattenjäger(in), un Gardien Ritter, un Archange ou un drame historique.

## Variables de contexte

- `GENEALOGY_SOURCE_URL`
- `GENEALOGY_NODE_NAME`
- `GENEALOGY_NODE_ROLE=SCHATTENJAGER|RITTER_GUARDIAN|ARCHANGEL|HISTORICAL_DRAMA`
- `GENEALOGY_PERIOD_START`
- `GENEALOGY_PERIOD_END`
- `GENEALOGY_SOURCE_STATUS=ATTESTED|DISPUTED|TRADITION|FICTION_CANONIQUE`
- `BLUE_DIAMOND_ID=6`

## Orchestration

1. Danoë lance `extraire_noeuds_genealogie()` et fixe le noeud à examiner.
2. En parallèle, Histoire applique `qualifier_noeud_historique()` ; Mémoire des Lieux applique `detecter_chevauchement_diamant()` ; George identifie les contraintes de pouvoir et de responsabilité ; Suspens estime ce qui doit rester une lacune.
3. Si `GENEALOGY_NODE_ROLE=SCHATTENJAGER`, alors Mémoire des Lieux exige une fenêtre sans chevauchement et une route plausible avant toute inscription au registre.
4. Si la source historique ne confirme pas une affirmation, alors Histoire la classe `TRADITION`, `DISPUTED` ou `FICTION_CANONIQUE` ; elle ne devient jamais un fait narratif implicite.
5. Si un chevauchement est détecté, alors Danoë choisit entre une fenêtre plus courte, un porteur anonyme ou le refus de l'intégration. La règle ne permet pas deux détenteurs du sixième diamant.
6. Après validation, Danoë appelle `modeliser_noeud_de_lignee()` et fixe aptitude, fragilité, limites et transmission.
7. Mémoire des Lieux appelle `synchroniser_genealogie()` : fiche personnage, registre, chronologie, index et tracking sont mis à jour ensemble.
8. Danoë réécrit la matière destinée au lecteur ; Histoire fournit les notes documentaires. Les agents spécialisés ne livrent pas de prose finale.

## Contrôles de sortie

- Le rôle annoncé par la source est distingué du rôle canonique retenu.
- Chaque possession du diamant est datée ou explicitement inconnue.
- Chaque aptitude est cumulative, limitée et associée à une fragilité.
- Les faits historiques ne sont pas gonflés par les besoins du récit.
