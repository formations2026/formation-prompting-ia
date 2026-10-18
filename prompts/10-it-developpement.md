# IT & Développement

**Mode d'emploi** : Remplacez les [crochets], collez vos données entre délimiteurs ###, testez, puis itérez une fois. Ne collez jamais de données personnelles ou confidentielles dans un outil non validé par votre entreprise.

Chaque prompt est construit sur C.R.O.F. : Contexte, Rôle, Objectif, Format. Les blocs ci-dessous donnent le prompt à copier, les
variables à remplacer, la décomposition en quatre ingrédients et le point de contrôle propre au prompt.

### 19. Revue de code

> Revue de code : voici une fonction ### [coller] ###. Relève bugs, failles de sécurité et problèmes de lisibilité, par ordre de gravité. Propose la version corrigée avec commentaires et un test unitaire.

- **À remplacer** : `[coller]`
- **Contexte** : Fonction fournie entre délimiteurs
- **Rôle** : Implicite (relecteur senior)
- **Objectif** : Relever bugs, failles et problèmes de lisibilité
- **Format** : Par ordre de gravité ; version corrigée commentée ; un test unitaire
- **À vérifier** : Exécuter le test proposé. Jamais de secrets (clés, mots de passe) dans le code collé.

### 20. Procédure utilisateur

> Rédige une procédure de [tâche IT] pour un utilisateur non technique : prérequis, étapes numérotées (15 max) avec captures à prévoir, erreurs fréquentes et solutions.

- **À remplacer** : `[tâche IT]`
- **Contexte** : [tâche IT] à documenter pour un public non technique
- **Rôle** : Implicite (rédacteur technique)
- **Objectif** : Rédiger la procédure
- **Format** : Prérequis ; 15 étapes max ; captures à prévoir ; erreurs fréquentes et solutions
- **À vérifier** : Dérouler la procédure sur un poste réel : les menus et libellés changent selon les versions.

Retour à la [bibliothèque complète](bibliotheque.md).
