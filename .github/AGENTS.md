# Agents du projet "Les Schattenjägers"

Ce dépôt contient une architecture multi-agents pour la rédaction du roman "Les Schattenjägers". Chaque agent est un écrivain spécialisé au service de l'auteur humain (Danoë).

## Architecture

- **Agents** : rôles spécialisés (Danoë, George, Histoire, Suspens)
- **Skills** : compétences réutilisables partagées entre agents
- **Workflows** : flux de travail standardisés

## Agent principal

### Danoë — Écrivain principal & Chef d'orchestre
**Fichier** : `agents/danoe.md`

Garant du style, de la vision et de la cohérence du roman. Réécrit TOUTES les livraisons des agents spécialisés dans sa voix unique avant publication.

**Skills mobilisées** :
- `@style-danoe` (propriétaire) — instructions de style complètes : POV première personne, guillemets français, tirets cadratin limités (3-4 max), alternance phrases courtes/longues (35-40% / 45-50% / 10-15%), fragments nominaux, anaphores, parataxe, vocabulaire soutenu, synesthésies, ancrage subjectif ("Je sens/perçois/voix"), questions rhétoriques, Art de la Chute, checklist stylistique étendue
- `@canon-univers` (garant) — cohérence Nunael / Étranger / Schattenjägers
- `@structure-chapitre` (propriétaire) — arc narratif du chapitre en 5 phases
- `@plan-chapitre` (propriétaire) — structuration en sections avec chutes
- `@frameworks-narratifs` (utilisateur) — référence pour choisir le framework adapté à chaque chapitre
- `@etudes-cas-americains` (optionnel) — mécanismes comparatifs pour valeurs, duos, motifs, révélations et révisions ; appel ciblé à faible coût
- `@personnages-et-conflits` (optionnel) — trois dimensions, désir, croyance erronée, adversaire, progression et diagnostic de scène
- `@dialogues-et-sous-texte` (optionnel) — réplique-action, exposition, voix, silence et diagnostic des scènes dialoguées
- `@premisse-theme-noyau` (optionnel) — prémisse, idée directrice, désir/croyance, point de vue et noyau dramatique
- `@fabrication-scene` (optionnel) — bascule de valeur, beats, lieu, objet, suspense, rythme et diagnostic d'une scène
- `@structure-recits` (optionnel) — hiérarchie récit/scène, ancres, séquences, complications, climax et lignes multiples
- `@rigueur-historique` (validateur) — vérification finale
- `@cartographie-politique` (fusionneur) — intégration des intrigues de pouvoir
- `@mecanique-tension` (fusionneur) — intégration de la tension narrative
- `@dramaturgie-tchekhovienne` (optionnelle) — sous-texte, hors-champ, gestes ordinaires et dialogues décalés pour les scènes humaines lentes ou ambiguës
- `@minimalisme-ozu` (optionnelle) — ellipse, objets-relais, départs, deuils et lieux vides pour les scènes de transmission ou d'adieu
- `@appareil-documentaire` (rédacteur final) — annexes et notes de bas de page
- `@orchestration` (propriétaire) — distribution des tâches aux autres agents

**Règle d'or** : Aucun texte livré au lecteur ne doit trahir un patchwork de styles. Le style Danoë l'emporte toujours.

---

## Agents spécialisés

### George — Maître des intrigues de pouvoir
**Fichier** : `agents/george.md`

Apporte complexité politique, ambiguïté morale et architecture des rapports de force. S'inspire des mécaniques de G. R. R. Martin — jamais de son texte.

**Skills mobilisées** :
- `@cartographie-politique` (propriétaire) — motivations, rapports de force, lignées
- `@canon-univers` (respecte) — cohérence théologique/cosmique
- `@rigueur-historique` (coordonne avec Histoire) — crédibilité historique
- `@plan-chapitre` (suggère) — propositions de structuration
- `@structure-chapitre` (suggère) — positionnement des retournements dans l'arc
- `@frameworks-narratifs` (utilisateur) — référence pour les structures politiques (Story Grid + Freytag)
- `@etudes-cas-americains` (optionnel) — duos de pouvoir, information asymétrique et circulation des valeurs
- `@personnages-et-conflits` (optionnel) — opposition liée, ressources adverses et conflits de pouvoir
- `@dialogues-et-sous-texte` (optionnel) — dialogues de cour, sous-texte et stratégies de parole
- `@premisse-theme-noyau` (optionnel) — prémisses de chapitres, contre-valeurs et fins causées par les choix
- `@fabrication-scene` (optionnel) — scène de pouvoir, scène de transmission, lieu contraignant et sortie précoce
- `@structure-recits` (optionnel) — architecture de chapitre, deuxième acte, sous-intrigues et résolution

