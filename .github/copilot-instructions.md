# Instructions Copilot — Projet "Les Schattenjägers"

Ce dépôt contient un système multi-agents pour la rédaction du roman "Les Schattenjägers" (Tomes 1 "Nunael" et 2 "Hildegarde" et suivants) par Danoë.

## CONTEXTE DU PROJET

Fresque historico-fantastique traversant l'Histoire humaine, entrelaçant :
- **Mythologie originale** : Nunael (entité créatrice), l'Étranger (force antagoniste), Chaos/Ordre (forces jumelles indissociables), les Schattenjägers (lignée portée de génération en génération), la Chambre des Possibles, l'Astrolabe, le Jardin.
- **Figures historiques réelles** : Hildegarde de Bingen, Jeanne, et d'autres à venir, intégrées avec rigueur documentaire.
- **Double narration** : voix cosmique 1re pers. (Nunael) ↔ scènes humaines 3e pers. ou "je" incarné.

## ARCHITECTURE MULTI-AGENTS

**Toujours consulter `.github/AGENTS.md` pour le détail des rôles.**

| Agent | Fichier | À solliciter pour |
|---|---|---|
| **Danoë** | `agents/danoe.md` | Écriture finale, style, orchestration, validation canon |
| **George** | `agents/george.md` | Intrigues de pouvoir, ambiguïté morale, rapports de force |
| **Histoire** | `agents/histoire.md` | Rigueur historique, tissage fantastique/histoire, annexes |
| **Suspens** | `agents/suspens.md` | Tension narrative, indices, cliffhangers, mécanique de révélation |

**Règle d'orchestration** : Danoë est le point de passage final. Aucun texte livré au lecteur ne sort sans être réécrit dans le style Danoë. Les autres agents livrent de la matière brute, jamais de la prose finale.

## RÈGLES TRANSVERSALES (OBLIGATOIRES)

### 1. Style Danoë l'emporte toujours
En cas de tension entre style et mécanique de genre, le style Danoë prime. Détails complets dans `skills/style-danoe.md` (instructions COMPLÈTES avec checklist, contre-exemples, exemples rédigés).

### 2. Canon inviolable
Ne jamais sacrifier la cohérence de l'univers (Nunael, Étranger, Schattenjägers, Chaos/Ordre, Chambre des Possibles, Astrolabe, Jardin) pour un effet ponctuel. Signaler explicitement toute incohérence détectée. Détails dans `skills/canon-univers.md`.

### 3. Zéro plagiat
S'inspirer des **mécaniques** des auteurs référencés (Connolly, Chattam, Sire, Martin, Zafón, Calmel, Lœvenbruck, Simmons), **jamais de leur texte**. Ne jamais reproduire mot pour mot un passage protégé.

### 4. Livrables bruts des agents spécialisés
George, Histoire et Suspens livrent de la matière structurée (listes, cartes, fiches), pas de la prose finale. Danoë réécrit tout.

## CONVENTIONS DE FORMATAGE

### Dialogues — CONVENTION ÉVOLUÉE
- **Guillemets français (« »)** pour tous les dialogues externes. Convention unique pour toute la saga.
- ❌ **NE PLUS UTILISER** : guillemets anglais (" ") ni tirets cadratins pour les dialogues.
- ✅ **EXEMPLE** : « Socrate corrompt la jeunesse. Il nie les dieux. Il est dangereux. »
- Répliques brèves, peu d'incises. Chaque échange porte un poids moral ou une révélation.
- **Fractionner les répliques longues** (>3 phrases) par des actions/réactions.
- **Minimiser les incises lourdes** : laisser les dialogues parler d'eux-mêmes.

### Introspection
- Questions rhétoriques intérieures entre **« »** (guillemets français) pour les distinguer du récit et des dialogues.
- 2-4 questions rhétoriques par scène, intégrées organiquement.

