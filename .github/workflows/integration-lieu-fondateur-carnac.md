# Workflow : Intégration d'un lieu fondateur — Carnac

## Déclencheur

Utiliser ce workflow lorsqu'une scène, un flashback, une annexe ou un indice relie Carnac au canon de Nunael.

## Variables de contexte

- `CARNAC_PERIOD=4500_BCE`
- `CARNAC_SITE=MENEC|KERMARIO|KERLESCAN|TUMULUS_SAINT_MICHEL`
- `CARNAC_NARRATIVE_MODE=SCENE|FLASHBACK|ANNEXE|MEMOIRE_DU_LIEU`
- `CARNAC_CANON_ROLE=GUIDANCE_NUNAEL|SCEAU|RELIQUE|HERITAGE`
- `CARNAC_HISTORICAL_STRICTNESS=STRICT|ROMANESQUE_ENCADRE`
- `CARNAC_SOURCE_URL=https://panodyssey.com/fr/article/fantaisie/les-pierres-de-carnac-7khr7fsdgfts`

## Étapes

1. **Cadrage** — Danoë précise l'objectif narratif, le lieu, l'époque et l'usage projeté.
2. **Validation canonique** — Danoë vérifie que l'élément proposé reste antérieur à la première Schattenjägerin, Hatchepsout.
3. **Recherche parallèle** :
   - Histoire applique `verifier_chronologie_carnac()` et `documenter_technologies_megalithiques()`.
   - Mémoire des Lieux applique `cartographier_lieux_rites()` et `suivre_permanence_lieu()`.
   - George applique `modeliser_dilemme_collectif()`.
   - Suspens applique `semer_murmures_antagonistes()`.
4. **Qualification** — Histoire applique `classifier_affirmations_site()`.
   - Si une donnée est une hypothèse archéologique, elle ne peut pas être présentée comme un fait dans une annexe.
   - Si une donnée est une décision fictionnelle, Danoë la consigne dans la fiche de continuité.
5. **Continuité de l'artefact** — Si le cristal vert est invoqué, Mémoire des Lieux applique `tracer_relique()` et vérifie sa compatibilité avec le statut `enfoui et non localisé`.
6. **Plan** — Danoë compose le plan de scène : objectif, conflit, ancrage sensoriel, value shift, chute.
7. **Rédaction et contrôle** — Danoë rédige ; Histoire fournit les notes documentaires ; Mémoire des Lieux met à jour les trackers après validation humaine.