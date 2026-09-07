# Workflow : Intégration de la gardienne Hélène

## Déclencheur

Utiliser ce workflow pour toute scène, annexe ou trace liée à Hélène, Constantin, la cour impériale, le pèlerinage palestinien ou aux traditions de reliques.

## Variables de contexte

- `HELENA_PERIOD=306_CE|324_CE|326_328_CE|327_330_CE`
- `HELENA_LOCATION=IMPERIAL_COUR|ROME|TRIER|PALESTINE`
- `HELENA_EVENT=RECALL|AUGUSTA|PILGRIMAGE|ARCHIVE|TRANSMISSION`
- `HELENA_SOURCE_STATUS=HISTORICAL|LATE_TRADITION|HAGIOGRAPHY|FICTION_CANONIQUE`
- `BLUE_DIAMOND_ID=6`

## Étapes

1. Danoë fixe l'enjeu : proximité du pouvoir, archive, relique ou transmission.
2. En parallèle, Histoire applique `qualifier_relique()` ; George applique `modeliser_proximite_imperiale()` ; Mémoire des Lieux applique `trouver_porteur_a_date()` ; Suspens définit la part d'incertitude.
3. Si une relique est mentionnée, la qualifier avant rédaction et ne pas en faire la cache du diamant.
4. Si Constantin ou Nicée apparaît, préserver l'agence des acteurs et les limites d'influence d'Hélène.
5. Si le diamant est transmis, appliquer `preserver_archive_discrete()` et `valider_transition_schattenjager()` vers une dépositaire anonyme.
6. Danoë rédige ; Histoire fournit les notes et le registre est mis à jour après validation humaine.