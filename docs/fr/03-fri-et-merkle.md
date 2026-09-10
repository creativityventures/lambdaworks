# 03 — FRI, Merkle et transcript

FRI demontre la proximite a un polynome de faible degre par plis successifs et ouvertures echantillonnees.
Les evaluations sont engagees dans des arbres de Merkle avant que le transcript ne derive les positions a ouvrir.
L ordre d absorption est un invariant de securite : un defi ne doit jamais preceder l engagement qu il est cense rendre imprevisible.
Chaque ouverture doit verifier feuille, chemin, racine et correspondance avec la couche FRI attendue.
Le nombre de requetes, le facteur d explosion et l extension de champ participent ensemble a la marge de securite.
Une configuration performante n est donc pas automatiquement une configuration sure.
Sources : [`crypto/merkle_tree`](https://github.com/lambdaclass/lambdaworks/tree/main/crypto/src/merkle_tree) et [`provers/stark`](https://github.com/lambdaclass/lambdaworks/tree/main/provers/stark).

[Suite : SNARK](04-snark-et-engagements.md)
