# Démo 6 — Un prompt « industriel » : tri automatique d'e-mails

Prompt système destiné à une automatisation (sans humain dans la boucle) : la sortie doit être machine-lisible,
toujours au même format, et le cas d'erreur est prévu. Sorties réelles, reproduites sans retouche.

## Le prompt système

```text
Tu es un assistant de tri du support client d'un éditeur de logiciel RH.
Pour chaque e-mail reçu, réponds UNIQUEMENT avec un JSON valide :
{
  "categorie": "bug" | "facturation" | "demande_fonctionnalite" | "autre",
  "priorite": 1 | 2 | 3,
  "resume": "<une phrase, 20 mots max>",
  "action": "<prochaine action pour l'équipe>"
}
Si l'e-mail est ambigu, choisis "autre" et priorite 2.
N'ajoute aucun texte hors du JSON.
```

## Test 1

```text
Bonjour, depuis la mise à jour d'hier impossible d'exporter les bulletins de paie, ça bloque tout le service,
on paye les salaires jeudi !
```

> ```json
> {
>   "categorie": "bug",
>   "priorite": 1,
>   "resume": "Export des bulletins de paie bloqué depuis la mise à jour, paie prévue jeudi.",
>   "action": "Escalader immédiatement à l'équipe technique, contacter le client sous 1 h."
> }
> ```

## Test 2

```text
Est-ce que vous pourriez ajouter un mode sombre ? Merci.
```

> ```json
> {
>   "categorie": "demande_fonctionnalite",
>   "priorite": 3,
>   "resume": "Demande d'ajout d'un mode sombre à l'interface.",
>   "action": "Enregistrer dans le backlog produit et remercier le client."
> }
> ```

## Ce qu'il faut remarquer

- La contrainte « UNIQUEMENT un JSON valide » est respectée : la sortie est directement exploitable par un outil.
- Le cas ambigu est prévu dans le prompt : c'est ce qui distingue un prompt d'automatisation d'un prompt de
  conversation.
- Priorité correcte dans les deux cas : l'urgence paie est en priorité 1, la demande esthétique en 3.

## À retenir pour vos propres prompts d'automatisation

1. Spécifier le format de sortie **exactement** (schéma, valeurs autorisées).
2. Prévoir le cas « je ne sais pas » / « ambigu ».
3. Interdire tout texte hors format.
4. Tester avec au moins un cas limite avant de mettre en production.
