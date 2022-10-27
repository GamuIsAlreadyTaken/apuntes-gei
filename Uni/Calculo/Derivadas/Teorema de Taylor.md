Nos sirve para aproximar funciones usando polinomios.
Cuanto mas alto sea el orden del polinomio mejor ser la aproximación a la función
Dada una función $f$, un punto $x_0$ y un grado $n \in\mathbb{N}$ la formula del polinomio es
$$P_{f,n=3,x_0=1}(x)=f(x_0)+\dfrac{f'(x_0)}{1!}(x-x_0)+\dfrac{f''(x_0)}{2!}(x-x_0)^2+...+\dfrac{f^n(x_0)}{n!}(x-x_0)^n$$


No hay ninguna forma de calcular el error mas alla de calcularlo a mano, lo que si se puede hacer es acotar este error, para ello, usamos una constante $\xi \in(x,x_0)$ y queda de la siguiente forma: $$E=\dfrac{f^{(n+1)}(\xi)}{(n+1)!}\left(x-x_0\right)^{n+1}$$ Para calcular el error tiene que ser posible la derivada $n+1$ 

Aproximar una función con un polinomio

Maclauring == x_0 = 0

- [ ] Practicar en casa #Ejercicio 
- [ ] Hacerlo en python, por teams hay codigo (sp.series(-,-,-,-), f.diff(var, gradoDerivada))

p(x) = 5 + (x+1)^2 + 3(x+1)^3 es el polinomio de taylor de tercer orden centrado en x_0=-1 de una función f, calcula 
f(-1) = 5, 
f'(-1) = 0,
f''(-1) = 2,
f'''(-1) = 18 ñjpojqwe