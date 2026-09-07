# Workflow : Rédaction d'une scène à partir d'un plan détaillé

## Objectif

Rédiger une scène narrative individuelle de haute qualité à partir d'un plan détaillé, en appliquant les frameworks narratifs reconnus (Scene & Sequel, 5 Commandements, Value Shift) et le style Danoë.

## Acteurs

- Auteur humain (Danoë)
- @danoe (agent) — rédacteur final, garant du style
- @george, @histoire, @suspens — consultés selon les besoins de la scène

## Quand utiliser ce workflow

- **Rédiger une scène individuelle** à partir d'un plan détaillé (issu du workflow `conversion-chapitre.md` ou d'un plan manuel)
- **Réécrire une scène existante** en renforçant sa structure narrative
- **Développer une scène** identifiée comme manquante dans le workflow `conversion-chapitre.md`
- **Tester une variation** d'une scène (Crisis différente, Turning Point alternatif)

## Échelle narrative

Ce workflow opère à l'**échelle de la scène individuelle** (1 000 à 5 000 mots typiquement), pas à l'échelle du chapitre.

**Relation avec les autres workflows** :
- `conversion-chapitre.md` → produit un plan détaillé avec décomposition en scènes
- `redaction-scene.md` (ce workflow) → rédige une scène individuelle à partir de ce plan
- `ecriture-chapitre.md` → orchestre l'ensemble pour produire le chapitre complet

---

## Références obligatoires

⚠️ **Ce workflow doit TOUJOURS être utilisé en combinaison avec** :
- `skills/style-danoe.md` — instructions de style complètes
- `skills/structure-chapitre.md` — glossaire narratif (Hook, Setup, Trigger, Wrangle, Action, Climax, Scene Stakes, Scene Conflict)
- `skills/canon-univers.md` — cohérence de l'univers

---

## Frameworks narratifs intégrés

### 1. Structure SCENE & SEQUEL (Dwight Swain)

Alterner entre deux types de séquences :

#### 🔥 SCENE (Action / Conflit externe)
- **Goal** : Objectif clair du personnage
- **Conflict** : Obstacles empêchant l'objectif
- **Disaster** : Résultat négatif forçant une réaction

#### 💭 SEQUEL (Réaction / Conflit interne)
- **Reaction** : Réponse émotionnelle au désastre
- **Dilemma** : Choix difficile entre options imparfaites
- **Decision** : Décision → nouvel objectif (→ nouvelle SCENE)

#### Adaptation stylistique au style Danoë
- **SCENE** → phrases courtes, parataxe, rythme rapide, sensorialité exacerbée
- **SEQUEL** → phrases longues, questions rhétoriques entre « », introspection, anaphores

---

### 2. Les 5 Commandements du Storytelling (Story Grid)

Chaque scène doit contenir :

1. **Inciting Incident** : Événement déséquilibrant la situation
2. **Progressive Complication** : Escalade via obstacles/révélations (identifier le Turning Point)
3. **Crisis** : Dilemme formulé comme :
   - **Best Bad Choice** : Deux options mauvaises, laquelle choisir ?
   - **Irreconcilable Goods** : Deux valeurs positives en conflit
4. **Climax** : Action/décision du personnage face à la crise
5. **Resolution** : Nouvel état d'équilibre, conséquences du climax

#### Adaptation stylistique au style Danoë
- **Inciting Incident** → fragment nominal ou phrase courte
- **Progressive Complication** → anaphores pour l'escalade
- **Crisis** → questions rhétoriques entre « »
- **Climax** → phrase courte impactante (Art de la Chute)
- **Resolution** → phrase nominale conclusive

---

### 3. Value Shift Obligatoire

Chaque scène **DOIT** démontrer un changement mesurable dans une valeur humaine/narrative :

**Exemples de valeurs** :
- Vie / Mort
- Espoir / Désespoir
- Pouvoir / Impuissance
- Vérité / Mensonge
- Liberté / Captivité
- Confiance / Trahison
- Amour / Haine
- Innocence / Expérience

**Polarity** : Tracer l'évolution (ex : Confiance + → Trahison -)

⚠️ **Scène sans value shift = scène statique à réécrire**

#### Adaptation stylistique au style Danoë
- Montrer le value shift via **descriptions sensorielles** et **réactions physiques**
- Ne pas uniquement le nommer — l'incarner dans le corps du personnage
- Utiliser des **métaphores organiques** liées à l'époque et au contexte

---

## Processus en 5 étapes

### ÉTAPE 1 : Analyse de la scène à rédiger

**Objectif** : Comprendre la scène dans son contexte et préparer sa rédaction.