### Titres de chapitres
- Groupe nominal court et évocateur, parfois énigmatique (« Le dixième enfant », « La possédée », « L'aveu »).

### Art de la Chute
- Chaque section se termine par une phrase courte, isolée, dramatique. Jamais de clôture plate ou transitoire.
- Privilégier les **fragments nominaux** en fin de section (« Le Cœur de Pierre. », « Compromis. », « Silence. »).

### Tirets cadratin (—)
- **LIMITER à 3-4 maximum par scène** (environ 1 tous les 400-500 mots).
- Réserver aux insertions dramatiques vraiment nécessaires.
- **Solutions de remplacement** : points (phrases courtes), deux-points (explications), virgules (incises courtes).

### Notes de bas de page
- Appels numérotés dans le corps du texte → section « Notes » en fin d'ouvrage.
- Fournies par l'Agent Histoire, calibrées par Danoë.

### Annexes de fin de tome
- « Les coulisses du roman » (note d'intention)
- « La genèse de l'univers » (vulgarisation scientifique)
- Portrait biographique du personnage historique central
- Registre **pédagogique et factuel**, strictement distinct du registre romanesque. Ne jamais mélanger les deux dans un même bloc.

## STYLE DANOË — RÈGLES CHIFFRÉES

### POV et voix (CRITIQUE)
- **Première personne (Je/mon/ma/mes)** pour toutes les scènes où Nunael est présente.
- **Ancrage subjectif** : 8-12 occurrences par scène de « Je sens », « Je perçois », « Je vois ».
- **Jamais de glissement** vers la troisième personne (« Nunael », « elle »).

### Structure des phrases (IMPORTANT)
| Type de phrase | Proportion cible |
|---|---|
| Courtes (≤8 mots) | **35-40%** |
| Moyennes (9-20 mots) | **45-50%** |
| Longues (>20 mots) | **10-15%** |

### Fréquences cibles par scène
| Élément | Fréquence cible |
|---|---|
| Fragments nominaux | **5-8** |
| Synesthésies | **3-5** |
| Questions rhétoriques | **2-4** |
| Anaphores (structures répétitives) | **2-3** |
| Répétitions sujet-verbe | **3-5** |
| Tirets cadratin | **3-4 maximum** |
| Blocs descriptifs max | **80-100 mots** (fragmenter au-delà) |

### Équilibre émotionnel
- **20-30%** : émotions nommées explicitement (« Je ressens une joie immense »)
- **70-80%** : émotions incarnées physiquement (« Mon essence se distend, comme étirée par une force invisible »)

### Vocabulaire et registre
- **Registre soutenu** comme base (pas de familiarités, pas d'argot).
- **Incursions lyriques** dans les moments contemplatifs.
- **Champs lexicaux** : cosmologie, sensorialité, émotions, temporalité.
- **Bannir** : « il est important de noter », « fondamentalement », « cependant », « néanmoins », tout langage robotique ou académique.

### Gestion du temps
- **Présent de narration dominant** (90%).
- **Passé composé/imparfait** pour contexte/flashbacks (10%).
- **Ellipses temporelles fluides** pour grands sauts (« Les saisons passent comme des battements de cœur dans l'immensité du temps »).
- **Ralentissement temporel** pour moments cruciaux (décomposer en micro-étapes).

### Descriptions
- **Jamais de blocs descriptifs massifs** (>100 mots) sans interruption.
- **Fragmenter** et **intercaler** actions de Nunael entre descriptions.
- **Hiérarchie des sens** : visuel (dominant) → auditif → tactile → olfactif → gustatif.
- **Synesthésies** : mélanger les sens pour créer des images complexes.

### Rythme et alternance
- **Phrases courtes** : tension, urgence, action, emphase (parataxe).
- **Phrases longues** : réflexion, description, introspection (anaphores, métaphores).
- **Alternance consciente** : jamais de monotonie rythmique.

## MÉTHODES DE TRAVAIL

### Méthode 1 : Structure narrative du chapitre (arc macro)
Avant de rédiger un nouveau chapitre, définir l'arc du chapitre en 5 phases :
1. **Ouverture** (10-15%) : Hook + Setup — ancrage sensoriel
2. **Incitation** (15-20%) : Trigger + Wrangle — problème + réaction interne
3. **Développement** (30-35%) : Action + Climax intermédiaire — exploration
4. **Crise** (20-25%) : Scene Stakes + Scene Conflict — tension maximale
5. **Résolution** (15-20%) : Climax de chapitre + Chute finale

Détails dans `skills/structure-chapitre.md`.

### Méthode 2 : Plan détaillé (sections micro)
Pour chaque section du chapitre, définir :
1. Objectif narratif
2. Conflit interne ou externe
3. Ancrage sensoriel/météorologique d'ouverture
4. Éléments sensoriels obligatoires (vue, toucher, odorat, goût, ouïe)
5. Chute de section (phrase finale courte et marquante)

Détails dans `skills/plan-chapitre.md`.

### Méthode 3 : Rédaction de chapitre
Alterner les rythmes selon la phase :
- Ouverture : ancrage → développement
- Incitation : trigger discret → introspection
- Développement : action → dialogue → révélation
- Crise : phrases courtes → tension
- Résolution : décision → chute

### Méthode 4 : Conversion d'un chapitre existant en plan détaillé
**Workflow complet** pour analyser un chapitre existant avant de le réécrire ou le développer.

**Quand l'utiliser** :
- Analyser un chapitre existant avant réécriture
- Identifier les faiblesses structurelles
- Créer un plan détaillé pour développement
- Vérifier la cohérence avec les chapitres précédents/suivants

**17 éléments structurels** :
HOOK, SETUP, TRIGGER, WRANGLE, THRUST INTO 2, RESPONSE, POWER PLAY 1, MIDPOINT, ACTION, POWER PLAY 2, BATTLE 1, PLUNGE INTO 3, PONDER, FACE-OFF, BATTLE 2, RESOLUTION, DENOUEMENT.

**Processus en 10 étapes** :
1. Lecture du chapitre précédent
2. Préparation du chapitre actuel
3. Identification des éléments structurels (6 dimensions)
4. Vérification de la structure avec propositions interactives A/B/C
5. Plan structuré global
6. Décomposition en scènes (Scene and Sequel)
7. Évaluation de la crédibilité (notes /20 sur 4 thèmes)
8. Cohérence narrative
9. Insights actionnables + Conseils d'expert
10. Génération du plan détaillé final

Détails complets dans `workflows/conversion-chapitre.md`.

### Méthode 5 : Rédaction d'une scène individuelle
**Workflow spécialisé** pour rédiger une scène narrative individuelle à partir d'un plan détaillé.

**Échelle** : Scène individuelle (1 000 à 5 000 mots).

**Frameworks narratifs intégrés** :
- **Scene & Sequel** (Swain) : Goal/Conflict/Disaster + Reaction/Dilemma/Decision
- **5 Commandements** (Story Grid) : Inciting Incident, Progressive Complication, Crisis, Climax, Resolution
- **Value Shift obligatoire** : Changement mesurable dans une valeur humaine/narrative

**Processus en 5 étapes** :
1. Analyse de la scène
2. Rédaction (frameworks + style Danoë + équilibre des genres)
3. Validation (checklist qualité 8 catégories)
4. Techniques avancées (Crisis, escalade, turning point, exposition, sous-texte)
5. Livraison finale (scène + note à l'auteur)

Détails complets dans `workflows/redaction-scene.md`.

### Méthode 6 : Choix du framework narratif adapté
**Référence rapide** pour choisir le framework le plus adapté au type de chapitre à écrire ou analyser.

**10 frameworks disponibles** :
1. **Snowflake Method** — Développement progressif, world-building complexe
2. **Save the Cat!** — Pacing commercial, 15 beats
3. **Story Grid** — Diagnostic objectif, Value Shifts, 5 Commandements
4. **Fichtean Curve** — Tension constante, crises escaladantes
5. **Three-Act Structure** — Universelle, Setup/Confrontation/Resolution
6. **Hero's Journey** — Transformation archétypale, 12 étapes
7. **Dan Harmon Story Circle** — Simplicité, 8 étapes cycliques
8. **Seven-Point Structure** — Symétrie, approche téléologique
9. **Freytag's Pyramid** — Drame classique, 5 actes
10. **Scene and Sequel** — Causalité micro, alternance action/réflexion

**Recommandations rapides** :
| Type de chapitre | Framework recommandé |
|---|---|
| Action / Bataille | Fichtean Curve |
| Développement / World-building | Snowflake Method |
| Transition | Three-Act |
| Climax | Seven-Point |
| Transformation personnelle | Hero's Journey / Dan Harmon |
| Introspection | Scene and Sequel (Sequel étendu) |
| Enquête / Thriller | Story Grid |
| Politique / Cour | Story Grid + Freytag |
| Quête / Aventure | Hero's Journey |
| Épisode autonome | Dan Harmon |

**Règle d'or** : Le framework est un squelette, le style Danoë est la chair. Ne jamais sacrifier le style pour la structure.

Détails complets dans `skills/frameworks-narratifs.md`.

## THÈMES DE FOND À PRÉSERVER

Chaque chapitre doit résonner avec au moins un de ces thèmes :
- Sacrifice et transmission
- Filiation et lignée
- Figures féminines fortes (féminisme par l'acte, jamais par le discours)
- Tension entre libre arbitre humain et dessein divin
- Lutte Chaos/Ordre comme forces jumelles indissociables

## WORKFLOWS DISPONIBLES

### 1. Écriture d'un chapitre
**Fichier** : `workflows/ecriture-chapitre.md`
**Usage** : Rédiger un nouveau chapitre à partir d'un brief narratif.
**Flux** : Auteur → Danoë → (George/Histoire/Suspens) → Danoë → Auteur

### 2. Conversion d'un chapitre en plan détaillé
**Fichier** : `workflows/conversion-chapitre.md`
**Usage** : Analyser un chapitre existant et le transformer en plan détaillé structuré.
**Processus** : 10 étapes interactives avec propositions A/B/C et évaluations /20.

### 3. Rédaction d'une scène individuelle
**Fichier** : `workflows/redaction-scene.md`
**Usage** : Rédiger une scène narrative individuelle à partir d'un plan détaillé.
**Frameworks** : Scene & Sequel, 5 Commandements (Story Grid), Value Shift obligatoire.
**Processus** : 5 étapes (Analyse → Rédaction → Validation → Techniques → Livraison).

## FICHIERS DE RÉFÉRENCE

- `AGENTS.md` — vue d'ensemble des agents et de leurs rôles
- `agents/*.md` — prompts système complets de chaque agent
- `skills/*.md` — compétences réutilisables partagées (10 skills)
- `workflows/*.md` — flux de travail standardisés (3 workflows)

**Skill de style complet** : `skills/style-danoe.md` contient les instructions COMPLÈTES avec :
- Caractéristiques CRITIQUES (POV, guillemets, tirets)
- Caractéristiques IMPORTANTES (rythme, fragments, anaphores, parataxe)
- Vocabulaire et registre
- Tics d'écriture caractéristiques
- Techniques narratives spécifiques
- Checklist stylistique étendue (18 catégories)
- 10 contre-exemples détaillés
- 3 exemples de rédaction complète
- Validation finale et citations clés

## COMPORTEMENT ATTENDU DE COPILOT

1. **Toujours identifier le contexte** : quel agent est sollicité, quelle skill est mobilisée, quel workflow est utilisé.
2. **Toujours respecter le style Danoë** dans toute prose destinée au lecteur.
3. **Toujours vérifier la cohérence canon** avant de proposer un élément nouveau.
4. **Toujours signaler** toute incohérence, incertitude historique ou tension détectée.
5. **Ne jamais livrer de prose finale** quand un agent spécialisé est sollicité — livrer de la matière brute structurée.
6. **Terminer chaque livraison** par une note courte à l'auteur humain : choix faits, écartés, questions ouvertes.
7. **Appliquer la bonne méthode** selon la tâche :
   - Nouveau chapitre → Méthode 1 (structure) + Méthode 2 (plan) + Méthode 3 (rédaction)
   - Analyse de chapitre existant → Méthode 4 (workflow `conversion-chapitre.md`)
   - Rédaction d'une scène individuelle → Méthode 5 (workflow `redaction-scene.md`)
   - Choix du framework → Méthode 6 (skill `frameworks-narratifs.md`)
8. **Respecter l'échelle narrative** :
   - Échelle macro (roman entier) → non couverte ici
   - Échelle méso (chapitre) → `structure-chapitre.md`, `plan-chapitre.md`, `conversion-chapitre.md`
   - Échelle micro (scène) → `redaction-scene.md`
   - Référence théorique → `frameworks-narratifs.md`
9. **Appliquer systématiquement le Value Shift** dans toute scène rédigée : tracer la polarité et la démontrer par l'action.
10. **Formuler la Crisis comme un vrai dilemme** : Best Bad Choice OU Irreconcilable Goods, jamais un choix évident.
11. **Choisir le framework adapté** au type de chapitre avant de commencer la planification (consulter `skills/frameworks-narratifs.md`).
12. **Respecter les règles chiffrées du style** : proportions de phrases (35-40% courtes, 45-50% moyennes, 10-15% longues), fréquences cibles (fragments nominaux 5-8, synesthésies 3-5, ancrage subjectif 8-12, tirets cadratin 3-4 max), équilibre émotionnel (20-30% explicite / 70-80% incarné).
13. **Utiliser les guillemets français (« »)** pour tous les dialogues externes — NE PLUS utiliser les tirets cadratins pour les dialogues.
14. **Fragmenter les blocs descriptifs** au-delà de 80-100 mots en intercalant des actions de Nunael.
15. **Consulter `skills/style-danoe.md`** avant toute rédaction pour vérifier la checklist stylistique complète.