
Cuerpo: conjunto numerico ($\mathbb Q, \mathbb R, \mathbb Z_p$)
En un cuerpo siempre va a existir el elemento inverso

## Teorema de Wilson
$$(p-1)! = p-1$$

Por que multiplicas cada número por su inverso excepto, $p-1$, y $1$ que son su propio inverso

## Resolución de sistemas usando matrices
Si la columna de terminos independientes es todo $0$ el sistema es homogeneo y siempre sitene solución, todas las variables son $0$ y si hay una solución entonces cualquier multiplo de esta será una solución

Un sistema se puede clasificar por su número de soluciones: 
- Compatible determinado (SCD): 1 sola solución
- Compatible indeterminado (SCI): mas de 1 solución
- Incompatible (SI): 0 soluciones

2 sistemas son equivalentes si tienen las mismas soluciones
Las siguientes operaciones elementales* transforman un sistema en otro equivalente:
- Intercambiar filas
- Escalar filas
- Sumar filas entre sí

> [!info] Sistemas graduados
> Sistemas con matriz triangular


> [!info] Matriz escalonada
> - Todas las filas compuestas unicamente por 0 están abajo
> - En cada fila el primer elemento no 0 es un  1 (pivote)
> - En dos filas consecutivas la que está mas abajo tiene el pivote mas a la derecha
> - Si todos los elementos de las columnas son 0 salvo el pivote se trata de una matriz escalonada y reducida


### Algoritmo de eliminación Gaussiana
Transformar la matriz ampliada de un sistema en otras matrices equivalentes mas sencillas utilizando las [[Sistemas de ecuaciones lineales, matrices y determinantes#Resolución de sistemas usando matrices|operaciones elementales]]