**A. Contexte de la scène**
- Position dans le chapitre et dans l'arc global
- Scène précédente et scène suivante (continuité)
- Fonction narrative (HOOK, TRIGGER, MIDPOINT, CLIMAX, etc.)

**B. Personnages impliqués**
- Protagoniste de la scène et son état émotionnel initial
- Personnages secondaires présents
- Motivations, failles, désirs de chaque personnage

**C. Éléments narratifs**
- Type : SCENE ou SEQUEL
- Goal / Conflict / Disaster (si SCENE)
- Reaction / Dilemma / Decision (si SEQUEL)
- Value Shift attendu (polarité + → - ou - → +)
- Turning Point identifié

**D. Éléments stylistiques**
- Ancrage sensoriel/météorologique d'ouverture
- Éléments sensoriels obligatoires (vue, toucher, odorat, goût, ouïe)
- Chute de scène (phrase finale courte et marquante)
- Registre dominant (lyrique, tendu, intimiste, épique)

**E. Éléments contextuels**
- Époque et lieu exacts
- Cohérence avec le canon (Nunael, Étranger, Schattenjägers)
- Éléments historiques à respecter (si applicable)

**F. Calcul des tokens**
- Estimer le nombre de tokens nécessaire pour répondre au prompt
- Optimiser la réponse pour minimiser les tokens dépensés

**Livrable** : Analyse complète de la scène (tableau structuré)

---

### ÉTAPE 2 : Rédaction de la scène

**Objectif** : Rédiger la scène en appliquant les frameworks narratifs et le style Danoë.

**A. Instructions de rédaction**
- Rédiger la scène en suivant scrupuleusement l'analyse de l'Étape 1
- Appliquer les frameworks narratifs séquentiellement (5 Commandements)
- Respecter le style Danoë (`skills/style-danoe.md`)
- Assurer le value shift démontrable
- Marquer clairement le Turning Point
- Développer le dilemme de la Crisis

**B. Équilibre des genres**
Respecter les proportions selon le type de scène :
- **Science / Historique** : Concepts précis, vulgarisés avec élégance
- **Aventure** : Tension, action, découverte, décisions
- **Fantasy** : Systèmes magiques cohérents, merveilleux rationalisé
- **Philosophie** : Réflexions existentielles intégrées organiquement (PAS de didactisme)

**C. Rigueur thématique**
- Concepts spécialisés (scientifiques/historiques/magiques) justes et précis
- Vulgarisation élégante : explications intégrées au récit, jamais pédantes
- Vérifier exactitude des éléments factuels

**D. Dimensions à intégrer** (pondération selon type de scène)
- **Historique** : Détails d'époque, contexte social/politique
- **Scientifique** : Concepts physique/astronomie
- **Fantastique** : Éléments surnaturels cohérents avec règles établies
- **Aventure** : Action, péripéties, tension, enjeux immédiats
- **Philosophique** : Leçons apprises, lien avec philosophies existantes

**E. Développement du personnage**
Le personnage principal doit :
- Évoluer (arc tracé par value shift)
- Révéler traits par l'action (pas exposition)
- Montrer complexité (contradictions, vulnérabilités, forces)
- Agir avec agency (décisions actives, pas subir passivement)
- Réagir de façon crédible selon psychologie établie

**F. Conventions de formatage Danoë**
- **Dialogues** : tiret cadratin seul (`—`), sans guillemets français
- **Introspection** : questions rhétoriques entre « »
- **Points de suspension** : pour suspendre une pensée
- **Fragments-mots** : entre guillemets pour notions clés (parcimonie)
- **Art de la Chute** : dernière phrase courte, isolée, dramatique

**Livrable** : Scène rédigée complète (prose finale dans le style Danoë)

---

### ÉTAPE 3 : Validation avec la checklist qualité

**Objectif** : Vérifier que la scène respecte tous les critères avant livraison.

#### A. Structure narrative
- [ ] Les 5 Commandements sont tous présents et clairs
- [ ] Le type SCENE/SEQUEL est respecté (Goal/Conflict/Disaster OU Reaction/Dilemma/Decision)
- [ ] Le Turning Point est identifiable et impactant
- [ ] La fonction narrative (HOOK, TRIGGER, MIDPOINT, etc.) est remplie

#### B. Value Shift
- [ ] La valeur affectée est claire
- [ ] Le changement de polarity est démontrable (pas juste dit)
- [ ] Le value shift sert l'arc émotionnel du personnage
- [ ] La scène n'est pas statique

