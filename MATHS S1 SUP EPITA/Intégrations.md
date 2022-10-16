## Intégration par parties

**Hypothèses :** soit $u$ et $v$ deux fonctions de classes $C_1$ (dérivables et continues sur $\mathbb{R}$) sur $I \subset \mathbb{R}$ et 
$(a,b) \in I^2,$ alors :

*Formule :* $$\boxed{\int_{a}^{b}u'(x)v(x)dx = [u(x)v(x)]_{a}^{b} - \int_{a}^{b}u(x)v'(x)dx}$$ **Démonstration :** *à connaitre par coeur*
$$[u(x)v(x)]_{a}^{b} = \int_{a}^{b}(uv)'(x)dx$$
$$= \int_{a}^{b}(u'v + uv')(x)dx = \int_{a}^{b}u'(x)v(x)dx + \int_{a}^{b}u(x)v'(x)dx$$
$$\Leftrightarrow \int_{a}^{b}u'(x)v(x)dx =[u(x)v(x)]_{a}^{b} - \int_{a}^{b}u(x)v'(x)dx    $$


## Intégration par changement de variables

Soient $I$ et $T$ deux intervalles de $\mathbb{R}$. $(\alpha,\beta)\in J^2, f$ une fonction continue sur $I$. $\varphi$ une fonction de classe $C_1$ de $J$ vers $I$.

$\underline{alors} :$ $$\boxed{\int_{\varphi(\alpha)}^{\varphi(\beta)}f(t)dt = \int_{\alpha}^{\beta}f(\varphi(t))\varphi '(t)dt}$$
$\underline{démonstration} :$ $$\int_{\varphi(\alpha)}^{\varphi(\beta)}f(t)dt = [F(t)]_{\varphi(\beta)}^{\varphi(\alpha)}, F'(t)=f(t)$$
$$=F(\varphi(\beta)) - F(\varphi(\alpha)) = F\circ\varphi(\beta)-F\circ\varphi(\alpha)$$
$$=[F\circ \varphi (t)]_{\alpha}^{\beta} = \int_{\alpha}^{\beta}F\circ \varphi '(t)dt$$
$$\int_{\alpha}^{\beta}F'\circ \varphi(t)\times\varphi '(t)dt =\int_{\alpha}^{\beta}f\circ \varphi(t)\times\varphi '(t)dt$$
$$=\int_{\alpha}^{\beta}f( \varphi (t))\times \varphi '(t)dt$$