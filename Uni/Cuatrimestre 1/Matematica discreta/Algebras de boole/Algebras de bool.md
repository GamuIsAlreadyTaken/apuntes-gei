Un algebra de bool esta formada por un conjunto

A = {a,b,c,d,...}, 2 operaciones binarias '+' y '*' y una operación unaria '-'(complemento/inversion)

- A es cerrado para las 3 operaciones
- Existen 2 elementos distinguidos 
	- Neutro, para ambas operaciones binarias
	- Complementario, para ambas operaciones binarias
- Las operaciones binarias cumplen la propiedad conmutativa$$a+b =b+a\qquad a*b = b*a$$
- Las operaciones binarias cumplen la propiedad asociativa$$a+(b+c)=(a+b)+c\qquad a*(b*c)=(a*b)*c$$
- Las operaciones binarias cumplen la propiedad distributiva$$a*(b+a)=(a*b)+(a*c)\qquad a+(b*c)=(a+b)*(a+c)$$

#### Ejemplos
- {Proposiciones logicas}, $\wedge\ ,\vee\ ,\neg$
- {0, 1}, +, $*$, $\bar{}$


### Idempotencia $$a = a + a$$
#### Ley de acotacion$$1+b = 1$$
#### Ley de absorcion$$a+(a*b)=a$$

Forma normal cojuntiva (Productos de sumas)
- Producto de las sumas de los 0 de la tabla
Forma normal disyuntiva (sumas de productos)
- Suma de los productos de los 1 de la tabla
- Minimal, no hay otra con menos sumandos
- Cualquier otra con mismo numero de sumandos tiene menos variables en alguno de los sumandos


## Diagramas o mapas de karnaugh 
- Es una tabla con los posibles estados de las variables en los lados (Arriba y derecha)
- Buscar implicantes primos esenciales para poder simplificar mas tarde

#### Implicantes, los 1 de la tabla
- Primos, si son adyacentes
- Esenciales, Cuando no hay ningún otro implicante que pueda cubrir sus unos




