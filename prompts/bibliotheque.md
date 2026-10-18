# Bibliothèque : 20 prompts métier prêts à l'emploi

**Mode d'emploi** : Remplacez les [crochets], collez vos données entre délimiteurs ###, testez, puis itérez une fois. Ne collez jamais de données personnelles ou confidentielles dans un outil non validé par votre entreprise.

Chaque prompt est construit sur C.R.O.F. : Contexte, Rôle, Objectif, Format. Les blocs ci-dessous donnent le prompt à copier, les
variables à remplacer, la décomposition en quatre ingrédients et le point de contrôle propre au prompt.

Version structurée : [`prompts.json`](prompts.json). Un fichier par domaine dans ce dossier.

## Ressources humaines

### 1. Fiche de poste

> Tu es DRH d'une PME de [secteur]. Rédige une fiche de poste pour [intitulé] : missions (5 max), compétences requises et souhaitées, conditions, phrase d'accroche inclusive. 250 mots, ton professionnel et engageant.

- **À remplacer** : `[secteur]`, `[intitulé]`
- **Contexte** : PME de [secteur]
- **Rôle** : DRH
- **Objectif** : Rédiger une fiche de poste pour [intitulé]
- **Format** : Missions (5 max), compétences requises/souhaitées, conditions, accroche inclusive ; 250 mots ; ton professionnel et engageant
- **À vérifier** : Les missions sont-elles réalistes pour le poste ? L'accroche évite-t-elle les formulations genrées ?

### 2. Grille d'entretien

> Prépare 8 questions d'entretien pour un poste de [X], dont 3 situationnelles. Pour chaque question, indique ce qu'une bonne réponse doit contenir et un signal d'alerte. Format : tableau.

- **À remplacer** : `[X]`
- **Contexte** : Recrutement pour un poste de [X]
- **Rôle** : Implicite (recruteur) — à préciser si besoin
- **Objectif** : Préparer 8 questions d'entretien dont 3 situationnelles
- **Format** : Tableau : question / contenu attendu / signal d'alerte
- **À vérifier** : Aucune question discriminatoire (âge, situation familiale, santé, origine) ?

## Marketing & Communication

### 3. Post LinkedIn ×3

> Tu es responsable communication de [marque]. Rédige 3 variantes d'un post LinkedIn annonçant [actualité] : factuelle, storytelling, question d'ouverture. 120 mots max chacune, 3 hashtags, pas d'emoji.

- **À remplacer** : `[marque]`, `[actualité]`
- **Contexte** : Annonce de [actualité] pour [marque]
- **Rôle** : Responsable communication
- **Objectif** : Rédiger 3 variantes d'un post LinkedIn
- **Format** : 3 angles (factuel, storytelling, question) ; 120 mots max ; 3 hashtags ; pas d'emoji
- **À vérifier** : Les faits annoncés sont-ils exacts ? Le ton correspond-il à la charte de la marque ?

### 4. Newsletter

> À partir de ces 3 actualités ### [coller] ###, rédige la newsletter mensuelle : objet (≤ 50 caractères), intro de 2 phrases, 3 blocs de 60 mots avec appel à l'action. Ton : [chaleureux].

- **À remplacer** : `[coller]`, `[chaleureux]`
- **Contexte** : 3 actualités fournies entre délimiteurs
- **Rôle** : Implicite (rédacteur de la newsletter)
- **Objectif** : Rédiger la newsletter mensuelle
- **Format** : Objet ≤ 50 caractères ; intro 2 phrases ; 3 blocs de 60 mots avec appel à l'action ; ton [chaleureux]
- **À vérifier** : Chaque bloc reprend-il fidèlement l'actualité source ? Les appels à l'action pointent-ils vers des liens existants ?

## Vente & Commercial

### 5. E-mail de prospection

