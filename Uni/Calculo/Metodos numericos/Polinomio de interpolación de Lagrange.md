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

Permite añadir nuevos puntos sin necesidad de rehacer todos los calculos

Para ello, podemos empezar con el caso mas basico, 1 solo punto $(x_0,y_0)$
$$P_0(x) = y_0$$
Podemos ver que para $x=x_0$ el polinomio devuelve $y_0$
Para el siguiente punto $(x_1,y_1)$ el polinomio $P_1(x)$ será $$P_1(x)=P_0(x)+a_1(x-x_0)$$
Donde a está dada por la siguiente formula$$a_k=\frac{y_k-P_{k-1}(x_k)}{(x_k-x_0)(x_k-x_1)(x_k-x_2)...(x_k-x_{k-1})}$$
Que se puede sacar de despejar $a_k$, en el caso de $a_1$ queda así$$a_1=\frac{y_1-y_0}{(x_1-x_0)}$$
Haciendo una tabla para ordenar los calculos 
$$\begin{array}{c|ccccc}
x_0 & {\color{red} y_0}  & {\color{red} [y_0 , y_1]} & {\color{red} [y_0 , y_1 , y_2]}  &  \ldots & {\color{red} [y_0,y_1,\ldots,y_n]}  \\[1ex]
x_1 & y_1  & [y_1 , y_2]  & [y_1 , y_2 , y_3] & \ldots &  \\[1ex]
x_2 & y_2  & [y_2 , y_3]  & [y_2 , y_3 , y_4] & \ldots &  \\[1ex]
\ldots & \ldots & \ldots & \ldots & \ldots &  \\[1ex]
x_{n-1} & y_{n-1}  & [y_{n-1} , y_n]  &  &  &  \\[1ex]
x_n & y_n 
\end{array}$$
Donde: $$[y_i,y_{i+1},\ldots,y_{i+k}] = 
    \displaystyle\frac{[y_i,y_{i+1},...,y_{i+k-1}]-[y_{i+1},...,y_{i+k}]}{x_i-x_{i+k}} , \, \forall 
    i=0,1,...,n-k \, .$$
Por ultimo, una vez calculados los coeficientes el polinomio final queda asi:
$$\begin{split}
\begin{array}{lcl}
p_n(x)\, &=& [y_0] \, +\, [y_0,y_1]\, (x-x_0) \, +\, [y_0,y_1,y_2]\, (x-x_0)(x-x_1) \, +  \\
         & & \ldots +\, [y_0,y_1,\ldots,y_n]\, (x-x_0)(x-x_1)\ldots(x-x_{n-1}).
\end{array}
\end{split}$$
Para añadir un nuevo punto es tan sencillo como añadirlo a la tabla y hacer la ultima diagonal de diferencias divididas

- [ ] #Ejercicio Mirar el codigo python del profe
- [ ] #Ejercicio Programar ambos metodos
- [ ] #Ejercicio Hacerlo a mano, ambos metodos
- [ ] #Ejercicio Implementar la formula de newton de delante a atras