# Logique propositionnelle

## Négation, conjonction et disjonction 

### Négation
Soit $P$ une proposition, on appelle **négation** de $P$ et on note "$\neg P$" ou "non $P$" la proposition qui est vraie si $P$ est fausse, et qui est fausse si $P$ est vraie.

*table de vérité de la **négation*** :

### Conjonction
Soit $P$ et $Q$ deux propositions, on appelle **conjonction** de $P$ et $Q$ et on note $P \land Q$ ou $P$ et $Q$, la proposition qui est vraie si $P$ et $Q$ sont vraies et qui est fausse dans tous les autres cas.

Sa négation est $\neg P \lor \neg Q$.

*table de vérité de la **conjonction*** : 

### Disjonction
Soit $P$ et $Q$ deux propositions, on appelle **disjonction** de $P$ et $Q$ et on note $P \lor Q$ ou $P$ ou $Q$, la proposition qui est vraie lorsqu'au moins $P$ ou $Q$ est vraie.

Sa négation est $\neg P \land \neg Q$.

*tables de vérité de la **disjonction*** : 

### Implication 
Soit $P$ et $Q$ deux propositions, on appelle **implication** de $P$ et $Q$ et on note $P\Rightarrow Q$ la proposition qui est **vraie** lorsque : 
- $P$ et $Q$ sont vraies.
- $P$ est fausse et $Q$ est vraie.
- $P$ et $Q$ sont fausses.

Et **fausse** lorsque $P$ est vraie et $Q$ est fausse.

Sa négation est $P \land \neg Q$.                     
Et sa contraposée est $\neg Q \Rightarrow \neg P$.

### Équivalence
Soit $P$ et $Q$ deux propositions, on appelle **équivalence** de $P$ et $Q$ et on note $P \Leftrightarrow Q$ la proposition qui est vraie lorsque $P$ et $Q$ sont tous deux vrais ou tous deux faux.

$P \Leftrightarrow Q = (P\Rightarrow Q \land Q\Rightarrow P)$  

Ainsi sa négation est : $(P \land \neg Q) \lor (Q\land \neg P)$

