# 04 — SNARK, R1CS et engagements polynomiaux

Lambdaworks contient aussi des briques SNARK, notamment Groth16 et des engagements polynomiaux.
R1CS separe les entrees publiques du temoin prive et exprime le calcul par produits de combinaisons lineaires.
Le setup et la cle de verification doivent correspondre exactement au circuit et a la courbe utilises.
Un engagement polynomial prouve une ouverture en un point sans publier tout le polynome, mais son modele de confiance depend du schema.
La verification cryptographique ne valide pas la provenance metier des entrees publiques.
Versionner relation, parametres et ordre des entrees evite les substitutions de contexte.
Sources : [`provers/groth16`](https://github.com/lambdaclass/lambdaworks/tree/main/provers/groth16) et [`crypto/commitments`](https://github.com/lambdaclass/lambdaworks/tree/main/crypto/src/commitments).

[Suite : limites](05-checklist-et-limites.md)
