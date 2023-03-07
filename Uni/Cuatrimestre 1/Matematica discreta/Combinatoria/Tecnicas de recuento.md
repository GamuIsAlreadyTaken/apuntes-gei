# Principios básicos

### Principio de la suma
Dados los sucesos $A$ y $B$ que cumplen $A\implies\neg B$ entonces $$|A\cup B|=|A|+|B|$$
#Ejemplo Número de gorras que te puedes poner de un armario se suma con las gorras que haya en otro armario

### Principio del producto
Si un suceso puede ocurrir en varias etapas, en una $A_1$, en la siguiente $A_2$...$$|A|=|A_1||A_2|...$$

#Ejemplo Numero de combinanciones que puedes llevar con 3 camisas y 4 pantalones es $3 \times 4$ 

### Principio del palomar(Dirichlet)
Si mas de $n\times p$ elementos se distribuyen en n cajas en una de ellas hay al menos $p+1$ elementos y hay alguno que tiene como mucho $p$ elementos
$$p+1=\left\lceil\frac{n\times p}{n}\right\rceil$$


## Variaciones ordinarias
Las variaciones ordinarias de $n$ elementos tomados de $m$ en $m$ $$V(n,m)=\frac{n!}{(n-m)!}$$

## Variaciones con repetición
Variaciones de $m$ elementos repetidas $n$ veces
$$VR(m,n)=m^n$$

## Permutaciones
Las permutaciones de $n$ elementos se calculan con el factorial $$P(n) = n!$$
Dado un conjunto $A= \{a_1,a_2,a_3 ...\}$ las permutaciones del $A = S_A$

## Permutaciones con repetición
$$PR(n_1, n_2, n_3 ...n_r) = \dfrac{n!}{n_1!n_2!n_3!...n_r!}\qquad, n = n_1+n_2+n_3 ...n_r$$
## Combinaciones
La eleccion de n elemntos de un conjunto de m elementos es $$C(n,m)={\displaystyle {\binom {n}{k}}}=\frac{n!}{m!(n-m)!}$$
## Combinaciones con repetición
$$CR(n,r)=C(n+r-1,r)=\binom{n+r-1}{r} = \binom{n+r-1}{n-1}$$

## Binomios y multinomios
$$(a+b)^n=\sum_{k=0}^m\binom mka^{m-k}b^k$$
El resultado será $2^n$ terminos con coeficiente 1 antes de agruparlos

## Permutaciones circulares
De cuantas formas pueden ordenarse $m$ elementos de manera circular, marcamos a un elemento como punto de referencia y vemos como ordenar el resto
$$PC(m)=(m-1)!$$


## Números combinatorios
Estas son algunas identidades de los números combinatorios

$$\binom{m}{r} = \dfrac{m!}{r!(m-r)!}$$
$$\binom{m}{0}=1$$
$$\binom mr = \binom m{m-r}$$
$$\binom m1=m$$
#### Formula de Stieffel
$$\binom mr + \binom m{r+1} = \binom{m+1}{r+1}$$

## Multinomio de Leibniz
$$(x_1 + x_2+...+x_k)^n = \sum_{n_1+n_2+...+n_k=n}PR(n;n_1,n_2,...n_k)x_1^{n_1} x_2^{n_2}...x_k^{n_k}$$