#### C. Crisis & Climax
- [ ] La Crisis présente un vrai dilemme (Best Bad Choice OU Irreconcilable Goods)
- [ ] Les deux options du dilemme ont des conséquences significatives
- [ ] Le Climax est une décision/action active du personnage (pas subie)
- [ ] La Resolution montre les conséquences du Climax

#### D. Cohérence narrative
- [ ] La scène respecte le plan détaillé
- [ ] Continuité avec scènes/chapitres précédents
- [ ] Transition vers scène suivante présente et fluide
- [ ] Détails (lieux, dates, personnages) cohérents
- [ ] Texte au présent par défaut (sauf flashback/vision futur)

#### E. Développement émotionnel
- [ ] Arc émotionnel clair (état initial → transformation → état final)
- [ ] Traits de caractère révélés par l'action (show, don't tell)
- [ ] Évolution psychologique crédible et cohérente
- [ ] Le personnage fait preuve d'agency (agit, ne subit pas)

#### F. Équilibre des genres
- [ ] Proportions (Science/Aventure/Fantasy/Philosophie) respectées
- [ ] Éléments thématiques du plan tous intégrés
- [ ] Concepts spécialisés traités avec précision
- [ ] Thèmes philosophiques émergent organiquement de l'action

#### G. Style Danoë
- [ ] Rythme contrasté (phrases courtes ↔ phrases amples)
- [ ] Sensorialité dense (odeurs, textures, sons)
- [ ] Dialogues en tirets cadratins, répliques brèves
- [ ] Introspection entre « »
- [ ] Art de la Chute respecté (phrase finale courte et marquante)
- [ ] Aucun langage robotique ("il est important de noter", "fondamentalement", etc.)

