# Owkin data challenge 2023

## TODO

- Chercher des méthodes de Multiple Instance Learning (MIL) : https://en.wikipedia.org/wiki/Multiple_instance_learning
- Trouver un moyen d'attribuer un score à une tile
- Remplacer la logistic regression par un modèle plus complexe de classification binaire
- Idée clustering : 1. On regroupe les tiles en K clusters. 2. Calculer la pureté de chaque cluster 3. Les clusters avec les plus forts % de malades devraient correspondre à un type de tiles importants pour prédire la maladie.

## Side notes

- Arthur a insisté sur le fait que les données pouvaient venir d'un hôpital autre, et que ça avait un gros impact (?)
- Comment utiliser les metadata ?
- léger déséquilibre de classes ⇒ rebalancer ?

## En cours

- PCA (Youri)
- Covariance matrix (Théophile)
- Recherche MIL (Louis)

## References

### MIL
- Site qui fait une review de review https://mars-tin.github.io/archives/reading/multiple_instance/
- Article "Multiple Instance Learning: A Survey of Problem Characteristics and Applications" https://arxiv.org/pdf/1612.03365.pdf
- Site review méthodes https://www.cs.cmu.edu/~juny/MILL/review.htm
- Arcile, ultra cité, "Multiple instance classification: Review, taxonomy and comparative study" https://www.sciencedirect.com/science/article/pii/S0004370213000581
