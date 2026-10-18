# La check-list du prompt efficace

Neuf cases cochées = un prompt prêt pour la production. À utiliser pour l'atelier 2, puis pour chaque prompt que
vous versez dans votre bibliothèque.

- [ ] Le **contexte** est posé (situation, public, contraintes)
- [ ] Le **rôle** de l'IA est défini
- [ ] L'**objectif** est un verbe d'action + un résultat précis
- [ ] Le **format** attendu est explicite (structure, longueur, ton, langue)
- [ ] Un **exemple** est fourni si le style compte (few-shot)
- [ ] La tâche est **découpée** si elle est complexe (chaîne de prompts)
- [ ] Le **raisonnement** est demandé pour les tâches logiques (chain-of-thought)
- [ ] Les **sources ou outils** à utiliser sont indiqués
- [ ] Je sais comment je vais **vérifier** le résultat

## Les 4 ingrédients, en détail

| Ingrédient | La question à se poser | Exemple |
|---|---|---|
| **Contexte** | Que doit savoir l'IA pour bien répondre ? Situation, public, contraintes. | « Nous sommes une PME de 40 personnes dans le BTP ; nos clients sont des collectivités… » |
| **Rôle** | Quelle casquette doit-elle endosser ? | « Tu es un responsable administratif expérimenté, courtois mais ferme. » |
| **Objectif** | Quelle tâche précise, quel résultat ? Verbe d'action. | « Rédige un e-mail de relance qui obtienne un paiement sous 10 jours. » |
| **Format** | À quoi doit ressembler la sortie ? Longueur, structure, ton, langue. | « 120 mots max, objet inclus, vouvoiement, termine par une proposition d'appel. » |

## Erreurs courantes

| Ce qui fait échouer | Ce qui fait réussir |
|---|---|
| Demande vague : « améliore ce texte » | Verbe d'action + résultat mesurable : « réduis à 100 mots » |
| Plusieurs questions dans un seul prompt | Une tâche par prompt, ou une chaîne de prompts |
| Aucun contexte, aucun public cible | Contexte, rôle, public, contraintes explicites |
| Format de sortie non précisé | Format imposé : liste, tableau, JSON, nombre de mots |
| Négations floues : « ne sois pas trop long » | Contraintes positives et chiffrées |
| Jargon interne non expliqué | Définir les termes ou fournir un glossaire |
| Accepter la première réponse sans la vérifier | Vérifier, puis itérer : 2-3 tours suffisent |
| Continuer une conversation qui dérive | Repartir d'une conversation propre si l'IA s'enlise |
