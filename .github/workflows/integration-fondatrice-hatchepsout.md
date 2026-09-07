# Workflow : Intégration de la fondatrice Hatchepsout

## Déclencheur

Utiliser ce workflow pour toute scène, annexe, fiche ou indice lié à Hatchepsout, aux prêtresses d'Hathor ou au sixième diamant bleu.

## Variables de contexte

- `HATCHEPSOUT_PERIOD=1479_BCE|1473_BCE|1470_BCE|1463_BCE|1458_BCE|1430_BCE`
- `HATCHEPSOUT_LOCATION=THEBES|KARNAK|ASSOUAN|POUNT|DEIR_EL_BAHARI`
- `HATCHEPSOUT_EVENT=REGENCE|INVESTITURE|EXPEDITION|CONSTRUCTION|TRANSMISSION|EFFACEMENT`
- `BLUE_DIAMOND_ID=6`
- `BLUE_DIAMOND_STATE=DEPOSE|PORTE|EPUISE|TRANSMIS`
- `HISTORICAL_STRICTNESS=STRICT|ROMANESQUE_ENCADRE`

## Étapes

1. Danoë fixe l'enjeu de scène et applique `verifier_etat_diamant(6, date, porteur)`.
2. En parallèle, Histoire vérifie le contexte de la XVIIIe dynastie ; George cartographie la crise de succession ; Suspens organise les indices et Mémoire des Lieux trace l'état du diamant.
3. Si une scène concerne l'investiture de 1473 av. J.-C., Hatchepsout agit comme corégente devenue pharaon, sans évincer rétroactivement Thoutmôsis III.
4. Si la pleine puissance du diamant est sollicitée, appliquer `evaluer_manifestation_majeure()` : épuisement temporaire et séquelle, jamais rupture automatique.
5. Si l'effacement est évoqué, le situer après la mort d'Hatchepsout et distinguer les motifs historiques débattus de l'action canonique de l'Étranger.
6. Danoë rédige ; les trackers sont mis à jour après validation humaine.