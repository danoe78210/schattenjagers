# Workflow : Intégration de l'oratrice Aspasie

## Déclencheur

Utiliser ce workflow pour toute scène, fiche, annexe ou indice lié à Aspasie, Périclès, Athènes, la guerre du Péloponnèse ou au sixième diamant bleu.

## Variables de contexte

- `ASPASIA_PERIOD=CA_470_BCE|MID_440S_BCE|431_429_BCE|POST_429_BCE`
- `ASPASIA_LOCATION=MILETUS|PIRAEUS|ATHENS|ATTICA`
- `ASPASIA_EVENT=ARRIVAL|RELATION|DEBATE|CALUMNY|PLAGUE|TRANSMISSION`
- `ASPASIA_SOURCE_STATUS=ANCIENT_TESTIMONY|LITERARY_TRADITION|LATE_TRADITION|FICTION_CANONIQUE`
- `BLUE_DIAMOND_ID=6`
- `ASPASIA_SOURCE_URL=https://panodyssey.com/fr/article/fantaisie/aspasie-de-milet-la-corruptrice-amwt72dhvb45`

## Étapes

1. Danoë fixe l'enjeu : parole, réputation, rapport entre vérité et accusation, ou transmission.
2. En parallèle, Histoire applique `qualifier_influence_intellectuelle()` ; George applique `cartographier_calomnie()` ; Suspens construit les rumeurs ; Mémoire des Lieux applique `verifier_etat_diamant(6, date, porteur)`.
3. Si une source est comique, philosophique ou tardive, la classer avant rédaction et ne pas la convertir en fait biographique.
4. Si Périclès, Socrate ou Lysiclès apparaît, préserver son autonomie et l'incertitude du lien exact avec Aspasie.
5. Si le diamant est transmis, appliquer `transmettre_argumentation()` et `tracer_transmission_diamant()` vers une dépositaire anonyme quittant Athènes.
6. Danoë rédige ; Histoire prépare la note documentaire et les trackers sont mis à jour après validation humaine.