# Asintotas verticales
- Se buscan en puntos que no pertenecen al dominio
- El limite cuando x tiende a x$_0$ sea igual a $\pm\infty$   

# Asintotas horizantales
- Cuando el limite cuando x tiende a masmenos inf = k
- Es interesante saber si la funcion esta por encima o por debajo de la asintota
# Asintota oblicua
Las asintotas oblicuas tienen la forma:
$$ \begin{align*}
&mx-n \\
&m = \lim_{x\to\pm\infty}\frac{f(x)}{x}\\
&n = \lim_{x\to\pm\infty}f(x)-mx
\end{align*}
\text{Si m y n existen y son finitos} \\

$$
En caso contrario, la función no tiene asintotas


> [!b] # Continuidad
> Sea $f:A\subset\mathbb{R}\to\mathbb{R},\ x_0\in A$, Diremos que una función es continua en un punto $x_0$ si, existe $\lim\limits_{x\to x_0}f(x)$ y es igual a $f(x_0)$ 
 >$$\forall\epsilon>0,\exists\delta>0\Big/|x-x_0|<\delta\Rightarrow|f(x)-f(x_0)|<\epsilon$$  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d1/L%C3%ADmite_01.svg/250px-L%C3%ADmite_01.svg.png" class="center">
> Por lo tanto, una funcion es continua en un punto si y solo si:
> ## $$\lim_{x\to x_0} f(x) = f(x)$$
^Continuidad


> [!example] ## Tipos de discontinuidades
> #### Discontinuidades esenciales $$\not\exists f(x_0)\qquad o\qquad \not\exists\lim\limits_{x\to x_0}f(x)$$
> #### Discontinuidad evitable$$\lim\limits_{x\to x_0} f(x) \neq f(x_0)$$
> <img src="https://luishervella.github.io/JB_Calculo1_UDC/_images/cap3_discontinuidades.png" class="center">
^Tipos-de-discontinuidades

> [!o] # Algebra de funciones continuas
> Sean $f,g:A\subset\mathbb{R}\to\mathbb{R}$ funciones continuas en un punto $x_0\in A$. Entonces
> - $\lambda f$ es continua en $x_0,\ \forall\lambda\in\mathbb{R}$
> - $f\pm g$ es continua en $x_0$
> - $f\ g$ es continua en $x_0$
> - si $g(x_0)\neq 0, \frac{f}{g}$ es continua en $x_0$
> - $f\circ g$ es continua en $x_0$
> - El limite conmuta con las funciones continuas: $$\lim\limits_{x\to x_0}g\left(f(x)\right)=g\left(\lim\limits_{x\to x_0}f(x)\right)$$
^Algebra-de-funciones-continuas

# Estudio de la continuidad en intervalos
> [!red] # Teorema de bolzano
> Sea $f:[a,b]\to\mathbb{R}$ una función [continua] en $[a,b]$ tal que $f(a)f(b)<0$(uno de los 2 esta por encima de $y=0$ y el otro por debajo). Entonces existe $x_0\in(a,b)$ tal que $f(x_0)=0$, es decir, tiene al menos 1 raiz en ese intervalo:
> <img src="https://luishervella.github.io/JB_Calculo1_UDC/_images/cap3_bolzano_1_2.png" class="center">
> Si alguna de las hipótesis no se cumple, el teorema no es valido:
> <img src="https://luishervella.github.io/JB_Calculo1_UDC/_images/cap3_bolzano_3.png" class="center"> 
^Teorema-de-bolzano


> [!g] # Teorema de weierstrass
> Sea $f:[a,b]\to\mathbb{R}$ una función [continua] en $[a,b]$. Entonces $f$ alcanza máximo y mínimo absoluto en $[a,b]$. Es decir, $$\exists x_1, x_2\in[a,b]\Big/f(x_1)\leq f(x)\leq f(x_2)\quad \forall x\in[a,b]$$
> <img src="https://luishervella.github.io/JB_Calculo1_UDC/_images/cap3_Weierstrass.png" class="center">
^Teorema-de-weierstrass