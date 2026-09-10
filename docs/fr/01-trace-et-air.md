# 01 — Du calcul a la trace STARK

Le prouveur STARK encode une execution comme une trace : chaque ligne decrit un etat et les colonnes portent les registres utiles.
L AIR definit les relations algebriques qui doivent relier les lignes et les conditions aux bords.
Une trace bien formee n est pas suffisante si une regle metier importante manque dans l AIR.
La revue doit donc suivre chaque colonne depuis sa semantique jusqu aux contraintes de transition et de frontiere.
Les entrees publiques lient la preuve a l instance revendiquee sans reveler necessairement toute la trace.
Lambdaworks separe ces responsabilites dans le prover STARK et les exemples AIR.
Source : [`provers/stark`](https://github.com/lambdaclass/lambdaworks/tree/main/provers/stark).

[Suite : compositions](02-composition-et-domaines.md)
