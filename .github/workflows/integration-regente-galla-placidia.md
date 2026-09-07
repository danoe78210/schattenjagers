# Workflow : Intégration de la régente Galla Placidia

## Déclencheur

Utiliser ce workflow pour toute scène liée à Galla Placidia, au sac de Rome, aux Wisigoths, à la régence occidentale ou au mausolée de Ravenne.

## Variables de contexte

- `GALLA_PERIOD=410_CE|414_415_CE|425_437_CE|450_CE`
- `GALLA_LOCATION=ROME|NARBONNE|RAVENNA|CONSTANTINOPLE`
- `GALLA_EVENT=CAPTIVITY|MARRIAGE|REGENCY|ARCHIVE|TRANSMISSION`
- `GALLA_SOURCE_STATUS=HISTORICAL|CONTESTED_ATTRIBUTION|FICTION_CANONIQUE`
- `BLUE_DIAMOND_ID=6`

## Étapes

1. Danoë fixe l'enjeu : survie, négociation, régence, mémoire ou compromis.
2. En parallèle, Histoire vérifie les dates ; George applique `cartographier_regence()` ; Mémoire des Lieux applique `trouver_porteur_a_date()` ; Suspens préserve les incertitudes.
3. Si le mausolée apparaît, le traiter comme monument associé à Galla et non comme cache prouvée du diamant.
4. Si le diamant est utilisé, appliquer `evaluer_consequence_decret()` ; il éclaire les effets humains sans imposer la décision.
5. Avant 450, appliquer `distribuer_memoire_administrative()` et `valider_transition_schattenjager()` vers une dépositaire anonyme.
6. Danoë rédige et le registre est actualisé après validation humaine.