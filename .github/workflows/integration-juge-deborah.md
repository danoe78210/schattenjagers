# Workflow : Intégration de la juge Déborah

## Déclencheur

Utiliser ce workflow pour toute scène, fiche, annexe ou trace mémorielle liée à Déborah, Baraq, Yaël, Sisera ou au Cantique.

## Variables de contexte

- `DEBORAH_PERIOD=LATE_12TH_BCE|EARLY_11TH_BCE`
- `DEBORAH_LOCATION=EPHRAIM|RAMAH_BETHEL|KEDESH_NAPHTALI|MOUNT_TABOR|KISHON|JAEL_TENT`
- `DEBORAH_EVENT=JUDGMENT|SUMMONS|BATTLE|SISERA_DEATH|SONG|TRANSMISSION`
- `BLUE_DIAMOND_ID=6`
- `DEBORAH_SOURCE_STATUS=BIBLICAL_TRADITION|FICTION_CANONIQUE`
- `DEBORAH_SOURCE_URL=https://panodyssey.com/fr/article/fantaisie/deborah-l-abeille-d-ephraim-rdfqpjnsqn87`

## Étapes

1. Danoë définit la valeur en jeu : justice, courage, survie collective ou mémoire.
2. En parallèle, Histoire applique `qualifier_source_judiciaire()` ; George applique `modeliser_jugement_local()` ; Suspens planifie les indices ; Mémoire des Lieux applique `verifier_etat_diamant(6, date, porteur)`.
3. Si le récit utilise Juges 4-5, Histoire sépare le cadre textuel de ce qui est historiquement attesté.
4. Si l'Étranger intervient, appliquer `distinguer_influence_et_responsabilite()` : il amplifie peur, ambition ou rancune sans commander une décision ni provoquer un phénomène naturel.
5. Si Yaël apparaît, conserver son action autonome ; aucun artefact ne doit accomplir l'acte à sa place.
6. Si le Cantique est transmis, Suspens et Mémoire des Lieux appliquent `transmettre_memoire_orale()` et `tracer_transmission_diamant()`.
7. Danoë rédige, puis les trackers sont actualisés après validation humaine.