# Démonstrations images

Deux démonstrations à refaire avec vos propres outils (DALL·E via ChatGPT, Midjourney, Stable Diffusion, Adobe
Firefly, Ideogram…). Les résultats varient d'un outil à l'autre et d'une génération à l'autre : c'est normal, et
c'est l'objet de la première démonstration.

## Démo A — Même prompt, trois IA d'images

Soumettez **exactement** ce prompt à trois outils différents :

```text
Une salle de réunion lumineuse où une équipe découvre l'IA, style photo éditoriale,
lumière naturelle du matin, ratio 16:9
```

Observez et notez pour chaque image :

| Critère | Ce que l'on regarde |
|---|---|
| Respect du prompt | Salle de réunion ? Équipe ? « Découvre l'IA » est-il représenté (écran, robot, rien) ? |
| Style | Photo éditoriale ou rendu 3D / illustration ? |
| Réalisme | Visages, mains, nombre de doigts, reflets, textes sur les écrans |
| Texte parasite | Lettres ou mots inventés sur les affiches, écrans, badges |
| Diversité des personnes | Âges, genres, origines représentés : premier aperçu des **biais** du modèle |

Ce que l'on retient : le même prompt ne produit jamais la même image ; chaque outil a un « style maison » ; les
biais de représentation apparaissent dès que le prompt ne précise rien.

## Démo B — L'échelle du prompt image en 4 niveaux

Même outil, on ajoute une couche à chaque niveau. Lisez chaque prompt **avant** de générer et essayez de prédire le
résultat.

### Niveau 1 — Sujet seul

```text
Une tasse de café
```

Attendu : l'outil choisit tout (style, cadrage, fond, lumière). Résultat générique, souvent un rendu 3D ou une photo
de banque d'images.

### Niveau 2 — + Style

```text
Photographie produit minimaliste d'une tasse de café fumante sur un bureau en bois
```

Attendu : rendu photo, fond épuré, la fumée apparaît. Le cadrage reste au choix de l'outil.

### Niveau 3 — + Composition

```text
Photographie produit minimaliste d'une tasse de café fumante sur un bureau en bois,
gros plan à 45°, fond flou
```

Attendu : point de vue stable, profondeur de champ, la tasse occupe le cadre.

### Niveau 4 — + Lumière, ambiance et paramètres

```text
Photographie produit minimaliste d'une tasse de café fumante sur un bureau en bois,
gros plan à 45°, fond flou, lumière naturelle du matin, tons chauds,
ratio 16:9, haute résolution, sans texte
```

Attendu : image exploitable pour un visuel professionnel (site, présentation) : cohérence de la lumière, format
adapté, pas de texte parasite.

## Les cinq couches d'un prompt image

| Couche | Ce qu'elle précise | Exemple |
|---|---|---|
| Sujet | Quoi, qui, combien, action | une tasse de café fumante sur un bureau en bois |
| Style | Photo, aquarelle, 3D, flat design, référence | photographie produit, style minimaliste |
| Composition | Cadrage, angle, plan, arrière-plan | gros plan, angle 45°, fond flou |
| Lumière et ambiance | Heure, source, couleurs, émotion | lumière naturelle du matin, tons chauds |
| Paramètres | Ratio, résolution, négatifs, version | ratio 16:9, haute résolution, sans texte |

Trois recettes prêtes à coller :

- **Photoréalisme** : `photographie, objectif 50 mm, profondeur de champ, grain léger`
- **Illustration** : `flat design, aplats de couleur, vectoriel, palette pastel`
- **Cohérence de marque** : `même personnage, même palette` + une image de référence

## Précautions

- Pour un usage commercial, vérifiez les conditions d'utilisation de l'outil (droits sur les images générées).
- Ne demandez pas d'imiter une marque, un auteur ou une personne réelle identifiable.
- Signalez qu'une image est générée par IA lorsqu'elle est diffusée.