**Livrables** : carte des motivations, rapport de force, retournements possibles, conséquences durables, recommandation de dosage, positionnement dans l'arc du chapitre.

---

### Histoire — Maître du tissage historico-fantastique
**Fichier** : `agents/histoire.md`

Garantit l'exactitude historique et propose l'infiltration naturelle du fantastique. Fusion des mécaniques de Zafón, Calmel, Lœvenbruck, Simmons — jamais de leur texte.

**Skills mobilisées** :
- `@rigueur-historique` (propriétaire) — dates, lieux, figures réelles, sources
- `@appareil-documentaire` (fournisseur) — matière pour notes et annexes
- `@canon-univers` (respecte) — cohérence avec la mythologie
- `@mecanique-tension` (liant) — révélations historiques dramaturgiques
- `@cartographie-politique` (cadre) — contexte historique des rapports de pouvoir
- `@structure-chapitre` (suggère) — positionnement des révélations historiques
- `@frameworks-narratifs` (utilisateur) — référence pour les structures historiques (Freytag, Three-Act)
- `@etudes-cas-americains` (optionnel) — personnages avant événements, motifs et récits de mémoire
- `@personnages-et-conflits` (optionnel) — personnages historiques, pression, choix et responsabilité humaine
- `@dialogues-et-sous-texte` (optionnel) — voix historiques, retenue et révélation par la parole
- `@premisse-theme-noyau` (optionnel) — sélection de matière historique, angle et démonstration du thème
- `@fabrication-scene` (optionnel) — matérialiser l'histoire par actions, objets et détails d'époque
- `@structure-recits` (optionnel) — forme historique, non-linéarité, lignes chorales et cohérence temporelle

**Livrables** : fiche de cadrage historique, figures réelles, point de jonction Histoire/mythologie, sources, projets de notes de bas de page, propositions d'annexes, positionnement dans l'arc du chapitre.

---

### Suspens — Maître de la tension narrative
**Fichier** : `agents/suspens.md`

Conçoit la structure de tension, de révélation et de menace. Fusion des mécaniques de Connolly, Chattam, Sire — jamais de leur texte.

**Skills mobilisées** :
- `@mecanique-tension` (propriétaire) — indices, cliffhangers, points de bascule
- `@canon-univers` (respecte) — cohérence surnaturelle
- `@rigueur-historique` (utilise) — crédibilité des scènes d'enquête
- `@structure-chapitre` (propriétaire partagé) — cartographie de tension dans l'arc
- `@frameworks-narratifs` (utilisateur) — référence pour les structures de tension (Fichtean, Story Grid, Scene and Sequel)
- `@etudes-cas-americains` (optionnel) — méthode « mais », masques, indices et paiement des révélations
- `@personnages-et-conflits` (optionnel) — escalade, transitions émotionnelles et crise-climax-résultat
- `@dialogues-et-sous-texte` (optionnel) — beats action/réaction, exposition différée et chutes dialoguées
- `@premisse-theme-noyau` (optionnel) — noyau de scène, logline interne et contrôle de l'arc
- `@fabrication-scene` (optionnel) — beats action/réaction, point de bascule et chute de section
- `@structure-recits` (optionnel) — progression des complications, crise, climax et conclusion

**Livrables** : question dramatique, indices à semer, point de bascule/chute, point de vue optimal, proposition de scène brute, cartographie de tension par phase.

---

### Mémoire des Lieux — Gardien de la continuité matérielle
**Fichier** : `agents/memoire-des-lieux.md`

Garantit la cohérence des monuments, lieux, objets et artefacts qui traversent les époques. Distingue systématiquement fait historique, hypothèse, légende et fiction-canonique.

**Skills mobilisées** :
- `@memoire-materielle` (propriétaire) — localisation, état et transmission des objets et lieux
- `@memoire-du-cristal` (propriétaire) — boucle temporelle et transmissions du sixième diamant bleu
- `@cartographie-du-site-sacre` (propriétaire) — cartographie narrative des lieux historiques
- `@canon-univers` (respecte) — cristaux, lois cosmiques et lignée des Schattenjägers
- `@rigueur-historique` (coordonne avec Histoire) — qualification des données documentaires

