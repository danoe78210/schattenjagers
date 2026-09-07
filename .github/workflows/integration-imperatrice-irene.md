# Workflow : Intégration de l'impératrice Irène l'Athénienne

## Déclencheur

Utiliser ce workflow pour toute scène, annexe ou analyse liée à Irène l'Athénienne, à Constantinople, à la crise iconoclaste, au deuxième concile de Nicée (787), au conflit avec Constantin VI ou au transfert du diamant vers la Northumbrie.

## Variables de contexte

- `IRENE_PERIOD=ATHENS_YOUTH|REGENCY_780_790|NICEA_787|SOLE_REIGN_797_802|EXILE_802_803`
- `IRENE_LOCATION=ATHENS|CONSTANTINOPLE|NICEA|LESBOS`
- `IRENE_EVENT=ICONOCLASM_CONFLICT|COUNCIL_OF_NICEA|CORRESPONDENCE_WEST|POWER_STRUGGLE|TRANSMISSION`
- `IRENE_SOURCE_STATUS=HISTORICAL_CHRONICLE|CONTESTED_ATTRIBUTION|FICTION_CANONIQUE`
- `BLUE_DIAMOND_ID=6`

## Orchestration

1. Danoë fixe l'enjeu narratif : sauvegarde de la beauté, restauration de la mémoire, résistance à l'effacement ou dérive du pouvoir politique.
2. En parallèle :
   - Histoire applique `qualifier_sources_byzantines()` et vérifie la chronologie du second concile de Nicée et du conflit iconoclaste.
   - George applique `cartographier_cour_byzantine()` pour modéliser la lutte de pouvoir entre régente, empereur, militaires iconoclastes et monastères studites.
   - Mémoire des Lieux applique `verifier_intervalle_diamant()` pour garantir la possession de 780 à 793 et la transmission vers la Northumbrie.
   - Suspens équilibre la tension dramatique sans transformer la mutilation de Constantin VI en ordre divin.
3. Si la crise iconoclaste apparaît, l'écrire comme conflit théologique et politique réel, amplifié par l'Étranger, et non comme un sortilège.
4. Si le transfert de 793 est abordé, rejeter la rencontre fictive à Parme en 781 ; utiliser le canal de correspondance monastique et la messagère northumbrienne vers Alcuin d'York.
5. Après validation, Danoë appelle `modeliser_noeud_de_lignee()` et fixe l'aptitude unique (*Discernement des visages*) et la fragilité transmise (*Ubris du pouvoir*).
6. Mémoire des Lieux synchronise les fichiers : fiche personnage, registre, chronologie générale et synthèses.
7. Danoë réécrit la prose finale dans le style Danoë.
