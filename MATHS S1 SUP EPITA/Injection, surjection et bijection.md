# MATHÉMATIQUES S-1 SUP EPITA

## Injection, surjection , bijection

### Injection
Soient deux ensembles $E$ et $F$ et une application de $f:E \rightarrow F$ , on dit que $f$ est **injective** lorsque tout élément $y$ de $F$ admet au plus un antécédent par $f$ :

$$\boxed{\forall(x, y)\in E^2, [f(x)]=f(y)]\Rightarrow (x=y)}$$
*exemple* : la fonction ci-dessous est **injective** car sur l'ensemble de départ et d'arrivée designé aucune image de $F$ renvoie le même antécédant dans $E$.
$$f :  \left \{
   \begin{array}{r c l}
      \mathbb{R}^{+}  & \rightarrow & \mathbb{R}^+ \\
      x   & \mapsto & x^2 - 1 \\
   \end{array}
   \right .$$
### Surjection
Soient deux ensembles $E$ et $F$ et une application $f : E \rightarrow F$ , on dit que f est surjective lorsque tout élément $y$ de $F$ possède au moins un antécédant dans par $f$ :
$$\boxed {\exists y\in F, \forall x\in E, f(x) = y} $$
*exemple* : celle-ci n'est **pas surjective** car sur $\mathbb{R}^-$ dans $F$, $y$ de $F$ ne possède aucun antécédant par $f$.
$$f :  \left \{
   \begin{array}{r c l}
      \mathbb{R}^{+}  & \rightarrow & \mathbb{R}\\
      x   & \mapsto & x^2 - 1 \\
   \end{array}
   \right .$$
### Bijection 
Lorsque $f$ est à la fois surjective et injective :
$$\boxed{\forall y\in F, \exists! x \in E, f(x)=y}$$

*exemple* :  
$$f :  \left \{
   \begin{array}{r c l}
      \mathbb{R}^{+}  & \rightarrow & \mathbb{R}^+\\
      x   & \mapsto & x^2 - 1 \\
   \end{array}
   \right .$$
### Image réciproque
Soit $f$ une application de $E$ dans $F$. On appelle **image reciproque** d'un sous-ensemble $G$ de $f$ et on note $f^{-1}(G)$, l'ensemble des antécédant de $y$ par $f$ :
$$f^{-1}(G) = \{ x \in E,f(x) \in G \} .$$
**NOTES** :