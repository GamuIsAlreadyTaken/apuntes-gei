
### Definición de limite
- Para todo $\epsilon$ > 0, el intervalo L= \[l + $\epsilon$, l - $\epsilon$]
- corresponde al intervalo X= \[x$_0$ + $\delta$, x$_0$ - $\delta$]
- Para cualquier valor del intervalo X - x$_0$ su imagen esta en el intervalo L
- Para todo $\epsilon$ > 0, existe un $\delta$ > 0 | si x $\in$ (x$_0$ - $\delta$, x$_0$ + $\delta$), x $\neq$ x$_0$ entonces f(x) $\in$ (l-$\epsilon$, l+$\epsilon$)

>[!important] # Limite
> El valor de una función en $x_0$ al acercarse infinitamente a $x_0$ 
> #### $$\lim\limits_{x\to x_0} f(x) =l:\Big[\forall\epsilon>0, \exists\delta>0\Big/0<|x-x_0|<\delta\Longrightarrow|f(x)-l|<\epsilon\Big]$$
> <img src="https://luishervella.github.io/JB_Calculo1_UDC/_images/cap3_definicion_limite_3.png" class="center">
>
$x_0$ podría no estar definido en la función, por ello se especifica que$0<|x-x_0|$ 

>[!r] ## Propiedades de los limites
> Sean $f,g:A\subset\mathbb{R}\to\mathbb{R}, x_0\in A$. Suponiendo que $f$ está [[Conjuntos de números#^Conjuntos-acotados|acotada]] cerca de $x_0$ y que $\lim\limits_{x\to x_0} g(x) = 0$ 
> - $\lim\limits_{x\to x_0} (f\ g)(x)=0$
> - $\lim\limits_{x\to x_0}(\lambda f)(x)=\lambda\lim\limits_{x\to x_0}f(x), \qquad \forall\lambda\in\mathbb{R}$
> - $\lim\limits_{x\to x_0}(fg)(x)=\left(\lim\limits_{x\to x_0}f(x)\right)\left(\lim\limits_{x\to x_0}g(x)\right)$
> - $\lim\limits_{x\to x_0}\left(\frac{f}{g}\right)(x)=\frac{\lim\limits_{x\to x_0}f(x)}{\lim\limits_{x\to x_0}g(x)}, si \lim\limits_{x\to x_0}g(x) \neq 0$


