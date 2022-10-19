La derivada de una funcion en un punto representa la pendiente de la tangente a esa funcion en dicho punto

Para calcularla calculamos la pendiente de la recta que contiene 2 puntos cuya distancia tiende a 0
$$
f'(x_0) = \lim_{h\to0}\frac{f(x_0+h) - f(x_0)}{h} =f'(x_0) = \lim_{x\to x_0}\frac{f(x)-f(x_0)}{x-x_0}
$$
> [!info] ## Ecuación de la recta tangente
> En un punto $P$ la tangente a $f$ es dada por:
> $$ P:(a,f(a))\qquad t=f'(a)x\ +\ f(a)-f'(a)a$$
> 
^Recta-tangente
> [!g] ## Derivadas laterales
> - Usando los limites anteriores pero se estudian por el lado correspondiente
> - Para que una funcion sea derivable en un punto sus derivadas laterales deben coincidir
^Derivadas-laterales
> [!r] # Propiedades de la derivacion
> - $f\ no\ continua\ en\ x_0\Rightarrow f \ no\ derivable\ en\ x_0$
> - Derivada del producto por un escalar$$(\lambda f)'=\lambda f'$$
> - Derivada de la suma$$(f\pm g)'=f'\pm g'$$
> - Derivada del producto$$(fg)'=f'g+fg'$$
> - Derivada de la división ($\frac{f}{g}=fg^{-1}$)$$\left(\frac{f}{g}\right)'=\frac{f'g-fg'}{g^2}$$
> - Derivada de la composición (Regla de la cadena) $$(g\circ f)'=g\,'(f)f'$$
^Propiedades-de-la-derivacion
> [!important] # Derivadas de funciones elementales 
> Cuando la funciones estan compuestas con otras se aplica la regla de la cadena
> ### Polinomios
> $$\frac{d}{dx}\left(x^n \right)=nx^{n-1}$$
> ### Logaritmos
> $$\frac{d}{dx}\left( \log_kx\right)=\frac{1}{x}\log_ke$$
> ### Exponencial
> $$\frac{d}{dx}\left(k^x\right)=k^x\log k$$
> ### Seno
> $$\frac{d}{dx}\left(\sin x\right)=\cos x$$
> ### Coseno
> $$\frac{d}{dx}\left(\cos x\right)=-\sin x$$
> ### Tangente
> $$\frac{d}{dx}\left(\tan x\right)=\frac{d}{dx}\left(\frac{\sin x}{\cos x}\right)=\frac{1}{\cos^2x}$$
> ### Arco seno
> $$\frac{d}{dx}\left(\arcsin x\right)=\frac{1}{\sqrt{1-x^2}}$$
> ### Arco coseno
> $$\frac{d}{dx}\left(\arcsin x\right)=\frac{-1}{\sqrt{1-x^2}}$$
> ### Arco tangente
> $$\frac{d}{dx}\left(\arcsin x\right)=\frac{1}{1+x^2}$$
> 
> 
^Derivadas-elementales
> [!b] ## Derivada de la función inversa
> Sea $f:(a,b)\to\mathbb{R}$, $x_0\in(a,b)$, si $f$ es derivable en $x_0$, $f'(x_0)\neq0$ y $f^{-1}$ existe, entonces $f^{-1}$ es derivable $$(f^{-1})'(f(x_0))=\frac{1}{f'(x_0)}$$$$(f^{-1})'(y_0)=\frac{1}{f'(f^{-1}(y_0))}$$    
^Derivada-de-la-inversa
> [!y] # Derivación implicita
> Una ecuación implicita es de la forma $F(x,y)=0$, donde la $x$ y la $y$ estan mezcladas y no se pueden despejar para llegar a una ecuación explícita $y=f(x)$ 
> 
> Para derivar una ecuación implicita se deriva de forma normal, añadiendo $y\ '$    
> en los terminos en los que haya que derivar y $$(xy)'=y+xy\ '$$
^Derivacion-implicita
> [!b] # Derivación logaritmica
> Sean $y$, $g$, y $f$ funciones de $x$ 
> $$y\, '=\left(g\,'\log f+g\frac{f'}f\right)y$$
^Derivacion-logaritmica

> [!r] Operaciones con limites infinitos
> Al operar con limites puede ocurrir que aparezcan infinitos, para operar con ellos se utilizan las siguientes propiedades
> - Suma
> 	- $\lambda + \infty = +\infty$
> 	- $\lambda - \infty = -\infty$
> 	- $+\infty + \infty = +\infty$
> 	- $-\infty - \infty = -\infty$
> - Multiplicación
> 	- $\lambda * \pm \infty = \pm\infty, \forall\lambda>0$
> 	- $\lambda * \pm \infty = \mp\infty, \forall\lambda<0$
> 	- $(\infty)(\infty) = (- \infty)(-\infty)=\infty$
> 	- $(\infty)(-\infty)=-\infty$
> - División
> 	- $\dfrac{\lambda}{\pm\infty}=0, \lambda\neq0$
> 	- $\dfrac{\lambda\ \text{ o }\  \infty}{0^\pm}=\pm\infty$ (Aplicando la regla de los signos)
> 	- $\dfrac{0}{\pm\infty}=0$
> - Potencias
> 	- $0^{\infty}=0$
> 	- $0^{-\infty}=\infty$
> 	- $\infty^\infty=\infty$
> 	- $\infty^{-\infty}=0$
> 	- $-\infty^\infty=\not\exists$
> 

> [!b] Indeterminaciones
> Tambien puede ocurrir que el resultado sea indeterminado
> - $\dfrac00$
> - $\dfrac\infty\infty$
> - $0(\infty)$
> - $\infty-\infty$
> - $1^{\pm\infty}$
> - $0^0$
> - $\pm\infty^0$

> [!important] Regla de l'Hôpital:
> Para resolver algunas de estas indeterminaciones se puede usar la 
> Sea $x_0\in\mathbb{R}$ y $f$ y $g$ funciones derivables en $(x_0-r, x_0)\cup(x_0, x_0+r)$. Si $\lim\limits_{x\to x_0}f(x)=\lim\limits_{x\to x_0}g(x)$ $$\lim\limits_{x\to x_0}\dfrac{f'(x)}{g\,'(x)}=\lim\limits_{x\to x_0}\dfrac{f(x)}{g(x)}$$
> No ocurre lo mismo si es al reves.
> Si vuelve a salir una indeterminación se puede repetir.
> 
> Sirve para resolver las siguientes indeterminaciones: 
> - $0(\infty)$
> - $\infty-\infty$
> - $1^{\pm\infty}$
> - $0^0$
> - $\pm\infty^0$
> 
^Regla-de-lhopital
