# Méta-prompting : l'IA écrit votre prompt

L'IA est excellente pour rédiger des prompts. Deux outils à garder dans votre bibliothèque.

## Le prompt générateur

Il construit le prompt à votre place. Répondez aux questions, copiez le prompt obtenu dans une conversation vierge,
gardez-le.

```text
Tu es un expert en prompt engineering. Je veux obtenir : [décrivez votre besoin en une phrase].
Pose-moi d'abord les questions nécessaires (5 maximum) pour bien comprendre mon contexte, mon public
et le résultat attendu. Ensuite, rédige le prompt optimal, structuré en Contexte / Rôle / Objectif / Format,
que je pourrai copier-coller dans une nouvelle conversation.
```

## Le prompt d'audit

Il améliore un prompt existant. Lisez la critique, comparez les deux versions sur un cas réel, itérez une fois, pas
plus.

```text
Voici un prompt que j'utilise : [collez votre prompt].
Évalue-le de 0 à 10 sur cinq critères : clarté de l'objectif, contexte fourni, rôle, format de sortie,
risques d'ambiguïté. Pour chaque critère, explique le problème en une phrase.
Puis propose une version améliorée et indique ce que tu as changé et pourquoi.
```

## Formules qui marchent

- « Pose-moi des questions avant de répondre »
- « Propose 3 variantes, je choisis »
- « Critique ta propre réponse, puis améliore-la »
- « Garde tout, change seulement le ton »
- « Repars de zéro : voici la consigne complète »
- « Réponds uniquement à partir du document joint ; si l'information n'y est pas, dis-le »
- « Indique ton degré de certitude et ce que tu as supposé »

Exemple de premier tour du prompt générateur : [`../demos/05-meta-prompting.md`](../demos/05-meta-prompting.md).
