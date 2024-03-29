Conjunto, una coleccion de objetos(elementos) distinguibles entre si
# Conjuntos
- Todos los elementos de un conjunto son unicos (No hay repetidos)

### Para describir un conjunto: 
- Dando una propiedad. {$x\forall\ \mathbb{N}\ |\ 5\leq6 x\leq 7$} = $A$
- Por extension, listando cada elemento del conjunto. {5,6,7} = $A$


$$A = \{a,\ b,\ c\}\qquad\qquad b\in A\qquad\qquad d\notin A$$

# El Conjunto Vacio $\varnothing$
- Conjunto con ningún elemento

# Conjuntos de infinitos elementos
- Tienen infinitos elementos. $\mathbb{N, Z, Q, ...}$

### Cardinal de un conjunto
- Numero de elementos que componen un conjunto
$$\begin{align*}
&A = \{a,e,i,o,u\}\\
&\# A = |A| = 5
\end{align*}$$

## Inclusión
- Si todos los elementos de A estan en B entonces $A\subset B$
$$Si\quad A\subset B\wedge B\subset A\Rightarrow A = B$$
### Conjunto de las partes de un conjunto
- Conjunto de los subconjuntos de un conjunto
- $\varnothing$ y $x$ son subconjuntos impropios de x
- El cardinal de $P(x)$ es igual a $2^{|x|}$

### Paradoja de Cantor
- El conjunto de todos los conjuntos

## Union
...
## Intersección
...
## Complementario
...
### Disjuntos
- Conjuntos sin elementos en comun
### Cardinal de un conjunto
- Numero de elementos de este

# Aplicaciones(Funciones)
- Una aplicacion de A en B es una relación entre A y B que a cada elemento de A le asigna un unico elemento de B
<img class="center" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTmh9weRW5LLLXRq67aDEGqgU9s1M6OGD8uog&usqp=CAU">
- A es el conjunto inicial
- El **dominio** es igual a A
- B es el conjunto final
- La **imagen** esta compuesta por todos los elementos de B que participan en la relación$$f_*(A)=Img\ f$$
#### Aplicación reciproca
### Tipos de aplicaciones
- Inyectivas, si cada elemento de A tienen una sola imagen en B, (Estas funciones son estrictamente crecientes/decrecientes)
	- En una composición inyectiva solo la primera función tiene que ser inyectiva
	- $|A|\leq|B|$
- Sobreyectiva, si todos los elementos de B tienen una preimagen, (Por lo tanto, la imagen de f coincide con B)
	- En una composición sobreyectiva la segunda función tiene que ser sobreyectiva
	- $|A|\geq|B|$
- Biyectiva o Biunivoca, si es inyectiva y sobreyectiva
	- $|A|=|B|$

- Si 2 conjuntos tienen el mismo cardinal, entonces: 
	- Si $f:A\to B$ es inyectiva, entonces $f$ es biyectiva
	- Si $f:A\to B$ es sobreyectiva, entonces $f$ es biyectiva 

# Identidad de un conjunto
Denotado como $I_A$ o $id_A$ para un conjunto $A$ lleva a todos los elementos a si mismos$$A\longrightarrow A$$
Si $g\circ f = I_A$ podemos decir que 
- g es la inversa por la izquierda de f
- f es la inversa por la derecha de g
Si ambas direcciones de la composición dan $I_A$ entonces g es la inversa de f$$g=f^{-1}$$$$f=g^{-1}$$
Tanto $f$ como $g$ tienen que ser biyectivas para poder ser inversas

## Composicion de funciones
- No es conmutativa $$f\circ g \neq g\circ f$$
- Es asociativa $$h\circ (g\circ f)=(h\circ g)\circ f$$











# Reflexiva $$\forall x \in U, x Rx$$

# Transitiva $$\forall x, y, z\in U, xRy\wedge yRz \implies xRz$$

# Simetrica $$\forall x, y\in U, xRy \implies yRx$$

# Antisimetrica $$\forall x, y \in U, xRy \wedge yRx \implies x = y$$