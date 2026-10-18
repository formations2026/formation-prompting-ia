# Glossaire : 16 mots pour parler IA

| Terme | Définition |
|---|---|
| **LLM** | *Large Language Model* : modèle de langage entraîné sur d'immenses corpus de texte. |
| **Token** | Unité de texte (≈ ¾ de mot) que le modèle lit et produit ; base de la facturation. |
| **Fenêtre de contexte** | Quantité de texte que le modèle peut prendre en compte en une fois. |
| **Température** | Réglage du hasard : basse = stable, haute = créatif. |
| **Hallucination** | Réponse fausse ou inventée, formulée avec assurance. |
| **Prompt système** | Instructions permanentes qui cadrent toute la conversation. |
| **Zero-shot / few-shot** | Prompt sans / avec exemples du résultat attendu. |
| **Chain-of-thought** | Demander au modèle de raisonner étape par étape. |
| **RAG** | *Retrieval-Augmented Generation* : l'IA répond à partir de documents indexés. |
| **Fine-tuning** | Ré-entraîner un modèle sur vos données pour le spécialiser. |
| **Multimodal** | Modèle qui traite texte, image, audio (et vidéo) en entrée et en sortie. |
| **Agent** | IA qui enchaîne de façon autonome des étapes et des outils vers un objectif. |
| **Function calling** | Capacité du modèle à appeler des outils ou API décrits dans le prompt. |
| **Diffusion** | Technique de génération d'images par débruitage progressif. |
| **Deepfake** | Contenu synthétique imitant une personne réelle (voix, visage). |
| **AI Act** | Règlement européen sur l'IA : obligations graduées selon le risque. |

## Autres termes rencontrés pendant la journée

| Terme | Définition |
|---|---|
| **C.R.O.F.** | Contexte, Rôle, Objectif, Format : les quatre ingrédients d'un prompt efficace. |
| **Prompt** | L'instruction en langage naturel donnée à une IA générative ; pour une IA de voix, le script lui-même. |
| **Date de coupure** | Fin des données d'entraînement d'un modèle ; il ne connaît rien de postérieur sans outil de recherche. |
| **Poids ouverts** | Modèle dont les paramètres sont téléchargeables, exécutable en local ou chez un hébergeur de son choix. |
| **Chaîne de prompts** | Découpage d'une tâche complexe en sous-tâches successives, chaque sortie alimentant le prompt suivant. |
| **Méta-prompting** | Demander à l'IA d'écrire ou d'auditer un prompt. |
| **Délimiteurs** | Marqueurs (`###`, `"""`, balises) qui séparent la consigne du contenu à traiter. |
| **Prompt négatif** | Ce que l'on ne veut pas voir dans une image générée (`--no` sur Midjourney, champ dédié sur Stable Diffusion). |
| **Transformer** | Architecture de réseau de neurones publiée en 2017, à la base des grands modèles de langage actuels. |
| **Embeddings** | Représentation numérique d'un texte (vecteur) qui permet de retrouver les passages proches d'une question ; brique du RAG. |
| **Biais** | Tendance d'un modèle à reproduire les stéréotypes de ses données d'entraînement. |
| **Traitement de données (RGPD)** | Toute opération sur des données personnelles, y compris les saisir dans un prompt. |

## Pour aller plus loin

- Guides officiels de prompting : OpenAI, Anthropic, Google et Mistral publient des guides gratuits et à jour.
- Cadre juridique : CNIL (IA et RGPD), AI Act de l'Union européenne, charte interne de votre entreprise.
- Bibliothèque d'équipe : centraliser et versionner les prompts validés (gabarit : `prompts/mes-prompts.md`).
- Formations Ambient IT : IA générative avancée, agents, RAG, automatisation, outils métier —
  formation@ambient-it.net · 01 48 10 09 46.