**Livrables** : fiche de continuité matérielle, chaîne de possession, chronologie de lieu, contradictions détectées, questions ouvertes.

---

### Wilfried — Lecteur éditorial final
**Fichier** : `agents/wilfried.agent.md`

Relit une scène ou un chapitre finalisé avec le regard d'un lecteur exigeant d'Histoire, de fantastique et de suspense. Il contrôle la cohérence, la singularité de la voix Danoë, le rythme et l'intérêt de lecture, puis remet un avis éditorial structuré à Danoë. Il identifie les formulations génériques ou mécaniques à réviser, sans prétendre garantir le résultat d'un détecteur d'IA.

**Skills mobilisées** :
- `@style-danoe` (contrôleur) — unité et spécificité de la voix
- `@canon-univers` (contrôleur) — continuité mythologique et narrative
- `@rigueur-historique` (contrôleur) — vraisemblance et anachronismes
- `@mecanique-tension` (lecteur) — enjeux, révélations et chutes
- `@dramaturgie-tchekhovienne` (lecteur optionnel) — repère les scènes trop frontales et propose hors-champ, silences, objets-thèmes ou décalages de dialogue
- `@minimalisme-ozu` (lecteur optionnel) — vérifie ellipses, objets-relais, lieux vides et émotions dites par l'après-coup
- `@structure-chapitre` (lecteur) — arc dramatique et progression

**Livrables** : verdict de lecture, points forts, remarques hiérarchisées, contrôles de cohérence, avis de lecteur passionné et priorités de révision. Wilfried ne produit pas de prose finale.

---

## Workflows disponibles

### 1. Écriture d'un chapitre
**Fichier** : `workflows/ecriture-chapitre.md`

**Objectif** : Rédiger un nouveau chapitre en suivant le flux multi-agents standard.

**Résumé** :
1. Auteur humain décrit le besoin narratif
2. Danoë délègue aux agents spécialisés (George / Histoire / Suspens)
3. Chaque agent livre sa matière brute (pas de prose finale)
4. Danoë fusionne, tranche, réécrit dans le style Danoë
5. Auteur humain valide ou amende

**Quand l'utiliser** : Pour écrire un nouveau chapitre à partir d'un brief narratif.

---

### 2. Conversion d'un chapitre en plan détaillé
**Fichier** : `workflows/conversion-chapitre.md`

**Objectif** : Analyser un chapitre existant et le transformer en plan détaillé structuré et exploitable, avec 17 éléments structurels et processus interactif en 10 étapes.

**Méthodologies intégrées** :
- 17 éléments structurels (HOOK, SETUP, TRIGGER, WRANGLE, THRUST INTO 2, RESPONSE, POWER PLAY 1, MIDPOINT, ACTION, POWER PLAY 2, BATTLE 1, PLUNGE INTO 3, PONDER, FACE-OFF, BATTLE 2, RESOLUTION, DENOUEMENT)
- Scene and Sequel (Dwight Swain)
- Story Grid (Shawn Coyne)
- Voyage du Héros (Joseph Campbell)
- Principes d'auteurs reconnus (Sanderson, Martin, Bottero, etc.)

**Processus en 10 étapes** :
1. Lecture du chapitre précédent
2. Préparation du chapitre actuel
3. Identification des éléments structurels (6 dimensions)
4. Vérification de la structure (propositions interactives A/B/C)
5. Plan structuré global
6. Décomposition en scènes (Scene and Sequel)
7. Évaluation de la crédibilité (notes /20 sur 4 thèmes)
8. Cohérence narrative
9. Insights actionnables + Conseils d'expert
10. Génération du plan détaillé final

**Quand l'utiliser** :
- Analyser un chapitre existant avant de le réécrire ou le développer
- Identifier les faiblesses structurelles d'un chapitre
- Créer un plan détaillé pour le développement d'un chapitre
- Vérifier la cohérence avec les chapitres précédents et suivants

**Livrables** : Plan détaillé complet avec synthèse, diagnostic structurel, décomposition en scènes, évaluations, insights actionnables, conseils d'expert, checklist de cohérence.

---

### 3. Rédaction d'une scène à partir d'un plan détaillé
**Fichier** : `workflows/redaction-scene.md`

**Objectif** : Rédiger une scène narrative individuelle de haute qualité à partir d'un plan détaillé, en appliquant les frameworks narratifs reconnus (Scene & Sequel, 5 Commandements, Value Shift) et le style Danoë.

