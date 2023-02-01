
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




