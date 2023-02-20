## Comment gagner à tous les coups aux paris sportifs ?

### Introduction

Les paris sportifs existent depuis plus de deux millénaires. Dans ce type de jeu, on cherche à prédire un évènement sur une rencontre sportive (généralement -> la victoire d'une équipe)

En effet, pendant Grèce Antique -> on jouait à l'artiasmos, ou "jeu du pair-impair". Une joueur A prend un certain nombre d'osselets dans sa main. Le joueur B doit deviner s'il a un nombre pair ou impair d'osselets. 
-> gagne, il récupère les osselets dans la main
perd -> le joueur B donne à A le nombre correspondant d'osselets dans la main

Maintenant -> paris sportifs ont évolué et couvre des centaines de sports. 
En france en 2021 -> CA de 617m € -> lié au fait que seul environ 3% des parieurs sont gagnants à long-terme

**Comment gagner à tous les coups aux paris sportifs ? Nous verrons comment nous appuyer sur les mathématiques et notamment les probas pour maximiser les gains sur ce type de jeu**

### Développement

#### 1) Définition d'une cote

Prenons deux équipes A et B.

Le bookmaker, cad celui qui prend les paris, donne une cote à 1.5 pour l'équipe A et une cote à 3.5 pour l'équipe B.

Or, qu'est-ce qu'une cote ? -> Retranscription de la probabilité qu'un évènement se produise. Elle permet de savoir quel sera le gain en cas de réalisation de l'évènement. 

Pour retrouver la probabilité, on prend l'inverse de la cote.

Ex -> On note A l'évènement "L'équipe A gagne"

La probabilité que l'équipe A gagne avec une cote de 1.5.

$$P(A) = \frac{1}{cote_{équipe \,A}}=\frac{1}{1.5} = 0.66$$
Donc la probabilité que l'équipe A gagne est de 66%.

Pour savoir quel sera le gain si l'évènement se produit, il suffit de multiplier la mise par la cote. Ex ->  pour l'équipe A avec une mise de 100€ : 

$$Gain_{équipe \,A} = 100*1.5 = 150€$$
Soit une plus-value de 50€

#### 2) L'arbitrage

Comment tirer avantage de tout cela ?

Il arrive que le bookmaker fasse des erreurs sur ses cotes et qu'il se trompe sur les probabilités que les deux équipes gagnent, c'est-à-dire que la somme des probabilités soit inférieure à 1 -> appelé "arbitrage de pari". 

Or, par définition, la somme des probabilités de tous les évènements d'une expérience aléatoire est égale à 1. 

Donc cette erreur permet de parier sur les deux issues de l'expérience alétoire et s'assurer un gain quelque soit l'issue.

Reprenons l'exemple précédent. 
A l'évènement "L'équipe A gagne" et non-A "L'équipe A perd", soit l'équipe B gagne. 
A et non-A -> une partition de l'univers.

$$S = \frac{1}{cote_{équipe \,A}} + \frac{1}{cote_{équipe \,B}} = \frac{1}{1.5}+\frac{1}{3.5} = 0.952<1$$

-> situation d'arbitrage de pari.

#### 3) Calcul des mises et plus-value

Maintenant que nous savons que nous avons une situation favorable -> répartir les mises sur les deux équipes et s'assurer un gain.

La formule est la suivante : 

$$Mise = \frac{Mise \,totale}{Somme\,des\,probabilités*cote}$$
Par exemple, si l'on veut miser 100€.

-> équipe A 

$${Mise_{équipe \,A}= \frac{100}{0.952*1.5} = 70€}$$
-> équipe B

$$Mise_{équipe \,B} = \frac{100}{0.952*3.5} = 30€ $$
On peut maintenant calculer les plus-values, c'est-à-dire le gain en retirant la mise initiale.

$$Plus-value = (mise*cote)-mise \; totale$$
Donc si l'équipe A gagne : 

$$P_{vA} = (70*1.5)-100 = 5€$$
Si l'équipe B gagne : 

$$P_{vB} = (30*3.5)-100 = 5€$$
On assure donc un profit de 5€ quelque soit l'équipe gagnante grâce à l'arbitrage de pari.

### Conclusion 

On a donc vu que la connaissance des probabilités permet d'avoir un gain assuré à chaque pari que l'on souhaite prendre.

Néanmoins, cette méthode présente quelques limites 
-> il faut avoir un capital de départ important pour dégager des bénéfices significatifs
-> les erreurs de probabilités des bookmakers demeurent rares
-> dans un volonté de maximiser leurs bénéfices, ces derniers n'hésitent pas à limiter voire bloquer les comptes des joueurs gagnants