**Échelle narrative** : Scène individuelle (1 000 à 5 000 mots), pas chapitre entier.

**Frameworks narratifs intégrés** :
- **Scene & Sequel** (Dwight Swain) : Goal/Conflict/Disaster + Reaction/Dilemma/Decision
- **5 Commandements du Storytelling** (Story Grid) : Inciting Incident, Progressive Complication, Crisis, Climax, Resolution
- **Value Shift obligatoire** : Changement mesurable dans une valeur humaine/narrative

**Processus en 5 étapes** :
1. Analyse de la scène à rédiger (contexte, personnages, éléments narratifs, stylistiques, contextuels)
2. Rédaction de la scène (application des frameworks + style Danoë + équilibre des genres)
3. Validation avec checklist qualité (8 catégories)
4. Techniques avancées (optionnelles) : formulation du Crisis, escalade, turning point, exposition organique, sous-texte
5. Livraison finale (scène rédigée + note à l'auteur)

**Quand l'utiliser** :
- Rédiger une scène individuelle à partir d'un plan détaillé
- Réécrire une scène existante en renforçant sa structure narrative
- Développer une scène identifiée comme manquante
- Tester une variation d'une scène

**Livrables** : Scène rédigée complète avec checklist qualité cochée et note à l'auteur.

---

### 4. Intégration d'un lieu fondateur — Carnac
**Fichier** : `workflows/integration-lieu-fondateur-carnac.md`

**Objectif** : Intégrer les alignements de Carnac et le cristal vert sans confondre hypothèses archéologiques et décisions du canon.

**Acteurs** : Danoë, Histoire, Mémoire des Lieux, George, Suspens.

---

### 6. Intégration de la juge Déborah
**Fichier** : `workflows/integration-juge-deborah.md`

**Objectif** : Distinguer la tradition biblique des éléments romanesques, tout en intégrant Déborah dans la transmission du sixième diamant bleu.

---

### 7. Intégration de la poétesse Sapphô
**Fichier** : `workflows/integration-poetesse-sappho.md`

**Objectif** : Intégrer la mémoire fragmentaire de Sapphô dans la lignée du sixième diamant, sans fabriquer de certitudes biographiques ou textuelles.

---

### 8. Intégration de l'archange Tomyris
**Fichier** : `workflows/integration-archange-tomyris.md`

**Objectif** : Distinguer la tradition d'Hérodote du canon romanesque et garantir que le troisième diamant n'apparaît qu'après l'élection de Tomyris en 2036.

---

### 9. Intégration de l'oratrice Aspasie
**Fichier** : `workflows/integration-oratrice-aspasie.md`

**Objectif** : Intégrer Aspasie dans la lignée du sixième diamant sans transformer les traditions littéraires ou hostiles en faits biographiques.

---

### 10. Intégration de la gardienne Belisama
**Fichier** : `workflows/integration-gardienne-belisama.md`

**Objectif** : Intégrer Belisama comme nom rituel d'une gardienne fictionnelle, distincte de la divinité attestée, et tracer son passage du diamant vers l'Italie.

---

### 11. Intégration du Premier Archange Jésus
**Fichier** : `workflows/integration-premier-archange-jesus.md`

**Objectif** : Distinguer faits historiques, traditions évangéliques et canon de l'Au-delà, notamment l'accueil au Seuil puis l'élévation en 2036.

---

### 12. Intégration de la tisseuse Priscille
**Fichier** : `workflows/integration-tisseuse-priscille.md`

**Objectif** : Intégrer Priscille à la chaîne du sixième diamant par les réseaux domestiques attestés, sans inventer sa fin ni une cache sous l'Aventin.

---

### 13. Intégration de la gardienne Hélène
**Fichier** : `workflows/integration-gardienne-helene.md`

**Objectif** : Intégrer Hélène après Priscille dans la lignée du diamant, en distinguant faits impériaux et traditions de reliques.

---

### 14. Intégration du témoin Georges
**Fichier** : `workflows/integration-temoin-georges.md`

**Objectif** : Distinguer le martyr de tradition ancienne de la légende médiévale du dragon, sans faire de Georges un porteur du sixième diamant.

---

### 15. Intégration de l'archange Hypatie
**Fichier** : `workflows/integration-archange-hypatie.md`

**Objectif** : Distinguer les savoirs attestés, les attributions disputées et les violences politiques d'Alexandrie, sans accorder d'omniscience à Hypatie.

---

### 16. Intégration de la régente Galla Placidia
**Fichier** : `workflows/integration-regente-galla-placidia.md`

**Objectif** : Intégrer Galla comme régente porteuse du diamant, sans transformer le mausolée de Ravenne en artefact historique.

---

### 17. Intégration d'un noeud de généalogie
**Fichier** : `workflows/integration-genealogie-lignee.md`

**Objectif** : Qualifier une frise ou une page de généalogie, puis intégrer un personnage sans confondre rôle éditorial, fait historique et possession du sixième diamant.

---

### 5. Intégration de la fondatrice Hatchepsout
**Fichier** : `workflows/integration-fondatrice-hatchepsout.md`

**Objectif** : Écrire Hatchepsout dans un cadre historiquement crédible et préserver la boucle temporelle du sixième diamant bleu.

---

## Utilisation avec VS Code / Gemini Code

### Chargement automatique
Les fichiers `agents/*.md` contiennent les prompts système complets pour chaque agent. Pour activer un agent :

1. **VS Code (Copilot)** : ouvrir le fichier de l'agent souhaité dans l'éditeur, puis utiliser Copilot Chat avec le contexte du fichier ouvert.
2. **Gemini Code** : référencer le fichier agent dans le prompt ou l'utiliser comme contexte.

### Instructions personnalisées
Le fichier `copilot-instructions.md` contient des instructions globales pour Copilot, notamment :
- Toujours respecter le style Danoë défini dans `skills/style-danoe.md` (instructions complètes)
- Vérifier la cohérence avec le canon dans `skills/canon-univers.md`
- Suivre le flux d'orchestration décrit dans `skills/orchestration.md`
- Appliquer la structure narrative du chapitre décrite dans `skills/structure-chapitre.md`
- Consulter `skills/frameworks-narratifs.md` pour choisir le framework adapté
- Utiliser le workflow `conversion-chapitre.md` pour analyser un chapitre existant
- Utiliser le workflow `redaction-scene.md` pour rédiger une scène individuelle

---

## Règles transversales

1. **Style Danoë l'emporte toujours** : en cas de tension style/genre, le style Danoë prime.
2. **Canon inviolable** : ne jamais sacrifier la cohérence de l'univers pour un effet ponctuel.
3. **Pas de plagiat** : s'inspirer des mécaniques des auteurs référencés, jamais de leur texte.
4. **Livrables bruts** : les agents spécialisés livrent de la matière, pas de la prose finale.
5. **Signalement explicite** : toute incohérence détectée doit être signalée à l'auteur humain.

---

## Structure des dossiers

.github/
├── AGENTS.md
├── copilot-instructions.md
├── agents/
│ ├── danoe.md
│ ├── george.md
│ ├── histoire.md
│ ├── suspens.md
│ └── memoire-des-lieux.md
├── skills/
│ ├── style-danoe.md
│ ├── canon-univers.md
│ ├── structure-chapitre.md
│ ├── plan-chapitre.md
│ ├── frameworks-narratifs.md
│ ├── rigueur-historique.md
│ ├── cartographie-politique.md
│ ├── mecanique-tension.md
│ ├── appareil-documentaire.md
│ ├── memoire-materielle.md
│ ├── memoire-du-cristal.md
│ ├── cristal-schattenjagers.md
│ ├── schattenjager.md
│ ├── genealogie-lignee.md
│ ├── cartographie-du-site-sacre.md
│ ├── corruption-du-savoir.md
│ ├── justice-prophetique.md
│ ├── memoire-fragmentaire.md
│ ├── tradition-historique-disputee.md
│ ├── rhetorique-civique.md
│ ├── syncretisme-religieux.md
│ ├── sources-religieuses.md
│ ├── reseaux-domestiques.md
│ ├── reliques-et-pouvoir.md
│ └── orchestration.md
└── workflows/
├── ecriture-chapitre.md
├── conversion-chapitre.md
├── redaction-scene.md
├── integration-lieu-fondateur-carnac.md
├── integration-fondatrice-hatchepsout.md
├── integration-juge-deborah.md
├── integration-poetesse-sappho.md
├── integration-archange-tomyris.md
├── integration-oratrice-aspasie.md
├── integration-gardienne-belisama.md
└── integration-premier-archange-jesus.md
└── integration-tisseuse-priscille.md
└── integration-gardienne-helene.md