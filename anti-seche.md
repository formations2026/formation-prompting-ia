# L'anti-sèche du prompteur

Une page à garder sous la main. Reprend l'essentiel de la journée.

## Construire

- **Contexte** : situation, public, contraintes
- **Rôle** : « Tu es… »
- **Objectif** : verbe d'action + résultat
- **Format** : longueur, structure, ton, langue

## Booster

- Exemples (few-shot)
- « Étape par étape » (chain-of-thought)
- Découper en chaîne de prompts
- Délimiteurs `###` pour les données
- Demander des questions d'abord

## Itérer

- Évaluer, ajuster **une** chose, relancer
- 3 variantes, puis choisir
- Auto-critique : « note-toi /10 »
- Repartir de zéro si ça dérive

## Vérifier

- Pertinence · Exactitude · Complétude · Cohérence · Sources
- Exiger les sources, recouper 2 faits
- Reformuler la question
- Tester les biais (prénom, genre, pays)

## Protéger

- Jamais de données personnelles ou confidentielles
- Outil validé par l'entreprise
- Relecture humaine avant diffusion
- Signaler le contenu généré

## Capitaliser

- Bibliothèque de prompts d'équipe
- Prompt système pour les tâches récurrentes
- Méta-prompting pour les cas nouveaux
- Veille : guides officiels des éditeurs

## Formules qui marchent

| Pour | Formule |
|---|---|
| Cadrer | « Pose-moi des questions avant de répondre » |
| Choisir | « Propose 3 variantes, je choisis » |
| Améliorer | « Critique ta propre réponse, puis améliore-la » |
| Ajuster | « Garde tout, change seulement le ton » |
| Repartir | « Repars de zéro : voici la consigne complète » |
| Cadrer les sources | « Réponds uniquement à partir du document joint ; si l'information n'y est pas, dis-le » |
| Mesurer la confiance | « Indique ton degré de certitude et ce que tu as supposé » |

## Les 10 techniques

1. **Délimiteurs** — séparez consigne et contenu : `###`, `"""` ou `<document>…</document>`
2. **Prompt système** — instructions permanentes (rôle, ton, règles) définies une fois
3. **Questions d'abord** — « Avant de répondre, pose-moi les questions nécessaires »
4. **Contraintes chiffrées** — « 120 mots », « 5 points », « niveau B1 » plutôt que « court »
5. **Format strict** — tableau, JSON, liste numérotée : la sortie se vérifie et se réutilise
6. **Variantes** — « Propose 3 versions différentes », puis choisissez ou combinez
7. **Niveau de confiance** — « Indique ton degré de certitude et ce que tu as supposé »
8. **Public cible** — « Pour un DAF pressé », « pour un stagiaire » : change tout le registre
9. **Interdits explicites** — « Pas de jargon, pas d'emoji, pas de superlatifs »
10. **Auto-critique** — « Relis ta réponse, note-la /10 selon [critères], puis améliore-la »

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

## Ce qu'il faut retenir, en trois blocs

| Comprendre | Prompter | Vérifier |
|---|---|---|
| Une IA générative **prédit**, elle ne sait pas | C.R.O.F. : contexte, rôle, objectif, format | Grille /10 : pertinence, exactitude, complétude, cohérence, sources |
| 3 familles : LLM, image, audio-vidéo | Zero-shot, few-shot, itératif | Exiger les sources, recouper, auto-critique |
| Tokens, contexte, température, date de coupure | Chain-of-thought et chaînes de prompts | RGPD, AI Act, transparence, relecture humaine |
| Limites : hallucinations, biais, confidentialité | Outils externes : web, fichiers, code, API, RAG | Charte en 8 points |
