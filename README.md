# Créer des prompts efficaces avec l'IA générative

Ressources des participants à la formation Ambient IT d'une journée (7 h) : bibliothèque de prompts, fiches
d'ateliers, grilles, charte, démonstrations commentées, quiz et glossaire.

Le support de cours complet (leçons, programme minuté, quiz interactif, flashcards) est sur le site de la formation ;
ce dépôt contient tout ce que vous copiez, remplissez ou emportez.

## Rien à installer

Tout se lit depuis GitHub. Pour une copie locale :

```bash
git clone https://github.com/formations2026/formation-prompting-ia.git
```

ou **Code → Download ZIP** sur la page du dépôt.

## Plan de la journée

| Horaire | Partie | Atelier | Fichiers utilisés |
|---|---|---|---|
| 9h00 – 10h30 | 1. Introduction aux IA génératives | [Atelier 1 – Même prompt, plusieurs IA](ateliers/atelier-1-comparer-les-ia.md) (30 min) | `grilles/auto-positionnement.md`, `demos/demos-images.md` |
| 10h45 – 12h00 | 2. Fondamentaux du prompting | [Atelier 2 – Reformuler un prompt mal conçu](ateliers/atelier-2-reformuler-un-prompt.md) (30 min) | `demos/01` à `05`, `grilles/checklist-prompt.md`, `prompts/meta-prompts.md` |
| 13h00 – 15h00 | 3. Prompting appliqué aux cas d'usage | [Atelier 3 – Concevoir un prompt métier](ateliers/atelier-3-prompt-metier.md) (45 min) | `prompts/`, `grilles/journal-iterations.md`, `demos/06-prompt-industriel.md` |
| 15h15 – 17h00 | 4. Analyse critique et bonnes pratiques | [Atelier 4 – Comparer, détecter, corriger](ateliers/atelier-4-comparer-detecter-corriger.md) (30 min) | `grilles/grille-evaluation-reponse.md`, `demos/07-hallucination-demasquee.md`, `charte/`, `quiz/` |

## Contenu du dépôt

| Chemin | Contenu |
|---|---|
| [`anti-seche.md`](anti-seche.md) | L'anti-sèche du prompteur : construire, booster, itérer, vérifier, protéger, capitaliser |
| [`prompts/bibliotheque.md`](prompts/bibliotheque.md) | Les 20 prompts métier sur une page, avec variables, structure C.R.O.F. et point à vérifier |
| [`prompts/01-…` à `10-…`](prompts/) | Les mêmes prompts, un fichier par domaine |
| [`prompts/prompts.json`](prompts/prompts.json) | Version structurée, pour un tableur ou une automatisation |
| [`prompts/meta-prompts.md`](prompts/meta-prompts.md) | Le prompt générateur et le prompt d'audit |
| [`prompts/mes-prompts.md`](prompts/mes-prompts.md) | Gabarit pour vos propres prompts et la bibliothèque d'équipe |
| [`ateliers/`](ateliers/) | Les 4 fiches d'atelier : consigne, grille à remplir, exemple de restitution |
| [`grilles/checklist-prompt.md`](grilles/checklist-prompt.md) | La check-list du prompt efficace (9 points) |
| [`grilles/grille-evaluation-reponse.md`](grilles/grille-evaluation-reponse.md) | La grille d'évaluation d'une réponse (5 critères, total /10) |
| [`grilles/journal-iterations.md`](grilles/journal-iterations.md) | Le journal d'itérations de l'atelier 3 |
| [`grilles/auto-positionnement.md`](grilles/auto-positionnement.md) | L'auto-positionnement matin / soir |
| [`demos/`](demos/) | Les démonstrations commentées : sorties réelles d'un modèle de langage, prompts des démonstrations images |
| [`charte/charte-usage-responsable.md`](charte/charte-usage-responsable.md) | La charte en 8 points, à compléter avec les règles de votre entreprise |
| [`quiz/quiz-validation.md`](quiz/quiz-validation.md) · [`quiz/reponses.md`](quiz/reponses.md) | Les 10 questions de validation et leurs réponses commentées |
| [`glossaire.md`](glossaire.md) | Les 16 termes de la formation |

## Les trois règles du dépôt

1. **Remplacez les `[crochets]`** et collez vos données entre délimiteurs `###`.
2. **Ne collez jamais de données personnelles ou confidentielles** dans un outil non validé par votre entreprise ;
   pendant la formation, utilisez des exemples anonymisés ou fictifs.
3. **Testez, puis itérez une fois** : notez le résultat sur 10, modifiez une seule chose, comparez.

## Après la formation

- Réutilisez votre prompt métier de l'atelier 3 dès demain.
- Démarrez une bibliothèque d'équipe à partir de `prompts/mes-prompts.md`.
- Appliquez la grille d'évaluation à chaque résultat important.

Contenu pédagogique © Ambient IT · formation@ambient-it.net · +33 (0)1 48 10 09 46
