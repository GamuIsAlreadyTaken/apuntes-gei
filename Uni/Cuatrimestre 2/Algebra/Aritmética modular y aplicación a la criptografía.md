
## Algoritmo de la división entera
Dados $a, b\in\mathbb Z,\quad b\ne 0$ existen valores únicos $q,r \in \mathbb Z$ tales que 
$a=b\cdot q + r,\quad 0 \le r < |b|$

Decimos que b es divisor de a (o a multiplo de b, b divide a a) si existe
$q \in Z$ tal que $a = q\cdot b$

- [ ] Latex de b|a o a=b^. y sus opuestos


Decimos que d es divisor común de a y de b si d|a y d|b
Ejemplo: todos los números enteros, m, tienen al menos 4 divisores:
- 1, -1, m, -m
Si un número $p > 1$ solo tiene 4 divisores entonces es primo
De lo contrario, es compuesto

### Criba de Eratostenes
Para comprobar si p es primo, consiste en, empezando por $a>1$ ir tachando los multiplos de $a$ y convirtiendo $a$ en el siguiente número no tachado, hasta llegar a $a\le \sqrt p$

### Maximo común divisor (MCD)
Sean a,b \in Z, d es el mcd de a y b (d=mdc(a,b))
Si d > 0, d|a, d|b y si existe c>0 con c|a y c|b
entonces c|d

Nota: mcd(a,0) ) |a|, mcd(0,0) = 0

Nota: d=mcd(a, a_1, a_2...) existe porque
D={n\in Z \big / n|a y n|a_1 y...}

- [ ] Algoritmo de euclides


## Teorema de Bezout

## Ecuaciones diofanticas
- [ ] Hacer los apuntes

## Factorización en números primos
Todo número puede descomponenrse en un unico producto de números primos

Un número p es primo si solo admite una factorización trivial (p * 1)
Todo primo tiene 4 divisores: 1, -1, p, -p

## MCM
$$mcm(a, b)\cdot mcd(a, b) = a\cdot b$$

## Criterios de divisibilidad
Buscar los valores congruentes con $10^i$ donde $10^i$ es la potencia de 10 con la que está multiplicado cada posición del número que queremos comprobar

## Ecuaciones en congruencia
$$a\cdot x\equiv_m b$$
Se resuelve como las ecuaciones diofanticas
$$
\begin{align*}
& a x - b = \dot m \\
& a x - b = k m \\
& ax - k m = b \\
& ax + k m = b
\end{align*}
$$
siendo d el mcd(a, b), 
Entre 0 y d no se repiten soluciones y en total hay d soluciones

- [ ] Mirar video de ecuaciones diofanticas

#### Calculo de inversos
El inverso de $a$ es quel número que al multiplicarlo por $a$ el resultado sea congruente con 1 $$ax\equiv_m1$$
## Función $\phi$ de Euler
Sea $n \in \mathbb{N}$ se designa por $\phi(n)$ al número de enteros positivos menores que n y coprimos con el

$$
\begin{align*}
\phi(1) &= 1 \\
\phi(2) &= 1 \\
p\ \text{primo}\to \phi(p) &= p-1\\
\phi(p^r) &= p^r-p^{r-1} = p^{r-1}(p-1) \\
\phi(n\cdot m) &= \phi(n)\cdot\phi(m)
\end{align*}
$$


## Teorema de Euler y Pequeño teorema de Fermat
Sean $a$ y $m$ números enteros m > 1
Si son coprimos entonces $a^{\phi(m)} \equiv_m 1$ 
 Fermat: 

Si p es un número primo y coprimo con a
Entonces $a^{p-1}\equiv_m1$ 
Esto resulta en que $a^{-1} = a^{p-2}$ 