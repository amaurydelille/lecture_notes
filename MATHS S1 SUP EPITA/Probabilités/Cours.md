# Probabilité
## Espace probabilisé

**Définition** : 
1) $\Omega$ est l'ensemble des possibles de toutes les expériences, supposé fini.
2) Un évènement est un sous-ensemble A $\subset \Omega$.
3) Un évènement élémentaire est un singleton {$\omega$}$\subset \Omega$
4) L'ensemble des parties de $\Omega$ est $P(\Omega)$ = {les sous-ensembles de $\Omega$} 

##### Évènements disjoints

- Des évènementes $A_1, ..., A_n$ sont deux à deux **disjoints** si $i\ne j \Rightarrow A_i \cap A_j \ne \varnothing$.

Leur union : $A_1 \cup ... \cup A_n = A_1 \sqcup... \sqcup A_n$

Ces évènements forment alors une **partition** de $\Omega$ si  $$\bigsqcup\limits_{i=1}^{n} A_i = A_1 \sqcup...\sqcup A_n = \Omega $$
#### Fonction de probabilité
Une probabilité sur un ensemble $\Omega$ est une application
$$P :  \left \{
   \begin{array}{r c l}
      P(\Omega) & \rightarrow & [0;1] \\
      A   & \mapsto & P(A) \\
   \end{array}
   \right .$$
   vérifiant :
   1) $P(\Omega)$ = 1
   2) $\forall(A,B) \in [P(\Omega)]^2, A\cap B = \varnothing, P(A\sqcup B)=P(A)+P(B)$

Le triplet ($\Omega, P(\Omega), P$) est un espace probabilisé.

**Propriétés :** 
1) $P(\varnothing) = 0$
2) $\forall(A,B) \in [P(\Omega)]^2, P(A) = P(A|B) + P(A\cap B)$
3)  $\forall(A,B) \in [P(\Omega)]^2, P(A \cup B) + P(A\cap B) = P(A) + P(B)$

#### Cas équiprobable
Cas équiprobable : $\Omega$ = {$\omega_1,...\omega_n$}, $P(\omega_i)=C$
- Condition : $$\sum_{i=1}^n P(\omega_i)=1 \Rightarrow n\times C =1 \Rightarrow C = \frac{1}{n} = \frac{1}{Card(\Omega)}$$
- $\forall A\in P(\Omega), A =${$w_k1,...w_kp$} $$\boxed{P(A) =\sum_{i=1}^n P(\omega_i)=p\times C= \frac{Card(A)}{Card(\Omega)} }$$
**exemple** : lancer de dé. $P(résultat <= 2)=P(1,2)=\frac{2}{6}=\frac{1}{3}$ 

#### Formule de Bayes
$$\boxed{P(A|B) = \frac{P(B|A)P(A)}{P(B)}}$$



### Variables aléatoires

**Définition :** On définit une **variable aléatoire** en associant un nombre réel à chaque éventualité d'une expérience aléatoire.

Une variable aléatoire $X$ est une application $$X:\Omega \rightarrow \mathbb{R}$$

**Conséquences :** $\forall B \subset X(\Omega), P_X(B) = P(X\in B) = P(A)$



La distribution de la variablea aléatoire $X$ est donnée par **UNE LOI DE $X$** 

- l'ensemble des valeurs prises par $X$ : $X(\Omega)=\{x_1, x_2, ..., x_n \}$
- les valeurs $P(X)=x_1, P(X)=x_2,..., P(X)=x_i$

#### Loi binomiale 
$$\boxed{\forall k \in [\![0;n]\!], P(X=k)= \begin{pmatrix}n\\k\end{pmatrix}p^k(1-p)^{n-k}}$$

#### Éspérance
L'éspérance est la **moyenne arithmétique** de $X$.

$$\boxed{E(X) = \sum_{i=1}^{n} x_i \times P(X=x_i)}$$
#### Variance 
La variance permet **d'estimer la dispersion des valeurs de $X$ autour de $E(X)$**.
$$V(X) = E((x_i - E(X)))^2$$
$$      = \sum_{i=1}^{n} (x_i - E(X))^2 \times P(X=x_i)$$
$$\boxed{= E(X^2) - (E(X))^2}$$
avec : $$\boxed{E(X^2) = \sum_{i=1}^{n} {x_i}^2 \times P(X=x_i)}$$

Soit $(\alpha, \beta)\in \mathbb{R}^2, X$ et $Y$ deux variables aléatoires,
$$E(\alpha X + \beta) = \alpha E(X) + \beta$$
$$V(\alpha X + \beta) = \alpha^2V(X)$$
*exemple :* voir exercice 4.12 polycopié