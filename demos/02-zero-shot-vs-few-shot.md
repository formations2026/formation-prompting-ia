# Démo 2 — Zero-shot vs few-shot

Classer un avis client : sans exemple, puis avec trois exemples. Sorties réelles, reproduites sans retouche.

## Zero-shot (sans exemple)

```text
Classe ce commentaire client : « Livraison rapide, mais le carton était abîmé et personne ne répond au téléphone. »
```

> Ce commentaire est plutôt négatif, même s'il contient un point positif.
> Point positif : la rapidité de la livraison.
> Points négatifs : l'emballage endommagé et l'impossibilité de joindre le service client.
> Les aspects négatifs dominent, notamment le manque de réactivité du service client, qui est souvent un facteur
> important d'insatisfaction.

Juste, mais en prose : impossible à traiter en masse.

## Few-shot (3 exemples)

```text
Classe chaque avis au format SENTIMENT | NOTE /5 | THÈME.
« Parfait, je recommande » → POSITIF | 5 | Global
« Produit correct, sans plus » → NEUTRE | 3 | Produit
« Remboursement toujours pas reçu » → NÉGATIF | 1 | SAV
« Livraison rapide, mais le carton était abîmé et personne ne répond au téléphone. » →
```

> NÉGATIF | 2 | Logistique, SAV

Une ligne, toujours au même format : prête pour un tableur.

## Ce qu'il faut remarquer

- Le zero-shot donne une bonne analyse, inexploitable pour 500 commentaires.
- Le few-shot impose le format **par l'exemple** : la sortie se colle directement dans Excel.
- À tester avec vos propres données — anonymisées.
