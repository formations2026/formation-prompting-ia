# Atelier 4 — Comparer, détecter, corriger

**30 min · trinômes · 15h50 – 16h20**

Comparer plusieurs sorties IA, identifier leurs limites et ajuster les prompts pour améliorer la qualité.

**Réussi si** : trois sorties notées sur 10 avec la grille, au moins une hallucination ou un biais documenté avec sa
preuve (source consultée), et un prompt corrigé dont le score est supérieur.

## Consigne

### 1. Choisir un sujet à risque

- Chiffres de marché, point de droit, biographie, conseil médical ou financier.
- **Vérifiable en quelques minutes** : une source officielle accessible. Si vous ne savez pas où vérifier, changez de
  sujet.

Sujet et prompt : ______________________________________________________________

Source de vérification prévue : _________________________________________________

### 2. Générer 3 sorties

- 3 IA différentes… ou 3 fois la même IA dans trois conversations neuves.
- Même prompt, copié à l'identique.

### 3. Évaluer et détecter

- Passez chaque sortie à la [grille d'évaluation](../grilles/grille-evaluation-reponse.md) : pertinence, exactitude,
  complétude, cohérence, sources, chacune de 0 à 2.
- Listez les hallucinations et les biais, **avec la preuve** : la source consultée et ce qu'elle dit réellement.

### 4. Corriger le prompt

- Ajoutez : sources exigées, périmètre fixé, auto-critique, distinction entre ce que l'IA sait et ce qu'elle suppose.
- Régénérez et mesurez le nouveau score.

## Tableau à remplir

| Critère (0-2) | Sortie 1 | Sortie 2 | Sortie 3 | Après correction |
|---|---|---|---|---|
| Pertinence | | | | |
| Exactitude | | | | |
| Complétude | | | | |
| Cohérence | | | | |
| Sources | | | | |
| **Total /10** | | | | |

Hallucinations et biais détectés :

| Sortie | Ce qui est faux ou biaisé | Preuve (source consultée) |
|---|---|---|
| | | |
| | | |

**Prompt corrigé** :

```text

```

## Formules de correction

```text
Réponds uniquement à partir de sources que tu peux citer avec leur nom, date et lien.
Si tu n'as pas de donnée fiable, dis-le explicitement et indique où la chercher.
Distingue ce que tu sais de ce que tu supposes.
Relis ta réponse et liste ce qui pourrait être faux.
```

Pour tester un biais : relancez le même prompt en changeant un prénom, un genre ou un pays, et comparez.

## Questions pour le partage

1. Quelle hallucination ou quel biais vous a le plus surpris ?
2. Quel ajustement du prompt a le mieux réduit le problème ?
3. Que faudrait-il vérifier systématiquement dans votre métier ?
4. Quelle règle ajoutez-vous à votre charte ?

## Exemple de correction (à consulter après l'atelier)

Voir [`../demos/07-hallucination-demasquee.md`](../demos/07-hallucination-demasquee.md) : une statistique inventée
avec une référence plausible (2/10), puis un prompt corrigé qui force l'IA à distinguer ce qu'elle sait de ce
qu'elle suppose (8/10).
