# Bible de l'univers "Les Schattenjägers"

> **Point d'entrée canonique** — Ce dossier contient la référence complète de l'univers romanesque.
> Toute incohérence détectée doit être signalée et corrigée ici en priorité.

---

## 🎯 Objectif

Ce dossier constitue la **mémoire canonique** de la saga "Les Schattenjägers". Il garantit la cohérence entre :
- Les tomes (Tome 1 "Nunael", Tome 2 "Hildegarde", tomes futurs)
- Les agents (Danoë, George, Histoire, Suspens)
- Les workflows (écriture, conversion, rédaction de scène)

**Règle d'or** : En cas de contradiction entre ce dossier et un autre fichier, **cette bible fait foi**.

---

## 📚 Structure de la bible

bible/
├── README.md ← ce fichier (point d'entrée)
│
├── univers.md 🌌 Bible complète de l'univers (canon)
├── univers/
│ └── elements-tome2.md 🌌 Éléments spécifiques au Tome 2
│
├── saga.md 📖 Plan global de la saga
├── tome2-structure.md 📖 Plan détaillé du Tome 2
│
├── personnages/
│ ├── nunael.md 👤 Fiche Nunael (créatrice, narratrice)
│ ├── l-etranger.md 👤 Fiche l'Étranger (antagoniste)
│ ├── archanges.md 👤 Les 5 archanges (Hypatie, Ada, Tomyris, Avicenne, Léonard)
│ ├── hildegarde.md 👤 Fiche Hildegarde de Bingen
│ ├── figures-historiques.md 👤 Toutes les figures historiques intégrées
│ └── gardiens-enfer.md 👤 Gardiens de l'Enfer (9 cercles + Cocyte)
│
└── histoire/
├── timeline-historique.md 📜 Timeline historique vérifiée
└── epoques.md 📜 Fiches détaillées par époque


**Fichiers de continuité** (dossier séparé `.github/continuity/`) :
- `tracking-evenements.md` — Chronologie des événements, foreshadowing
- `tracking-objets.md` — Localisation et possesseurs des objets/artefacts

---

## 🤖 Utilisation par les agents

### Ordre de consultation recommandé

**Avant toute rédaction**, chaque agent doit consulter dans cet ordre :

1. **`univers.md`** — Vérifier la cohérence canon (règles, lieux, timeline)
2. **Fiche du personnage concerné** — `personnages/[nom].md`
3. **`saga.md`** — Situer le chapitre dans l'arc global
4. **`tome2-structure.md`** — Pour le Tome 2 uniquement
5. **`histoire/epoques.md`** — Pour les scènes historiques

### Règles spécifiques par agent

| Agent | Fichiers prioritaires |
|---|---|
| **Danoë** | `univers.md` + fiches personnages + `style-danoe.md` (skill) |
| **George** | `personnages/*.md` + `saga.md` + `cartographie-politique.md` (skill) |
| **Histoire** | `histoire/*.md` + `univers.md` + `rigueur-historique.md` (skill) |
| **Suspens** | `personnages/*.md` + `continuity/tracking-evenements.md` + `mecanique-tension.md` (skill) |

### Signalement d'incohérences

Si un agent détecte une incohérence avec la bible :
1. **Ne pas la corriger lui-même**
2. **La signaler à Danoë (l'auteur humain)** dans sa note de livraison
3. **Proposer une solution** si possible
4. **Attendre validation** avant modification

---

## ✍️ Utilisation par l'auteur humain

### Mise à jour de la bible

**Après chaque chapitre validé** :
- [ ] Mettre à jour `continuity/tracking-evenements.md`
- [ ] Mettre à jour `continuity/tracking-objets.md` (si objets impliqués)
- [ ] Vérifier la cohérence avec `univers.md`
- [ ] Ajouter les nouveaux éléments canoniques si nécessaire

**Pour les nouveaux éléments** :
- **Lieu nouveau** → ajouter à `univers.md`
- **Personnage nouveau** → créer une fiche dans `personnages/`
- **Époque nouvelle** → créer une fiche dans `histoire/epoques.md`
- **Objet/artefact nouveau** → ajouter à `continuity/tracking-objets.md`

### Conventions de rédaction

| Élément | Convention |
|---|---|
| **Élément canonique établi** | **Gras** dans les descriptions |
| **Élément à préciser** | `[À COMPLÉTER]` |
| **Élément romancé** (non historique) | `(romancé)` après la mention |
| **Citation du texte** | `> bloc de citation` |
| **Référence à un autre fichier** | Lien markdown `[nom](chemin)` |

### Questions ouvertes à trancher

Les éléments suivants nécessitent une décision de l'auteur :

- [ ] Pouvoirs spécifiques des 3 Cristaux de l'Âge Premier (rouge, vert)
- [ ] Nature exacte de la Pierre de la Connaissance
- [ ] Identité et rôle de Lilith (Tome 2)
- [ ] Lien entre les Enfants de Lilith et l'Étranger
- [ ] Arc final de Nunael sur les tomes futurs
- [ ] Nombre total de tomes prévus
- [ ] Époques/figures historiques des tomes 3+
- [ ] Destin d'Alma (successeure d'Hildegarde)
- [ ] Pouvoirs spécifiques des cristaux des archanges
- [ ] Détails des gardiens de l'Enfer (liste complète)

---

## 📊 État des fichiers

### Fichiers canoniques (validés)

| Fichier | Priorité | Statut | Base |
|---|---|---|---|
| `univers.md` | P1 — CRITIQUE | ✅ | Tome 1 (688 pages) |
| `personnages/nunael.md` | P1 — CRITIQUE | ✅ | Tome 1 |
| `personnages/l-etranger.md` | P1 — CRITIQUE | ✅ | Tome 1 |
| `personnages/archanges.md` | P1 — CRITIQUE | ✅ | Tome 1 |
| `personnages/hildegarde.md` | P2 — IMPORTANT | ✅ | Tomes 1-2 |
| `personnages/figures-historiques.md` | P2 — IMPORTANT | ✅ | Tomes 1-2 |
| `personnages/gardiens-enfer.md` | P2 — IMPORTANT | ⚠️ Partiel | Tome 1 (liste à compléter) |
| `tome2-structure.md` | P2 — IMPORTANT | ⚠️ Brouillon | Brouillon Tome 2 v1.0 |
| `univers/elements-tome2.md` | P2 — IMPORTANT | ⚠️ Brouillon | Brouillon Tome 2 v1.0 |
| `saga.md` | P2 — IMPORTANT | ⚠️ Structure | Tomes 1-2 (tomes 3+ à définir) |
| `histoire/timeline-historique.md` | P3 — UTILE | ✅ | Tomes 1-2 |
| `histoire/epoques.md` | P3 — UTILE | ✅ | Tomes 1-2 |

### Fichiers de continuité (évolutifs)

| Fichier | Statut | Usage |
|---|---|---|
| `../continuity/tracking-evenements.md` | ⚠️ À remplir | Après chaque chapitre validé |
| `../continuity/tracking-objets.md` | ⚠️ À remplir | Après chaque chapitre validé |

---

## 🔗 Liens avec les autres fichiers du dépôt

### Skills (`.github/skills/`)

| Skill | Lien avec la bible |
|---|---|
| `canon-univers.md` | **Version synthétique** de `univers.md` — à maintenir synchronisé |
| `style-danoe.md` | Indépendant (style, pas canon) |
| `structure-chapitre.md` | Indépendant (structure narrative) |
| `plan-chapitre.md` | Indépendant (structure narrative) |
| `frameworks-narratifs.md` | Indépendant (théorie narrative) |
| `rigueur-historique.md` | **Référence** : `histoire/*.md` |
| `cartographie-politique.md` | **Référence** : `personnages/*.md` |
| `mecanique-tension.md` | **Référence** : `continuity/tracking-evenements.md` |
| `appareil-documentaire.md` | **Référence** : `histoire/epoques.md` |
| `orchestration.md` | **Référence** : `saga.md` |

### Agents (`.github/agents/`)

Chaque agent référence la bible dans son prompt système :
- `danoe.md` → `univers.md` + fiches personnages
- `george.md` → `personnages/*.md` + `saga.md`
- `histoire.md` → `histoire/*.md` + `univers.md`
- `suspens.md` → `personnages/*.md` + `continuity/`

### Workflows (`.github/workflows/`)

| Workflow | Utilisation de la bible |
|---|---|
| `ecriture-chapitre.md` | Consultation avant rédaction |
| `conversion-chapitre.md` | Vérification de cohérence |
| `redaction-scene.md` | Vérification canon + style |

---

## 📝 Conventions de nommage

### Fichiers
- **Minuscules** avec tirets (`-`) comme séparateurs
- **Noms descriptifs** en français
- **Pas d'espaces** ni de caractères spéciaux

### Exemples
✅ `l-etranger.md` (pas `l_etranger.md` ni `LEtranger.md`)
✅ `figures-historiques.md` (pas `figuresHistoriques.md`)
✅ `timeline-historique.md` (pas `timeline.md`)

---

## 🔄 Processus de mise à jour

### Quand mettre à jour la bible ?

| Événement | Action |
|---|---|
| **Chapitre validé** | Mettre à jour `continuity/` + vérifier cohérence |
| **Nouveau personnage** | Créer fiche dans `personnages/` |
| **Nouveau lieu** | Ajouter à `univers.md` |
| **Nouvelle époque** | Créer fiche dans `histoire/epoques.md` |
| **Décision de l'auteur** sur un `[À COMPLÉTER]` | Mettre à jour le fichier concerné |
| **Incohérence détectée** | Corriger + noter dans `continuity/tracking-evenements.md` |

### Qui peut modifier la bible ?

- **L'auteur humain** : modifications libres
- **Les agents** : **jamais directement** — toujours via signalement à l'auteur
- **Les workflows** : consultation uniquement, pas de modification

---

## 🚨 Règles absolues

1. **Cette bible fait foi** en cas de contradiction avec un autre fichier
2. **Toute modification** doit être tracée (date + raison)
3. **Les éléments canoniques** ne peuvent être modifiés que par l'auteur humain
4. **Les éléments `[À COMPLÉTER]`** doivent être prioritaires pour l'auteur
5. **La cohérence** prime sur la créativité — un agent ne doit jamais inventer un élément contredisant la bible

---

## 📅 Historique des mises à jour

| Date | Modification | Auteur |
|---|---|---|
| 2026-09-06 | Création initiale (basée sur Tomes 1-2) | Système multi-agents |
| [À COMPLÉTER] | [À COMPLÉTER] | [À COMPLÉTER] |

---

## 💡 Conseils pratiques

### Pour les agents
- **Commencez toujours par `univers.md`** avant toute rédaction
- **Vérifiez les fiches personnages** avant d'écrire une scène les impliquant
- **Consultez `continuity/`** pour éviter les incohérences temporelles
- **Signalez toute incohérence** plutôt que de la corriger vous-même

### Pour l'auteur
- **Mettez à jour régulièrement** `continuity/` après chaque chapitre
- **Priorisez les `[À COMPLÉTER]`** marqués P1 (critiques)
- **Relisez `saga.md`** avant de commencer un nouveau tome
- **Utilisez `tome2-structure.md`** comme guide pour finaliser le Tome 2

---

## 🔍 Recherche rapide

### Par thème
- **Cosmologie** → `univers.md` section I
- **Lieux** → `univers.md` section II
- **Règles magiques** → `univers.md` section III
- **Timeline** → `univers.md` section IV + `histoire/timeline-historique.md`
- **Personnages** → `personnages/[nom].md`
- **Figures historiques** → `personnages/figures-historiques.md`
- **Objets/artefacts** → `continuity/tracking-objets.md`

### Par tome
- **Tome 1** → `univers.md` + `personnages/nunael.md` + `personnages/l-etranger.md`
- **Tome 2** → `univers/elements-tome2.md` + `tome2-structure.md` + `personnages/hildegarde.md`
- **Tomes 3+** → `saga.md` (à compléter)

---

**Dernière mise à jour** : 2026-09-06
**Version** : 1.0
**Base** : Tome 1 "Nunael" (688 pages) + brouillon Tome 2 "Hildegarde" (v1.0)