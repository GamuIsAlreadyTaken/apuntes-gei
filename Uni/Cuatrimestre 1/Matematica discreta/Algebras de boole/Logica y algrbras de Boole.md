# Logica
- Trata de formalizacion del lenguaje y los metodos de razonamiento, reglas y tecnicas para saber si un argumento es valido o no

## Las proposiciones
Son oraciones declarativas que pueden ser *ciertas* o *falsas* 
- Una proposicion puede ser
	- **Atomica** o **Primitiva** si no se puede descomponer en proposiciones mas sencillas
	- **Compuesta** si puede descomponerse

### Proposiciones bien formadas (F.B.F)
- Una composicion esta bien formada si:
	- Es atomica
	- Si es de la forma:$$\neg p,\quad\text{siendo p una F.B.F}$$
	- Si es de la forma: 
	$$\begin{align*}
	&p\wedge q\\
	&p\vee q\\ 
	&p\implies q\\
	&
	\end{align*}$$

### Operadores logicos, conectivos o juntores
- Combinan 2 proposiciones para obtener una mas compleja 
1. Disuncion: $$p\vee q\quad,\quad\text{'p ó q'} $$
2. Conjuncion: $$p\wedge q\quad, \quad\text{'p y q'}$$
3. Negacion:  $$\neg p\quad,\quad\text{'no p'}$$
 4. Condicional: $$p\longrightarrow q \quad,\quad\text{'si p entonces q'}$$
 5. Doble condicional: $$p\longleftrightarrow q\quad, \quad\text{'p si y solo si q'}$$El doble condicional es equivalente a: $$p\Longleftrightarrow q = (p\implies q)\wedge (p\Longleftarrow q)$$ 
## Prioridad de operadores: 
### $$\underset{Negacion}{\neg}\qquad>\qquad \underset{Conjuncion}{\wedge} \quad/\quad \underset{Disyuncion}{\vee} \qquad >\qquad \underset{Condidional}{\implies} $$

> [!info] Formulas bien formadas
> - Proposiciones atomicas
> - si p es una formula bien formada entonces no p tambien
> - si p y q son formulas bien formadas entonces p y q, p o q, y si p entonces q tambien lo son

Tablas de verdad: es un metodo que proporciona valores de verdad a proposiciones compuestas a partir de los valores de verdad de sus proposiciones atomicas

##### Ley de Morgan
- La negacion del conjunto es igual a la disyuncion de las negaciones
$$\neg (p\wedge q) =\neg p\vee\neg q$$
- La negacion de la disyuncion es igual a la conjuncion de las negaciones
$$\neg (p\vee q) =\neg p\wedge\neg q$$

### Interpretacion de una formula
- Una interpretacion de una formula es un valor de verdad obtenido a partir de los valores de verdad de las proposiciones atomicas que la definen
- Ejemplos de interpretaciones: 
	- $\top$, Tautologia: todos los valores de verdad son verdaderos
	- $\bot$, Contradiccion: todos los valores fuesen falsos
	- Contingencia: cualquier otro caso
- Si $p\longleftrightarrow q$ es una tautologia decimos que $p$ y $q$ son equivalentes$$\text{Si }p\longleftrightarrow q\text{ es }\top,\quad p\iff q$$
- Si $p\longrightarrow q$ es una tautologia decimos que p implica logicamente a q$$\text{Si }p\longrightarrow q\text{ es }\top,\quad p\implies q$$
### Tablas semanticas (Arbol semantico)


Un conjunto de proposiciones es **consistente** si la conjuncion de todas es una contingencia (Admite un modelo y por lo tanto, un modelo comun a todas)


### Modelos de interpretacion
Si cuando las primitivas son verdad la proposicion es verdad se trata de una **interpretacion modelo**
Si la proposicion es mentira se trata de un **contraejemplo**

