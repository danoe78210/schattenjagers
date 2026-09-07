# Workflow : Intégration du témoin Georges

## Déclencheur

Utiliser ce workflow pour toute scène liée à Georges, au martyre chrétien, à la légende du dragon ou à la transformation d'un souvenir de résistance en récit de conquête.

## Variables de contexte

- `GEORGE_PERIOD=LATE_3RD_CE|EARLY_4TH_CE|MEDIEVAL_LEGEND`
- `GEORGE_LOCATION=CAPPADOCIA_TRADITION|LYDDA_TRADITION|NICOMEDIA_TRADITION`
- `GEORGE_EVENT=CONSCIENCE|MARTYR_TRADITION|LEGEND_TRANSFORMATION`
- `GEORGE_SOURCE_STATUS=EARLY_TRADITION|LATE_HAGIOGRAPHY|MEDIEVAL_LEGEND|FICTION_CANONIQUE`
- `GEORGE_CRYSTAL_STATUS=NO_POSSESSION`

## Étapes

1. Danoë fixe l'enjeu : courage, témoin, mémoire déformée ou refus d'un ordre.
2. Histoire applique `qualifier_tradition()` et `qualifier_tradition_religieuse()` ; George cartographie le coût du refus ; Suspens décide quelle part de la légende reste hors champ.
3. Si le dragon apparaît, le traiter comme tradition médiévale ou métaphore canonique, jamais comme un fait antique.
4. Vérifier avec `trouver_porteur_a_date()` que Georges ne reçoit pas le sixième diamant.
5. Danoë rédige et consigne toute nouvelle interprétation dans le journal de continuité.