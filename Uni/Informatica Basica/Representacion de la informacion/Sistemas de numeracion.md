# Sistemas de numeracion
> [!example] Ejemplos de sistemas de numeracion
>- Numeros romanos
>- Numeros decimales
>- Numeros egipcios
>- Numeros binarios

> [!info] Representacion booleana
>Simbolos
> $$\{0, 1\}$$
>Sistema posicional: 
>- La posicion de los simbolos afecta al valor
>


# Conversion entre bases
- #### De cualquier base a decimal
$$N_{b}=d_{n-1}+d_{n-2}+...+d_{1}+d_{0}+d_{-1}+...+d_{-k}=\sum\limits_{i=-k}^{n-1} d_{i}b^{i}$$
- #### De decimal a cualquier base
	- Division escalonada (Parte entera)
	- Multiplicacion escalonada (Parte decimal)
- De cualquier base a cualquier base
	- Pasar a base 10 y luego a la base deseada
	- Si las bases satisfacen $q = b^n$
		- Convertir cada digito a su base superior o inferior y mantener el orden $$\begin{align*}0xF7&1D.2C\\0000\,0111\,0001&\,1101\,.\,0010\,1100\end{align*}$$
	- Si las bases satisfacen $q = n^c, b = n^d$
		- Pasar de $q$ a base $n$ y luego a base $b$
