# Skill : Cartographie du site sacré

## Objectif

Modéliser les lieux historiques qui reçoivent une fonction mythologique durable, sans confondre l'archéologie et le canon romanesque.

## Fonctions

### `cartographier_lieux_rites(site, donnees_historiques, canon)`
- **Entrées** : site, données archéologiques sourcées, éléments de canon proposés.
- **Sorties** : zones narratives, usages humains plausibles, fonctions surnaturelles, limites de représentation.

### `classifier_affirmations_site(affirmations)`
- **Entrées** : liste d'affirmations sur le site.
- **Sorties** : catégories `atteste`, `hypothese`, `legende`, `fiction-canonique` et action éditoriale recommandée.

### `ancrer_scene_dans_paysage(scene, site, periode)`
- **Entrées** : intention de scène, site, date.
- **Sorties** : contraintes spatiales, détails sensoriels plausibles, risques d'anachronisme.

## Propriétaire et validateurs
- **@memoire-des-lieux** (production)
- **@histoire** (validation archéologique)
- **@danoe** (validation narrative finale)

## Règle

Une fonction astronomique, rituelle ou sociale débattue doit rester une hypothèse dans l'appareil documentaire et peut devenir une vérité uniquement dans le plan fictionnel explicitement assumé.