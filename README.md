# risksharing
Dans le fichier principale , Nous avons utilisé le solver CPLEX avec la language de programmation Julia 1.7.3 .Les fonctions ErdosRenyiGraph et RandomGraph permettent respectivement de generer 2 types d'instances .
Il existe deux fonctions qui permettent de donner la nouvelle repartition de risques apres partage :
  . Risksharing1 : pour les contrats reciproques identiques.
  . Risksharing2 : pour les contrats reciproques personalisées.
            Note: Il est à signaler que lors de la recherche de la solution optimale,Nous avons remarqué que le solver affiche la solution optimale γ qui contient plus de zeros,alorsqu'il existe d'autres solutions optimales.
