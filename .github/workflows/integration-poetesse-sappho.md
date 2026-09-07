# Workflow : Intégration de la poétesse Sapphô

## Déclencheur

Utiliser ce workflow pour toute scène, fiche, annexe ou indice lié à Sapphô, Lesbos, l'exil sicilien ou aux fragments poétiques.

## Variables de contexte

- `SAPPHO_PERIOD=CA_630_570_BCE|CA_600_BCE`
- `SAPPHO_LOCATION=MYTILENE|LESBOS|SICILY|IONIA`
- `SAPPHO_EVENT=COMPOSITION|EXILE|CIRCLE|TRANSMISSION|FRAGMENT_SURVIVAL`
- `BLUE_DIAMOND_ID=6`
- `SAPPHO_SOURCE_STATUS=ATTESTED|ANCIENT_TRADITION|SCHOLARLY_HYPOTHESIS|FICTION_CANONIQUE`
- `SAPPHO_SOURCE_URL=https://panodyssey.com/fr/article/fantaisie/sappho-la-voix-de-lesbos-7nkpvufsfhh7`

## Étapes

1. Danoë fixe la valeur en jeu : voix, désir, création, transmission ou effacement.
2. En parallèle, Histoire applique `qualifier_corpus()` ; Mémoire des Lieux applique `tracer_transmission_textuelle()` et `verifier_etat_diamant(6, date, porteur)` ; George examine les conflits civiques ; Suspens organise la survie d'un fragment.
3. Si un détail biographique n'est pas attesté, le classer comme tradition ancienne, hypothèse savante ou fiction-canonique avant rédaction.
4. Si un poème est cité, employer uniquement un texte du domaine public dont l'attribution et la traduction sont vérifiées, ou ne citer aucun vers.
5. Si le diamant est transmis, appliquer `tracer_transmission_diamant()` vers une dépositaire anonyme, jamais vers Cleïs comme fait établi.
6. Danoë rédige ; Histoire prépare la note documentaire et Mémoire des Lieux actualise les trackers après validation humaine.