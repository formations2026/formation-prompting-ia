# Atelier 3 — Concevoir un prompt métier

**45 min · individuel ou binôme métier · 14h05 – 14h50**

Concevoir un prompt « métier » (texte, code, image ou vidéo) et l'optimiser par itérations successives.

**Réussi si** : un prompt final que vous réutiliserez, un journal où chaque ligne ne change qu'une chose et porte
une note, et une estimation du temps gagné par semaine.

## Consigne

### 1. Choisir

- Un besoin **réel** de votre poste.
- Un domaine : texte, code, image ou vidéo.
- Un résultat que vous sauriez juger.

Besoin choisi : ______________________________________________________________

### 2. Construire la v1

- Contexte · Rôle · Objectif · Format (voir la [check-list](../grilles/checklist-prompt.md)).
- Un exemple si le style compte (few-shot).
- Vous pouvez partir d'un prompt proche dans la [bibliothèque](../prompts/bibliotheque.md), ou laisser l'IA vous
  interroger avec le [prompt générateur](../prompts/meta-prompts.md).
- Soumettre, puis noter le résultat sur 10.

### 3. Itérer (3 fois maximum)

- **Une seule modification par itération** : ajouter un format, préciser le public, poser un garde-fou, demander le
  raisonnement, fournir un exemple…
- Noter ce qui change et le gain.
- S'arrêter quand le gain devient faible ; annuler une itération qui n'apporte rien.

### 4. Restituer

- Le prompt final et le journal d'itérations.
- Le « déclic » de l'atelier.
- Ce que vous automatiseriez si vous le pouviez.

Données : utilisez des exemples **anonymisés ou fictifs** si votre cas réel contient des informations personnelles ou
confidentielles.

## Journal d'itérations

Version longue à remplir : [`../grilles/journal-iterations.md`](../grilles/journal-iterations.md).

| Version | Modification apportée | Note /10 | Gain |
|---|---|---|---|
| v1 | — | | — |
| v2 | | | |
| v3 | | | |
| v4 | | | |

**Prompt final** :

```text

```

Temps gagné estimé par semaine : ____________

## Questions pour la restitution

1. Quelle itération a produit le plus gros gain ? Quel ingrédient a changé ?
2. Qu'est-ce que l'IA n'a jamais réussi à faire correctement ?
3. Combien de temps ce prompt vous fera-t-il gagner par semaine ?
4. Quels prompts mériteraient une bibliothèque partagée dans l'équipe ?

## Exemple de journal (à consulter après l'atelier)

Cas : le compte rendu de réunion.

| Version | Modification apportée | Note /10 | Gain |
|---|---|---|---|
| v1 | « Fais un compte rendu de ces notes » | 4 | — |
| v2 | + Format : décisions / actions en tableau (qui, quoi, quand) / points ouverts | 7 | +3 |
| v3 | + Contexte et public : « pour le directeur qui n'était pas présent, 200 mots max » | 8,5 | +1,5 |
| v4 | + Garde-fou : « signale les ambiguïtés plutôt que de les trancher » | 9 | +0,5 |
| v5 | + Changement de ton (tenté) : « plus chaleureux » | 8,5 | −0,5 → on garde v4 |

**Prompt final (v4)**

> Tu es l'assistant du directeur de [service]. Voici mes notes brutes de réunion ### [coller] ###. Rédige pour le
> directeur, absent, un compte rendu de 200 mots max : 1) décisions, 2) actions en tableau (qui / quoi / quand),
> 3) points ouverts. Signale les ambiguïtés plutôt que de les trancher.

Gain estimé : 20 minutes par réunion × 4 réunions par semaine ≈ 1 h 20 par semaine.

Ce qui fait la qualité du journal : une seule modification par ligne, un score, et le courage d'annuler une
itération qui n'apporte rien (v5). Le gain décroît : on s'arrête à v4.
