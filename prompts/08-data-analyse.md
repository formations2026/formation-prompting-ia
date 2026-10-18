# Data & Analyse

**Mode d'emploi** : Remplacez les [crochets], collez vos données entre délimiteurs ###, testez, puis itérez une fois. Ne collez jamais de données personnelles ou confidentielles dans un outil non validé par votre entreprise.

Chaque prompt est construit sur C.R.O.F. : Contexte, Rôle, Objectif, Format. Les blocs ci-dessous donnent le prompt à copier, les
variables à remplacer, la décomposition en quatre ingrédients et le point de contrôle propre au prompt.

### 15. Exploration de données

> Voici un extrait CSV ### [coller] ###. Décris la structure, détecte anomalies et valeurs manquantes, propose 3 analyses pertinentes et écris le code Python (pandas) de la première.

- **À remplacer** : `[coller]`
- **Contexte** : Extrait CSV fourni entre délimiteurs
- **Rôle** : Implicite (data analyst)
- **Objectif** : Décrire, détecter les anomalies, proposer 3 analyses, coder la première
- **Format** : Description ; anomalies et valeurs manquantes ; 3 analyses ; code pandas
- **À vérifier** : Exécuter le code sur l'extrait avant de le lancer sur le jeu complet. Données anonymisées uniquement.

### 16. Messages clés pour le COMEX

> Transforme ces résultats ### [coller] ### en 3 messages clés pour un COMEX, chacun avec le chiffre qui le prouve et une recommandation. Propose le graphique adapté à chacun.

- **À remplacer** : `[coller]`
- **Contexte** : Résultats d'analyse fournis entre délimiteurs
- **Rôle** : Implicite (analyste présentant au COMEX)
- **Objectif** : Transformer les résultats en 3 messages clés
- **Format** : 3 messages ; chiffre preuve ; recommandation ; type de graphique
- **À vérifier** : Chaque chiffre cité provient-il bien des résultats collés, sans arrondi trompeur ?

Retour à la [bibliothèque complète](bibliotheque.md).