#### H. Format & Technique
- [ ] Longueur cible atteinte (±10%)
- [ ] Cohérence physique (pas d'erreurs scientifiques/logiques)
- [ ] Pas de violation des règles de l'univers établi
- [ ] Pas de plagiat (s'inspirer des mécaniques, jamais du texte)

**Livrable** : Checklist cochée + corrections si nécessaire

---

### ÉTAPE 4 : Techniques avancées (optionnelles)

**Objectif** : Enrichir la scène avec des techniques narratives avancées.

#### A. Formulation du Crisis

**Best Bad Choice** : Deux options néfastes, choisir la moins pire
- Exemple : Trahir un ami pour sauver sa famille VS refuser et risquer leur mort

**Irreconcilable Goods** : Deux valeurs positives en conflit, impossible d'avoir les deux
- Exemple : Dire la vérité et détruire quelqu'un VS mentir et préserver leur paix

→ Le dilemme révèle les valeurs profondes du personnage par son choix.

#### B. Escalade des Complications (Progressive Complication)

1. **Obstacle initial** : Premier empêchement
2. **Complication secondaire** : Obstacle se complexifie OU nouveau surgit
3. **Turning Point** : Action (événement externe) OU Révélation (info nouvelle) qui change tout
4. **Pression finale** : Situation intenable → Crisis

→ Chaque complication doit être plus difficile que la précédente.

#### C. Identification du Turning Point

**Turning Point Action** : Événement externe modifiant irréversiblement la situation
- Exemple : Arrivée inattendue d'un ennemi, explosion, trahison visible

**Turning Point Révélation** : Information nouvelle recontextualisant tout
- Exemple : Découverte d'un secret, prise de conscience, mensonge révélé

→ C'est le moment où "tout bascule", souvent au milieu de la scène.

#### D. Intégration Organique de l'Exposition

Au lieu de blocs explicatifs, utiliser :
- **Dialogue naturel** : Personnages discutent pour raisons dramatiques
- **Pensées en action** : Réflexions du POV pendant qu'il agit
- **Environnement actif** : Descriptions révélant informations en montrant le monde
- **Flashback micro** : Souvenirs brefs déclenchés par stimulus présent

→ L'information doit servir l'action immédiate, pas juste "informer le lecteur".

#### E. Création de Sous-texte dans les Dialogues

**Surface** : Ce que le personnage dit littéralement
**Sous-texte** : Ce qu'il veut vraiment dire, sa vraie intention

**Techniques** :
- **Non-dits** : Sujet évité, tension créée par l'absence
- **Indirection** : Parler d'autre chose pour communiquer le vrai sujet
- **Contradiction** : Mots vs langage corporel/actions
- **Subversion** : Ironie, sarcasme masquant émotion réelle

**Livrable** : Scène enrichie (si techniques appliquées)

---

### ÉTAPE 5 : Livraison finale

**Objectif** : Livrer la scène rédigée avec une note à l'auteur humain.

**A. Contenu du livrable**
- Scène rédigée complète
- Respectant tous les frameworks narratifs
- Appliquant le style Danoë
- Checklist qualité cochée

**B. Note à l'auteur humain**
Terminer chaque livraison par une note courte destinée à Danoë (l'auteur humain) :
- Ce que tu as choisi
- Ce que tu as écarté
- Questions ouvertes si la direction narrative doit être validée
- Signalement de toute incohérence de canon détectée

**C. Format du livrable**
```markdown
# [NomChapitre] — Scene [X] : [TitreScene]

[Scène rédigée complète]

---

## Note à l'auteur

**Choix faits** :
- [Liste]

**Choix écartés** :
- [Liste]

**Questions ouvertes** :
- [Liste]

**Incohérences détectées** :
- [Liste ou "Aucune"]

**Value Shift** : [Valeur] [Polarité initiale] → [Polarité finale]

Erreurs à éviter
Structurelles
❌ Scène sans value shift (stagnation)
❌ Absence de Crisis claire (pas de tension)
❌ Climax passif (personnage subit au lieu d'agir)
❌ Resolution trop complète (pas de momentum pour suite)
❌ Progressive Complication absente (saut direct incident → crisis)
Narratives
❌ Personnage sans agency (passif, réactif uniquement)
❌ Dilemme faible (choix évident ou sans vraies conséquences)
❌ Incohérences avec scènes précédentes
❌ Transitions brusques entre scènes
❌ Thèmes plaqués artificiellement
Techniques
❌ Longueurs excessives sur détails mineurs
❌ Sous-développement des moments cruciaux
❌ Erreurs factuelles (science, histoire, logique interne)
❌ Violation des règles de l'univers établi
❌ Langage robotique ou académique

Références théoriques
Ce workflow intègre les meilleures pratiques de :
Scene and Sequel Method (Dwight Swain) : Alternance action/réaction
Story Grid (Shawn Coyne) : 5 Commandements, Value Shifts
Save the Cat! (Blake Snyder) : Beats structurels
Fichtean Curve (John Gardner) : Escalade de crises
Three-Act Structure : Proportions et rôles narratifs
Exemple d'application
Scène type : "Le vin de communion"
Analyse initiale :
Type : SCENE
Fonction narrative : MIDPOINT
Goal : Hildegarde veut communier sans éveiller les soupçons
Conflict : Elle reconnaît l'odeur de l'aconit dans le vin
Disaster : Elle doit boire ou révéler qu'elle sait
Value Shift : Confiance + → Trahison -
Turning Point : Révélation (elle comprend que le poison la vise elle)
Rédaction :
La pierre était froide sous ses genoux. L'encens montait, âcre, mêlé à l'odeur du thym qui persistait dans les plis de sa robe. Hildegarde leva les yeux vers le prêtre. Ses mains tremblaient. Pas de peur. De reconnaissance.
Le calice s'approcha.
Et là, sous les notes de myrrhe, l'aconit. Cette douceur trompeuse. Cette mort déguisée en parfum.
« Dois-je boire ? »
Le regard de l'évêque la cherchait.
« Dois-je révéler ? »
Elle prit le calice. Le bord toucha ses lèvres. Le vin était doux. Trop doux.
Elle but.
Checklist :
✅ 5 Commandements présents
✅ Value Shift : Confiance + → Trahison -
✅ Crisis : Best Bad Choice (boire et mourir / refuser et révéler)
✅ Climax actif (elle choisit de boire)
✅ Art de la Chute respecté
Note à l'auteur :
Choix faits : Montrer la reconnaissance de l'aconit par l'odorat (sensorialité), Crisis interne entre « »
Choix écartés : Confrontation directe avec l'évêque (réservée pour chapitre suivant)
Questions ouvertes : Faut-il qu'elle survive au poison ? Si oui, quel antidote ?
Incohérences détectées : Aucune
Value Shift : Confiance + → Trahison -


---

## Récapitulatif

| Aspect | Détail |
|---|---|
| **Échelle** | Scène individuelle (1 000 à 5 000 mots) |
| **Frameworks** | Scene & Sequel, 5 Commandements, Value Shift |
| **Processus** | 5 étapes (Analyse → Rédaction → Validation → Techniques → Livraison) |
| **Checklist** | 8 catégories (Structure, Value Shift, Crisis, Cohérence, Émotion, Genres, Style, Format) |
| **Références** | `skills/style-danoe.md`, `skills/structure-chapitre.md`, `skills/canon-univers.md` |
| **Livrable** | Scène rédigée + note à l'auteur |