> Tu es commercial B2B. Rédige un e-mail de prospection à [fonction] chez [type d'entreprise] pour [offre]. Accroche personnalisée sur [enjeu du prospect], 1 bénéfice chiffré, 1 question finale. 90 mots max.

- **À remplacer** : `[fonction]`, `[type d'entreprise]`, `[offre]`, `[enjeu du prospect]`
- **Contexte** : Prospection de [fonction] chez [type d'entreprise], enjeu : [enjeu du prospect]
- **Rôle** : Commercial B2B
- **Objectif** : Rédiger un e-mail de prospection pour [offre]
- **Format** : Accroche personnalisée ; 1 bénéfice chiffré ; 1 question finale ; 90 mots max
- **À vérifier** : Le bénéfice chiffré est-il réel et sourçable ? Pas de promesse que l'offre ne tient pas ?

### 6. Traitement des objections

> Liste les 6 objections les plus probables d'un [prospect] face à [offre]. Pour chacune : une réponse en 2 phrases et une question de relance. Format : tableau.

- **À remplacer** : `[prospect]`, `[offre]`
- **Contexte** : [prospect] face à [offre]
- **Rôle** : Implicite (commercial expérimenté) — à préciser si besoin
- **Objectif** : Anticiper 6 objections et préparer les réponses
- **Format** : Tableau : objection / réponse en 2 phrases / question de relance
- **À vérifier** : Les réponses restent-elles honnêtes sur les limites de l'offre ?

## Finance & Gestion

### 7. Analyse d'écarts

> Voici un tableau de charges N et N-1 ### [coller] ###. Identifie les 5 postes en plus forte hausse, explique les causes possibles, propose 3 actions. Tableau chiffré puis synthèse de 100 mots pour la direction.

- **À remplacer** : `[coller]`
- **Contexte** : Tableau de charges N et N-1 fourni entre délimiteurs
- **Rôle** : Implicite (contrôleur de gestion)
- **Objectif** : Identifier les 5 postes en plus forte hausse, expliquer, proposer 3 actions
- **Format** : Tableau chiffré puis synthèse de 100 mots pour la direction
- **À vérifier** : Recalculer les 5 écarts à la main ou avec l'exécution de code : l'IA se trompe parfois sur les pourcentages. Données anonymisées uniquement.

### 8. Formule Excel

> Explique pas à pas comment construire dans Excel une formule qui [objectif], avec un exemple sur ces données ### [coller] ###. Donne la formule finale, ses limites et une alternative.

- **À remplacer** : `[objectif]`, `[coller]`
- **Contexte** : Données d'exemple fournies entre délimiteurs
- **Rôle** : Implicite (expert Excel)
- **Objectif** : Construire une formule qui [objectif]
- **Format** : Explication pas à pas ; formule finale ; limites ; alternative
- **À vérifier** : Tester la formule sur les données d'exemple avant de la généraliser ; vérifier la version d'Excel (fonctions récentes).

## Support client

### 9. Réponse à une réclamation

> Tu es conseiller clientèle de [entreprise]. Réponds à cette réclamation ### [coller] ### : empathie, reformulation du problème, solution concrète, délai, formule de politesse. 120 mots, vouvoiement, sans jargon.

- **À remplacer** : `[entreprise]`, `[coller]`
- **Contexte** : Réclamation client fournie entre délimiteurs, pour [entreprise]
- **Rôle** : Conseiller clientèle
- **Objectif** : Répondre à la réclamation
- **Format** : Empathie, reformulation, solution, délai, politesse ; 120 mots ; vouvoiement ; sans jargon
- **À vérifier** : La solution et le délai proposés sont-ils tenables ? Anonymiser la réclamation avant de la coller.

### 10. FAQ à partir de tickets

> À partir de ces 20 tickets ### [coller] ###, regroupe les questions par thème, rédige une FAQ de 10 entrées (question + réponse de 40 mots) et signale les questions sans réponse claire.

- **À remplacer** : `[coller]`
- **Contexte** : 20 tickets de support fournis entre délimiteurs
- **Rôle** : Implicite (responsable support)
- **Objectif** : Produire une FAQ de 10 entrées et signaler les questions ouvertes
- **Format** : Regroupement par thème ; 10 entrées question + réponse de 40 mots ; liste des questions sans réponse
- **À vérifier** : Chaque réponse de FAQ est-elle validée par le métier ? Les tickets sont-ils anonymisés ?

## Management & Projet

### 11. Compte rendu de réunion

> Voici mes notes de réunion ### [coller] ###. Rédige un compte rendu : décisions, actions en tableau (qui / quoi / quand), points ouverts. 200 mots max. Signale les ambiguïtés plutôt que de les trancher.

- **À remplacer** : `[coller]`
- **Contexte** : Notes brutes de réunion fournies entre délimiteurs
- **Rôle** : Implicite (assistant de direction)
- **Objectif** : Rédiger un compte rendu structuré
- **Format** : Décisions ; actions en tableau qui/quoi/quand ; points ouverts ; 200 mots max ; garde-fou sur les ambiguïtés
- **À vérifier** : Relire les actions attribuées : l'IA peut attribuer une tâche à la mauvaise personne si les notes sont elliptiques.

### 12. Plan de projet

> Tu es chef de projet. Découpe [projet] en phases et jalons sur [durée], avec pour chaque phase : livrable, risque majeur et parade. Format : tableau, puis les 3 décisions à prendre cette semaine.

- **À remplacer** : `[projet]`, `[durée]`
- **Contexte** : [projet] à réaliser sur [durée]
- **Rôle** : Chef de projet
- **Objectif** : Découper en phases et jalons
- **Format** : Tableau phase / livrable / risque / parade ; puis 3 décisions de la semaine
- **À vérifier** : Les durées par phase sont-elles cohérentes avec vos ressources réelles ?

## Juridique & Conformité

### 13. Vulgarisation d'une clause

> Explique cette clause ### [coller] ### à un non-juriste en 5 points, puis liste 3 questions à poser à un avocat. Ne donne pas de conseil définitif ; signale explicitement les points incertains.

- **À remplacer** : `[coller]`
- **Contexte** : Clause contractuelle fournie entre délimiteurs
- **Rôle** : Implicite (juriste pédagogue)
- **Objectif** : Expliquer la clause à un non-juriste
- **Format** : 5 points ; 3 questions pour un avocat ; pas de conseil définitif ; points incertains signalés
- **À vérifier** : L'IA ne remplace pas un avis juridique. Vérifier toute référence à un article de loi cité.

### 14. Check-list RGPD

> Pour un projet de [description], établis une check-list RGPD de 10 points (base légale, minimisation, durée de conservation, droits des personnes, sous-traitants…). Pour chaque point : oui / non / à vérifier.

- **À remplacer** : `[description]`
- **Contexte** : Projet de [description]
- **Rôle** : Implicite (DPO)
- **Objectif** : Établir une check-list RGPD
- **Format** : 10 points ; pour chacun oui / non / à vérifier
- **À vérifier** : Faire valider la check-list par le DPO ou le juriste de l'entreprise.

## Data & Analyse

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

## Formation & Pédagogie

### 17. Module de formation

> Tu es ingénieur pédagogique. Conçois un module de 2 h sur [sujet] pour [public] : objectifs (verbes d'action), séquence minutée, 1 activité pratique, 5 questions de quiz avec réponses.

- **À remplacer** : `[sujet]`, `[public]`
- **Contexte** : Module de 2 h sur [sujet] pour [public]
- **Rôle** : Ingénieur pédagogique
- **Objectif** : Concevoir le module
- **Format** : Objectifs en verbes d'action ; séquence minutée ; 1 activité ; 5 questions de quiz avec réponses
- **À vérifier** : Les réponses du quiz sont-elles exactes ? Le minutage tient-il en 2 h avec les transitions ?

### 18. Flashcards

> Crée 10 flashcards sur [sujet] : question au recto, réponse en 2 phrases au verso, du plus simple au plus difficile. Format : tableau à 2 colonnes.

- **À remplacer** : `[sujet]`
- **Contexte** : [sujet] à réviser
- **Rôle** : Implicite (formateur)
- **Objectif** : Créer 10 flashcards progressives
- **Format** : Tableau 2 colonnes recto / verso ; réponse en 2 phrases ; difficulté croissante
- **À vérifier** : Vérifier chaque réponse : une flashcard fausse s'apprend aussi bien qu'une vraie.

## IT & Développement

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
