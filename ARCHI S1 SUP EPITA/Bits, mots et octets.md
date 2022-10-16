## Définition

**Bit :** contraction de *binary digit*, c'est la plus petite unité d'information qu'un ordinateur peut manipuler. Il peut uniquement valoir 0 ou 1.

**Mot :** c'est un regroupement de un ou plusieurs bits qui peuvent être manipulés comme un tout.
La taille d'un mot (son nombre de bits) est fixe.

*exemple :* 
- un mot de un bits possède **deux** combinaisons possibles : 0 et 1.
- 2 bits : 00, 01, 10, 11
- 3 bits : 000, 001, ..., 111
- $n$ bits : $2^n$ combinaisons possibles.
---
- Hors contexte, la taille d'un mot est indéfinie et doit être précisée.
- De nos jours les microrpocessuers sont conçus pour manipuler des octets (8 bits) ou des groupes d'octets.
- le bit le plus à gauche d'un mot est le **le bit de poids fort** (**MSB : Most Significant Bit**) et le bit le plus à droite est le **bit de poids faible (LSB : Less Significant Bit)**. Les bits d'un mot à $n$ bits sont numérotés de $0$ à $n-1$, où le $0$ est le LSB et le $n-1$ est le MSB. 
---
## Complément à un
Le complément à un d'un mot s'obtient en inversant chacun de ses bits :$$00110110\rightarrow 11001001$$

## Complément à deux
Le complément à deux d'un mot s'obtient en inversant chacun de ses bits en lui additionnant un. Autrement dit il s'agit du complément à un plus un. 

*exemple :* $$1110011000_2 \rightarrow 0001100111_2 +1_2 =0001101000_2$$
Le complément à deux s'obtient également en conservant la valeur des bits de poids faibles (**du LSB jusqu-au premier un**) et en inversant les autres bits.
*exemple :*$$1110011000 \rightarrow 0001101000$$
$$00110110 \rightarrow 11001010$$
$$111111 \rightarrow 000001$$
