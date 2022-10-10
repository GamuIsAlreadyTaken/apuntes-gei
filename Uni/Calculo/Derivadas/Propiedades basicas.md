

La derivada de una funcion en un punto representa la pendiente de la tangente a esa funcion en dicho punto

Para calcularla calculamos la pendiente de la recta que contiene 2 puntos cuya distancia tiende a 0
$$
\begin{align*}
&f'(x_0) = \lim_{h\to0}\frac{f(x_0+h) - f(x_0)}{h}\\
&\qquad\qquad\qquad o\\
&f'(x_0) = \lim_{x\to x_0}\frac{f(x)-f(x_0)}{x-x_0}
\end{align*}
$$
## Ecuación de la recta tangente
En un punto $P$ la tangente a $f$ es dada por:
$$ P:(a,f(a))\qquad t=f'(a)x\ +\ f(a)-f'(a)a$$

## Derivadas laterales
- Usando los limites anteriores pero se estudian por el lado correspondiente
- Para que una funcion sea derivable en un punto sus derivadas lateraales deben coincidir

## Propiedades de la derivacion
- Si la funcion es derivable en un punto entonces la funcion es continua en ese punto
- La derivada de un escalar por una funcion es la derivada de la funcion, por el escalar$$f'(kx)=kf'(x)$$
#### Multiplicacion
$$f(x) = A*B,\qquad f'(x)=A'B+AB'$$
#### Division
$$f'\left(\frac{x}{y}\right)=\frac{A'B-AB'}{y^2}$$

- [ ] Regla de la cadena?
# Derivadas de funciones elementales 
- [ ] Aprenderlo!

## Derivada de la función inversa
- [ ] Latex

# Derivación implicita
- Funciones de forma f(x, y) donde ninguna variable se puede despejar
- [ ] Hacer derivacion a mano :)
- [ ] Latex
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