Vamos a ver funciones en [[Sistemas digitales#^Escala-de-integracion|escala MSI]]

Indice: 
Aritmetico-logicas
Ruta de datos
Manipuladores de codigo

Codificación de numeros
- Sin signo (binario puro)
- Con signo (1 bit de signo, el resto representan el valor)
	- Signo-magnitud
	- Complemento a 1
	- Complemento a 2

Vamos a usar el complemento a 2 (suma y resta con un solo circuito + solo 1 representación para el 0)

El rango de la codificacion en complemento a 2 es $[-2^{n-1}, +2^{n-1}-1]$
siendo $n$ el número de bits del formato

Extensión de signo, para pasar de un formato menor a otro mayor, replicamos el bit de signo. $$\begin{split}0111 &\to 00000111 \\ 7 &\to 7\end{split}$$ 

