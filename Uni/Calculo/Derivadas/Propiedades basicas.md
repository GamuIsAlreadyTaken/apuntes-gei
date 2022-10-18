La derivada de una funcion en un punto representa la pendiente de la tangente a esa funcion en dicho punto

Para calcularla calculamos la pendiente de la recta que contiene 2 puntos cuya distancia tiende a 0
$$
f'(x_0) = \lim_{h\to0}\frac{f(x_0+h) - f(x_0)}{h} =f'(x_0) = \lim_{x\to x_0}\frac{f(x)-f(x_0)}{x-x_0}
$$
> [!info] ## Ecuación de la recta tangente
> En un punto $P$ la tangente a $f$ es dada por:
> $$ P:(a,f(a))\qquad t=f'(a)x\ +\ f(a)-f'(a)a$$
> 
## Derivadas laterales
- Usando los limites anteriores pero se estudian por el lado correspondiente
- Para que una funcion sea derivable en un punto sus derivadas laterales deben coincidir

> [!r] # Propiedades de la derivacion
> - $f\ no\ continua\ en\ x_0\Rightarrow f \ no\ derivable\ en\ x_0$
> - Derivada del producto por un escalar$$(\lambda f)'(x)=\lambda f'(x)$$
> - Derivada de la suma$$(f\pm g)'(x_0)=f'(x)\pm g'(x)$$
> - Derivada del producto$$(fg)'(x)=f'(x)g(x)+f(x)g'(x)$$
> - Derivada de la división ($\frac{f}{g}=fg^{-1}$)$$\left(\frac{f}{g}\right)'(x)=\frac{f'(x)g(x)-f(x)g'(x)}{g^2(x)}$$
> - Derivada de la composición (Regla de la cadena)

> [!important] # Derivadas de funciones elementales 
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

> [!b] ## Derivada de la función inversa
> Sea $f:(a,b)\to\mathbb{R}$, $x_0\in(a,b)$, si $f$ es derivable en $x_0$, $f'(x_0)\neq0$ y $f^{-1}$ existe, entonces $f^{-1}$ es derivable $$(f^{-1})'(f(x_0))=\frac{1}{f'(x_0)}$$$$(f^{-1})'(y_0)=\frac{1}{f'(f^{-1}(y_0))}$$    

# Derivación implicita
Una ecuación implicita es de la forma $F(x,y)=0$, donde la $x$ y la $y$ estan mezcladas y no se pueden despejar para llegar a una ecuación explícita $y=f(x)$ 

Para derivar una ecuación implicita se deriva de forma normal, añadiendo $y\ '$    
en los terminos en los que haya de derivar y $$(xy)'=y+xy\ '$$
# Derivación logaritmica
- [ ] Hacer la derivacion, empezar con $y(x)=f(x)^{g(x)}$ y tomar logs a ambos lados


## Regla de l'Hôpital
- 2 funciones derivables en el rango - [ ] completar
- Si ambos limites en X$_0$ entonces
- Se puede aplicar varias veces - [ ] mirar lhopital en sus apuntes


### Suma
- k + oo -> oo
- ...
- [ ] Seguir con esto
### Multiplicación
- k * oo -> oo
- k * -oo -> -oo
### División
- [ ] Rellenar identidades

el limite es 0$^+$ si se queda por encima del 0, 0$^-$ si se queda por debajo ...

### Indeterminaciones
- 0/0
- oo/oo
- o+-oo


- [ ] Mirar el codigo de numpy de polinomio de interpolacion de lagrange


