Metodo para encontrar raices de funciones de forma mas eficiente que [[Metodo de Dicotomía]]

Se basa en que la función debe parecerse a la recta tangente en un punto, por lo que la raiz de la función tiene que estar cerca de la raiz de la recta tangente
<img src="https://luishervella.github.io/JB_Calculo1_UDC/_images/cap_der_newton.png" class="center">
Dado un punto de inicio $x_0 \in (a,b)$ la raiz de la [[Propiedades basicas#^Recta-tangente|tangente]] es: $$x_1=x_0-\dfrac{f(x_0)}{f'(x_0)} \qquad f'(x_0)\neq0$$
Iterando con la formula anterior tenemos que $$x_{k+1}=x_k-\dfrac{f(x_k)}{f'(x_k)} \qquad f'(x_k)\neq0$$


## Pasos
1. Probar que se puede aplicar el teorema de bolzano
2. Conseguir un punto de arranque, P$_1$
3. Calcular tangente de f en P$_1$ 
4. Intersecarla con y=0
5. Evaluar f en el punto de corte, P$_2$
6. Volver al paso 3

> [!warning] La derivada en cada punto evaludao debe ser no nula ($f'(x_n)\neq 0$)

> [!code] En SymPy
> sp.diff -> derivada en sympy

mismo criterio de parada que el del metodo de dicotomia
