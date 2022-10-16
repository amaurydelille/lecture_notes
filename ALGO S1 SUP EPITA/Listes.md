### Définition
$\lambda$ : liste               -> l
e : élément        -> e
liste-vide           -> [ ]
$\lambda 2$ = cons(e, $\lambda$)  -> let l2 = e: :l
e = premier($\lambda$)  -> let e: :l2 = l in e

*exemple :* 
0 < k < longueur($\lambda$)
$\Rightarrow$ accès(cons(e, $\lambda$), k+1) = accès($\lambda$, k)  $\rightarrow$ accéder au $k_ième$ 

existe(e, liste-vide) = faux
existe(e, cons(e, $\lambda$)) = vrai

*exemple* : e $\ne$ e' $\Rightarrow$ existe(e', cons(e, $\lambda$)) = existe(e', $\lambda$)
