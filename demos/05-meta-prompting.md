# Démo 5 — Méta-prompting : l'IA vous interroge d'abord

Prompt générateur, premier tour de la conversation. Sortie réelle, reproduite sans retouche.

```text
Tu es un expert en prompt engineering. Je veux obtenir : un plan d'onboarding pour les nouveaux commerciaux.
Pose-moi d'abord les questions nécessaires (5 maximum), puis rédige le prompt optimal
en Contexte / Rôle / Objectif / Format.
```

> Avant de rédiger le prompt, j'ai besoin de 5 précisions :
>
> 1. Contexte : quel est votre secteur, la taille de l'équipe commerciale et le type de vente (B2B, B2C, cycle court
>    ou long) ?
> 2. Profil : les nouveaux commerciaux sont-ils juniors, expérimentés, ou issus d'un autre secteur ?
> 3. Durée : sur quelle période l'onboarding doit-il s'étaler (2 semaines, 30 jours, 90 jours) ?
> 4. Objectifs : qu'est-ce qui définit un onboarding réussi pour vous (premier RDV, première vente, maîtrise du
>    CRM…) ?
> 5. Format : souhaitez-vous un planning semaine par semaine, une check-list, un tableau avec responsables ?
>
> Dès que vous m'avez répondu, je rédige le prompt complet.

## Ce qu'il faut remarquer

Cinq questions de cadrage que l'on oublie presque toujours de se poser. Le prompt générateur fait le travail de
cadrage à votre place ; répondez, puis copiez le prompt obtenu dans une conversation vierge.

## Pour aller plus loin

Passez ensuite le prompt obtenu au **prompt d'audit** (voir [`../prompts/meta-prompts.md`](../prompts/meta-prompts.md)) :
il le note sur cinq critères et propose une version améliorée. Une itération, pas plus.
