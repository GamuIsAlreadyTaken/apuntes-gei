Dada una nube de puntos, nos permite construir un polinomio que pase por cada punto de dicha nube

> [!info] No hay una sola solución al problema

# Polinomio de Interpolación de Lagrange
Dados $n+1$ puntos distintos, existe un unico polinomio de grado menor o igual a n que pase por todos los puntos

Existen 2 formas de contruir tal polinomio:

## Contrucción por polinomios fundamentales
Para todo i existe un unico polinomio $l_i$ de grado menor o igual n tal que
$$
\begin{align*}
&l_i(x_i) = 1 \\
&l_i(x_j)=0, \forall j \neq i
\end{align*}$$
Para una nube de 4 puntos, cada polinomio fundamental quedaría asi

$$l_0(x) = \frac{(x-x_1)(x-x_2)(x-x_3)}{(x_0-x_1)(x_0-x_2)(x_0-x_3)}$$
$$l_1(x) = \frac{(x-x_1)(x-x_2)(x-x_3)}{(x_1-x_0)(x_1-x_2)(x_1-x_3)}$$
$$l_2(x) = \frac{(x-x_1)(x-x_2)(x-x_3)}{(x_2-x_0)(x_2-x_1)(x_2-x_3)}$$
$$l_3(x) = \frac{(x-x_1)(x-x_2)(x-x_3)}{(x_3-x_0)(x_3-x_2)(x_3-x_0)}$$
Para obtener el polinomio final simplemente multiplicamos multiplicamos cada polinomio con su punto respectivo y lo sumamos todo
$$p(x) = y_0l_0(x)+y_1l_1(x)+y_2l_2(x)+y_3l_3(x)$$

## Construcción mediante diferencias divididas
- Se representa como una tabla
- Formula de Newton
