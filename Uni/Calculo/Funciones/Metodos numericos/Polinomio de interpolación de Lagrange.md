Dada una nube de puntos, construir un polinomio que pase por cada punto de dicha nube
- No hay una sola solución al problema

# Polinomio de Interpolación de Lagrange
- n+1 puntos distintos
- n+1 valores cualesquiera, existe un unico polinomio de grado <= n que pase por todos los puntos

## Contrucción por polinomios fundamentales
- Para todo i existe un unico polinomio l$_i$ de grado <= n tal que
	- $l_i(x_i) = 1$
	- $l_i(x_j)=0, \forall j \neq i$


$$l_0(x) = \frac{(x-x_1)(x-x_2)(x-x_3)}{(x_0-x_1)(x_0-x_2)(x_0-x_3)}$$
$$l_1(x) = \frac{(x-x_1)(x-x_2)(x-x_3)}{(x_1-x_0)(x_1-x_2)(x_1-x_3)}$$
$$l_2(x) = \frac{(x-x_1)(x-x_2)(x-x_3)}{(x_2-x_0)(x_2-x_1)(x_2-x_3)}$$
$$l_3(x) = \frac{(x-x_1)(x-x_2)(x-x_3)}{(x_3-x_0)(x_3-x_2)(x_3-x_0)}$$
$$p(x) = y_0l_0(x)+y_1l_1(x)+y_2l_2(x)+y_3l_3(x)$$

## Construcción mediante diferencias divididas
- Se representa como una tabla
- Formula de Newton
