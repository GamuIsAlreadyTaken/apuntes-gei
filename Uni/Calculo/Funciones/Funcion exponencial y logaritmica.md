
> [!r] # Funcion Exponencial
> 
> Sea $a>0$. La función exponencial de base $a$ es: $$f(x)=a^x$$
> Cuando $a\neq1$ el comportamiento de $f$ varía en función de si $a$ es menor o mayor que 1, en ambos casos se verifica que: 
> - $Dom\ f=\mathbb{R}$
> - $Im\ f =(0, +\infty)$
> - $f(0)=a^0=1$
>
><img src="https://estudianteo.com/wp-content/uploads/2021/07/Grafica-de-la-funcion-exponencial11-300x295.png" height="400" class="center">
>
> ### Si $a<1$
> - $f$ es estrictamente decreciente
> - $\lim\limits_{x\to-\infty}a^x=+\infty$
> - $\lim\limits_{x\to+\infty}a^x=0$
> 
> ### Si $a>1$
> - $f$ es estrictamente creciente
> - $\lim\limits_{x\to-\infty}a^x=0$
> - $\lim\limits_{x\to+\infty}a^x=+\infty$
> 

> [!code] En sympy
> $$sp.exp(x) \to e^x$$

> [!info] La derivada de $e^x$
> $$e^x\frac{\delta}{\delta x}=e^x$$

> [!important] ## Propiedades de la función exponencial
> - Multiplicación de potencias de misma base $$a^xa^y=a^{x+y},\qquad\forall x,y\in\mathbb{R}$$
> - Potencia de una potencia $$(a^x)^y=a^{xy},\qquad\forall x,y\in\mathbb{R}$$
> - Potencias negativas $$a^{-x}=(a^x)^{-1}=\frac{1}{a^x}$$

---
> [!r] # Función logarítmica
> 
> Sea $a>0$, $a\neq1$, el logaritmo en base $a$ de $x$ si $a^y=x$$$y=\log_a(x)\ :\Leftrightarrow\ a^y=x$$
> La funcion $\log_a$ es la inversa de la $\exp_a$
> 
> Para $a>0$ y $a\neq1$
> - $Dom (log_a)=(0,+\infty)$
> - $Im(log_a)=\mathbb{R}$
> - $log_a(1)=0$
> 
> <img src="https://calculo.cc/temas/temas_bachillerato/primero_ciencias_sociales/funciones_elementales/imagenes/teoria/f_logaritmicas/logaritmicas.gif" class="center" height="400">
> 
> ### Si $a\in(0,1)$
> - Estrictamente decreciente
> - $\lim\limits_{x\to0^+}\log_a(x)=+\infty$
> - $\lim\limits_{x\to+\infty}\log_a(x)=-\infty$
> ### Si $a>1$
> - Estrictamente creciente
> - $\lim\limits_{x\to0^+}\log_a(x)=-\infty$
> - $\lim\limits_{x\to+\infty}\log_a(x)=+\infty$
> 

> [!code] En sympy
> $$sp.log(x)\to\log(x)$$
> $$sp.log(x,y)\to\log_y(x)$$

> [!info] Logaritmo neperiano
> Es el logaritmo en base $e$ $$\log(x)=\ln(x)=\log_e(x)$$

> [!important] ## Propiedades de la función logaritmo
> - Logaritmo del producto $$\log_a(xy)=\log_a(x)+\log_a(y),\qquad\forall x,y>0$$
> - Logaritmo de una potencia $$\log_a(x^y)=y\log_a(x),\qquad\forall x>0,\quad\forall y\in\mathbb{R}$$
> - Logaritmo de la fracción $$\log_a\left(\frac{x}{y}\right)=\log_a(x)-\log_a(y),\qquad\forall x,y>0$$
> 
