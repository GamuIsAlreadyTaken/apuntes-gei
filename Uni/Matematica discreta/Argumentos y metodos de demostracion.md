

si h1, h2, h3...es un conjunto de proposiciones diremos que C es una consecuencia de ellos si
$$
h_1\wedge h_2\wedge h_3\, ...\models C \longrightarrow \top
$$

Diremos que el anterior es un argumento valido si: 
$$\neg (H_i) \vee C\longrightarrow\top$$ 


Tipos de demostracion
- Demostracion directa,
	- Mediante la tabla de valor
	- Que la consecuencia sea una de las hipotesis
	- La conclusion es una tautologia
	- Que la consecuencia sea logicamente equivalente a una de las hipotesis
	- Que la consecuencia se derive de las hipotesis
	- Reglas de inferencia



- Demostracion indirecta
	- Reduccion al absurdo(ley de reduccion al absurdo)$$p\longrightarrow q \equiv(p\wedge q)\longrightarrow \bot$$
	- Principio de induccion$$\langle P(1), \forall\ k\ (P(k)\rightarrow P(k+1)\rangle\models \forall\ x \in P(x)$$
	- Principio de induccion fuerte$$\langle\ P(1),\ P(2),\ ...,\ P(k) \ \rangle\models\ P(k+1) \implies \forall\ n\ P(n)$$
