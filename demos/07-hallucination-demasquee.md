# Démo 7 — Une hallucination démasquée

Une question qui appelle un chiffre que le modèle ne connaît pas. Cet exemple a été construit pour la formation ;
le mécanisme, lui, se reproduit tous les jours : une question « chiffrée » sans source produit une statistique
inventée avec une référence plausible. Refaites-le avec votre outil et comparez.

## Le prompt initial

```text
Quel pourcentage des PME françaises utilisent l'IA générative ?
```

> Selon une étude du cabinet Delorme & Associés publiée en mars 2024, 73,4 % des PME françaises utilisent déjà l'IA
> générative au quotidien, un chiffre en hausse de 41 points par rapport à 2023.

## Les signaux d'alerte

| Signal | Dans la réponse |
|---|---|
| Source introuvable | Le cabinet et l'étude n'existent pas ; le nom est plausible, la date précise rend l'ensemble crédible |
| Précision suspecte | 73,4 % avec une décimale, sur une question qu'aucune enquête ne tranche aussi nettement |
| Chiffre invraisemblable | Une hausse de 41 points en un an |
| Aucun lien, aucune méthodologie | Rien à ouvrir, rien à recouper |
| Instabilité | La question reposée autrement donne un autre chiffre (58 %) |

Score à la [grille d'évaluation](../grilles/grille-evaluation-reponse.md) : **2/10**
(pertinence 1 · exactitude 0 · complétude 1 · cohérence 0 · sources 0).

## Le prompt corrigé

```text
Quel pourcentage des PME françaises utilisent l'IA générative ?
Réponds uniquement à partir de sources que tu peux citer avec leur nom, date et lien.
Si tu n'as pas de donnée fiable, dis-le explicitement et indique où la chercher.
Distingue ce que tu sais de ce que tu supposes.
```

> Je n'ai pas de chiffre fiable et daté pour 2026. Les baromètres publics (Bpifrance, INSEE, France Num) publient des
> enquêtes annuelles : je vous conseille de consulter leur dernière édition. Ce que je peux dire avec certitude :
> l'adoption progresse fortement depuis 2023.

Score : **8/10** (pertinence 2 · exactitude 2 · complétude 1 · cohérence 2 · sources 1). Les organismes cités sont
réels et publient effectivement sur le sujet ; la réponse ne donne aucun chiffre qu'elle ne peut pas sourcer.

## Ce qu'il faut remarquer

- Une réponse « je ne sais pas » bien orientée vaut mieux qu'un chiffre inventé.
- Trois consignes suffisent pour passer de 2/10 à 8/10 : exiger des sources nommées, autoriser « je ne sais pas »,
  distinguer le su du supposé.
- L'hallucination n'est pas une panne du modèle : c'est le résultat prévisible d'un prompt qui réclame une réponse à
  tout prix.

## À faire chez vous

Posez à votre outil une question chiffrée de votre secteur (part de marché, taux, délai réglementaire). Notez la
réponse avec la grille, puis reposez la question avec le prompt corrigé. Consignez l'écart dans votre
[journal d'itérations](../grilles/journal-iterations.md).
