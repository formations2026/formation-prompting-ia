# Quiz de validation — réponses et explications

À consulter **après** avoir répondu au [quiz](quiz-validation.md).

| Question | Réponse | Pour relire |
|---|---|---|
| 1 | **b** | Partie 1 — Comment fonctionne un modèle de langage |
| 2 | **b** | Partie 1 — Tokens et fenêtre de contexte |
| 3 | **a** | Partie 1 — Les paramètres : température |
| 4 | **b** | Partie 2 — Zero-shot, few-shot ; démo 2 |
| 5 | **b** | Partie 2 — La méthode C.R.O.F. ; démo 1 |
| 6 | **a** | Partie 2 — Chain-of-thought ; démo 3 |
| 7 | **b** | Partie 4 — Hallucinations ; démo 7 |
| 8 | **b** | Partie 4 — Cadre éthique et usage responsable ; charte |
| 9 | **a** | Partie 1 et partie 3 — RAG ; démo 4 |
| 10 | **b** | Partie 4 — Grille d'évaluation en 5 critères |

## Explications

**1 — b.** Un modèle génératif prédit le token suivant à partir des régularités apprises pendant l'entraînement. Il
ne consulte pas une base de faits et ne « comprend » pas au sens humain : c'est pour cela que la qualité de la
réponse dépend autant de la qualité du prompt, et qu'une réponse fluide peut être fausse.

**2 — b.** Le modèle lit et produit des tokens, des fragments de texte d'environ ¾ de mot en moyenne. C'est l'unité
de la fenêtre de contexte et de la facturation : un texte de 500 mots représente des centaines de tirages successifs.

**3 — a.** La température règle la part de hasard dans le choix du token suivant. Haute : réponses plus variées et
créatives, mais plus risquées. Basse : réponses stables et répétables, ce que l'on recherche pour une tâche
automatisée.

**4 — b.** Few-shot : on fournit 2 à 5 exemples du résultat attendu. C'est le moyen le plus sûr d'imposer un format,
un style ou un barème, comme dans la démonstration de classement d'avis clients au format
`SENTIMENT | NOTE /5 | THÈME`.

**5 — b.** C.R.O.F. : le **Contexte** (situation, public, contraintes), le **Rôle** que l'IA endosse, l'**Objectif**
(verbe d'action + résultat précis) et le **Format** attendu (longueur, structure, ton, langue). Un prompt sans format
laisse l'IA choisir le sien, rarement le bon.

**6 — a.** « Raisonne étape par étape, puis vérifie » : expliciter le raisonnement améliore les tâches logiques et de
calcul, et surtout rend l'erreur visible à l'étape où elle apparaît. À ne pas confondre avec la chaîne de prompts,
qui découpe une tâche en sous-tâches successives.

**7 — b.** L'hallucination est une réponse fausse ou inventée (chiffre, référence, citation, loi) présentée avec
aplomb. Signaux d'alerte : chiffre très précis sans source, référence introuvable, ton péremptoire. Réflexe : exiger
les sources et recouper deux faits.

**8 — b.** Un prompt contenant des données personnelles est un traitement au sens du RGPD, et ce que l'on saisit
dans un outil public peut être stocké ou réutilisé. Règle : outil validé par l'entreprise (offre entreprise ou modèle
hébergé en interne), sinon on n'y colle rien de personnel ni de confidentiel.

**9 — a.** Retrieval-Augmented Generation : les documents de l'entreprise sont indexés, les passages pertinents sont
récupérés puis injectés dans le contexte du modèle, qui répond en s'appuyant dessus. Moins d'hallucinations, des
réponses sourcées, sans ré-entraîner le modèle.

**10 — b.** L'aisance n'est pas une preuve. On passe la réponse à la grille d'évaluation (pertinence, exactitude,
complétude, cohérence, sources, chacune notée de 0 à 2), on recoupe deux faits et on relit avant toute diffusion.
