# Démo 1 — Prompt vague vs prompt C.R.O.F.

Même besoin, même IA, deux prompts. Sorties réelles, reproduites sans retouche.

## Prompt vague

```text
Fais-moi un mail de relance pour une facture.
```

> Objet : Relance – Facture n° [numéro] en attente de règlement
>
> Bonjour [Nom du client],
>
> Sauf erreur de notre part, nous n'avons pas encore reçu le règlement de la facture n° [numéro] d'un montant de
> [montant] €, arrivée à échéance le [date].
>
> Pourriez-vous vérifier de votre côté et procéder au paiement dans les meilleurs délais ? Si le règlement a déjà été
> effectué, merci de ne pas tenir compte de ce message.
>
> Cordialement,
> [Votre nom]

Six trous à combler · aucune stratégie · ton par défaut.

## Prompt C.R.O.F.

```text
Contexte : PME BTP, client collectivité, facture de 12 000 € en retard de 45 jours.
Rôle : responsable administratif courtois mais ferme.
Objectif : paiement sous 10 jours sans dégrader la relation.
Format : 120 mots max, objet inclus, vouvoiement, proposer un appel.
```

> Objet : Facture n° [n°] – règlement attendu sous 10 jours
>
> Madame, Monsieur,
>
> Notre facture n° [n°] d'un montant de 12 000 € reste impayée à ce jour, 45 jours après son échéance.
>
> Nous tenons à la qualité de notre collaboration et souhaitons régler ce point simplement : nous vous remercions de
> procéder au virement d'ici le [date J+10].
>
> Si une difficulté administrative bloque le paiement, je vous propose un court échange téléphonique cette semaine
> pour la lever ensemble.
>
> Bien cordialement,
> [Nom], responsable administratif

Montant, délai, ton, appel : tout y est · prêt à 90 %.

## Ce qu'il faut remarquer

1. Le prompt vague donne une réponse correcte mais remplie de crochets : l'IA ne sait rien, donc elle laisse des
   trous — ou, pire, invente.
2. Le prompt structuré intègre montant, retard, ton, délai et la proposition d'appel.
3. L'IA n'a **pas** inventé de numéro de facture : elle a laissé `[n°]`. Bon réflexe à souligner.

## La version longue du prompt C.R.O.F.

```text
Nous sommes une PME de 40 personnes dans le BTP ; nos clients sont des collectivités. Un client a une facture
de 12 000 € en retard de 45 jours.
Tu es un responsable administratif expérimenté, courtois mais ferme.
Rédige un e-mail de relance qui obtienne un paiement sous 10 jours sans dégrader la relation.
Format : 120 mots max, objet d'e-mail inclus, ton professionnel, vouvoiement, une seule demande claire,
termine par une proposition d'appel.
```
