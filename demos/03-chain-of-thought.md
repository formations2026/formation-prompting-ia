# Démo 3 — Chain-of-thought : une réponse que l'on peut vérifier

Un calcul avec un piège : le formateur mange aussi. Sorties réelles, reproduites sans retouche.

## Réponse directe

```text
Une salle coûte 450 € la journée. Au-delà de 8 participants, chaque participant supplémentaire coûte 35 €.
Le traiteur facture 18 € par personne, formateur inclus. Coût total pour 11 participants ?
Donne seulement le résultat.
```

> 771 €

Juste… mais comment le savoir sans refaire le calcul ?

## Avec « étape par étape »

```text
Une salle coûte 450 € la journée. Au-delà de 8 participants, chaque participant supplémentaire coûte 35 €.
Le traiteur facture 18 € par personne, formateur inclus. Coût total pour 11 participants ?
Raisonne étape par étape, puis vérifie.
```

> 1. Salle : 450 €
> 2. Participants au-delà de 8 : 11 − 8 = 3 → 3 × 35 € = 105 €
> 3. Repas : 11 participants + 1 formateur = 12 personnes → 12 × 18 € = 216 €
> 4. Total : 450 + 105 + 216 = 771 €
> Vérification : 555 € (salle) + 216 € (traiteur) = 771 € ✓

Chaque étape se contrôle : le piège est visible.

## Ce qu'il faut remarquer

Les deux réponses sont justes, mais seule la seconde est vérifiable : on voit immédiatement que le formateur a bien
été compté dans le traiteur (12 repas et non 11), le piège classique de l'énoncé. En situation réelle, c'est à cette
étape que l'on repère une erreur.

## Un second exemple

```text
Un abonnement coûte 29 €/mois avec 2 mois offerts la première année. Avant de donner le coût annuel,
détaille chaque étape de ton calcul, puis vérifie-le.
```

Attendu : 12 − 2 = 10 mois facturés → 10 × 29 = 290 € → vérification : OK.
