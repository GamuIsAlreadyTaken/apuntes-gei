Metodo para encontrar raices de funciones de forma mas eficiente que [[Metodo de Dicotomía]]

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


## Metodo de Newton-Raphson
- Metodo mas eficiente para calcular raices de funciones
- [ ] Seguir con esto
