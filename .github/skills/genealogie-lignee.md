# Skill : Généalogie de la lignée

## Objectif

Transformer une généalogie éditoriale en continuité exploitable sans confondre une étiquette de personnage, une donnée historique et une possession du sixième diamant bleu.

## Règles

- Une personne indiquée comme Schattenjäger(in) dans une source externe n'est intégrée au registre qu'après contrôle d'intervalle.
- La biographie attestée, la tradition, l'hypothèse et le canon romanesque restent séparés.
- Deux porteurs ne peuvent pas détenir le sixième diamant au même moment.
- Une lacune documentée reste `INCONNU` tant qu'une décision canonique ne la remplace pas.
- L'Étranger infléchit des peurs et intérêts humains ; il ne supprime jamais leur responsabilité.

## Fonctions

### `extraire_noeuds_genealogie(source_url, contenu)`
- **Entrées** : URL source, contenu de la page ou de l'archive.
- **Sorties** : personnages, rôles annoncés, dates, lieux, drames historiques et niveau de précision de chaque donnée.

### `qualifier_noeud_historique(personnage, donnees_source)`
- **Entrées** : personnage, dates, lieux, affirmations biographiques et sources disponibles.
- **Sorties** : faits attestés, traditions disputées, incertitudes, éléments à classer `fiction-canonique` et interdictions de rédaction.

### `detecter_chevauchement_diamant(candidat, debut, fin, registre)`
- **Entrées** : candidat, fenêtre de possession proposée et registre du sixième diamant.
- **Sorties** : intervalle compatible, chevauchement détecté ou lacune à préserver.

### `modeliser_noeud_de_lignee(candidat, contexte, heritages)`
- **Entrées** : candidat validé, contexte historique, héritages cumulés.
- **Sorties** : rôle narratif, aptitude unique limitée, fragilité persistante, transmission plausible et contraintes morales.

### `synchroniser_genealogie(fiche, registre, chronologie, index)`
- **Entrées** : fiche validée et fichiers de continuité concernés.
- **Sorties** : liste de mises à jour cohérentes, contradictions résiduelles et contrôle final à exécuter.

## Propriétaires et validateurs

- **@memoire-des-lieux** : contrôle des intervalles, lieux et transmissions.
- **@histoire** : qualification documentaire.
- **@george** : lecture des coûts et rapports de pouvoir.
- **@suspens** : gestion des lacunes et de la révélation.
- **@danoe** : décision finale de canon et rédaction.
