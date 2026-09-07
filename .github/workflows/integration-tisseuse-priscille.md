# Workflow : Intégration de la tisseuse Priscille

## Déclencheur

Utiliser ce workflow pour toute scène, annexe ou trace liée à Priscille, Aquila, Paul, Apollos, Rome, Corinthe, Éphèse ou à la transmission du sixième diamant.

## Variables de contexte

- `PRISCILLA_PERIOD=49_CE|50_52_CE|52_57_CE|POST_57_CE`
- `PRISCILLA_LOCATION=ROME|CORINTH|EPHESUS|ITALY`
- `PRISCILLA_EVENT=EXPULSION|WORKSHOP|TEACHING|HOUSE_ASSEMBLY|TRANSMISSION`
- `PRISCILLA_SOURCE_STATUS=PAULINE_LETTER|ACTS_TRADITION|ROMAN_SOURCE|FICTION_CANONIQUE`
- `BLUE_DIAMOND_ID=6`
- `PRISCILLA_SOURCE_URL=https://panodyssey.com/fr/article/fantaisie/priscille-la-tisseuse-de-lumiere-qkws7jwut2cm`

## Étapes

1. Danoë fixe l'enjeu : accueil, déplacement, parole partagée, discrétion ou transmission.
2. En parallèle, Histoire applique `qualifier_reseau_domestique()` ; George applique `cartographier_hospitalite()` ; Mémoire des Lieux applique `trouver_porteur_a_date()` ; Suspens choisit ce qui peut rester hors champ.
3. Si l'édit de Claude ou Apollos apparaît, conserver leur statut de sources romaine ou chrétienne et ne pas en déduire plus que le texte ne permet.
4. Si Paul ou Aquila apparaît, préserver son autonomie, ses ambiguïtés et son rôle propre.
5. Si le diamant est transmis, appliquer `transmettre_sans_exposer()` et `valider_transition_schattenjager()` vers une dépositaire anonyme quittant l'Italie.
6. Danoë rédige ; Histoire prépare les notes et le registre du sixième diamant est actualisé après validation humaine.