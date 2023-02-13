Contenidos
- Fundamentos basicos de electricidad
- Ley de ohm

## Carga (Q)
q: Culombio $[C]$ $$C \to mC \to \micro C\to nC\to pC$$
El origen del campo electrico es la carga electrica
Genera una fuerza en su entorno $\left[\dfrac N C\right]$ $$\vec E = \frac{\vec F}{q}$$ 
## Intensidad (I)

Al tener un conductor expuesto a un campo electrico se genera una corriente electrica
La intensidad es la carga electrica en movimiento
Intensidad: $\vec I$
Unidad: $\left[\dfrac C S\right] = \left[A\right]$
$$I_\text{media} = \dfrac{\delta q}{\delta t}$$

## Potencial electrico (V) 
Diferencia de potencial $V_{ab}$
Entre 2 puntos A, B
Separadas una distancia d
En un campo electrico uniforme
$$\dfrac{W_{b\to A}} {q} :[v]$$
$V_{ab}$: Trabajo externo para llevar una carga de 1 C de B a A
$$\begin{split}
&V_{ab}=V_a-V_b = \pm E\cdot b \\
&V_{ab} > 0 \to V_a > V_b \\
&V_{ab} < 0 \to V_a < V_b \\
&V_a = V_a - V_b\qquad V_b\to0
\end{split}$$
## Resistencia (R)
Ohmios: $[\Omega]$ 
Conductividad $G=\dfrac I R$ $[\Omega^{-1}]$
$\rho$: Resistividad $[\Omega\cdot m]$
$$R = \rho \dfrac L S : \left[\Omega\cdot m\dfrac{m}{m^2} \right]= \left[\Omega\right]$$
L: longitud del resistor
S: area de la sección del resistor

- [ ] Ponerlo bonito y repasar

## Potencia electrica (P)
Indica como varía la energía en función del tiempo
$$P=\dfrac{\delta W}{\delta t} = \dfrac{\delta W}{\delta q}\cdot\dfrac{\delta q}{\delta t} = V\cdot I$$
Watts: $[W]$ 

## Principio de conservación de la energía
Sum(Pe) = Sum(Pa)
Pe: potencia entregada (P=V·I > 0)
Pa: potencia absorbida (P=V·I < 0)


## Ley de Ohm
V = I · R

## Ley de joule

Pdisipada en R = V·I [W], siempre >= 0


## Simplificación de circuitos
Asociación de resistencias

1. En serie (Seguidas): Divisor de tensión

- [ ] Añadir imagen de resistencias en serie
v = v_1+ v_2
v = I·R_1 + I·R_2
V= I(R_1+R_2)
V = I· R_eq
R_eq = R_1 + R_2

2. En paralelo (El camino se divide): Divisor de corriente
Si la corriente da negativa significa que la dirección de esta es la contraria a la asumida
- [ ] Imagen de resistencias en paralelo
I = I_1 + I_2
V/R_eq = V/R_1 + V/R_2
V·1/R_eq = V·(1/R_1 + 1/R_2)

1/R_eq = 1/R_1 + 1/R_2 = (R1 + R2)/(R1·R2)
R_eq = (R1+R2)/(R1·R2)

I1 = I·R2/(R1+R2)
I2 = I·R1/(R1+R2)

- [ ] Latex

## Generadores
### Fuentes de tensión

- [ ] Imagen de batería 
La ralla mas larga es el positivo, la mas corta el negativo

##### Generador ideal
El voltaje que emite es independiente de la corriente
- [ ] imagen
##### Generador real
$R_g$: Representa las perdidas del mundo real, funciona en serie
$$V=V_g + I\cdot R_g$$
Conforme la corriente aumenta la carga disminuye
$$P_v=P_g-P_{R_g}$$
La potencia que da un generador real nunca es la maxima
- [ ] Imagen



### Fuentes de corriente
##### Generador ideal 
La corriente es independiente de la carga
- [ ] Imagen
##### Generador real
$R_g$: Representa las perdidas del mundo real, funciona en paralelo
- [ ] Imagen
$$I= I_g - \dfrac V {R_g} $$
Conforme la carga aumenta la corriente disminuye
$$P_I=P_g - P_{R_g}$$

- [ ] Hacer ejercicios del boletin!

## Asociación de generadores
- 2 generadores de corriente en serie
	- La corriente tiene que ser igual en ambos
- 2 generadores de corriente en paralelo
	- La corriente es la suma de ambas corrientes
- 2 generadores de tensión en serie
	- La tensión es la suma de ambas
- 2 generadores de tensión en paralelo
	- La tensión es la misma en ambos

- [ ] Poner bonito

## Herramientas de analisis de circuitos
- [ ] Mover a otra hoja?
1. Nodo, punto del circuito donde se unen 3 o mas conductores
2. Rama, cualquier camino entre dos nodos consecutivos
3. Bucle, cualquier camino cerrado
## Leyes de Kirchhoff
1. Ley de las corrientes (Principio de conservación de carga)
$$\sum I_{in} = \sum I_{out}$$
Se pueden sacar (numero de nodos - 1) de ecuaciones linealmente independientes
2. Ley de los voltajes (Principio de conservación de energía)
Sumatorio de las caidas de potencial en un bucle tienen que ser igual a 0
$$\sum V_{bucle} = 0$$
Se pueden sacar (numero de ramas - numero de numdos + 1) de ecuaciones linealmente independientes
- [ ] Hacer ejercicios

## Teoremas para simplificar circuitos
#### Teorema de Thévenin
Reducir un circuito a un generador de tension en serie con una resistencia donde
## $$V_{TH} = V_{ab_{\text{en circuito abierto}}}$$
## $$R_{TH} = R_{eq_{\text{al eliminar los generadores}}}$$
eliminación de generadores
V -> cortocircuito
I -> circuito abierto
- [ ] Imagen
#### Teorema de Norton
Reducir un circuito a un generacor de corriente en paralelo con una resistencia
## $$R_{N} = R_{TH}$$
## $$I_{N}=I_{ab_{\text{en cortocircuito}}}$$
- [ ] Imagen
#### Equivalencia de generadores
Entregan igual V e I a cualquier carga conectada entre sus terminales
$$I_{N} = \dfrac {V_g}{R_g}$$
$$R_N = R_g$$
- [ ] Imagen


## teorema de la superposición
la respuesta de un circuito lineal con varías fuentes de energía es igual que la suma de las respuestas indeividuales de cada fuente

generadores:
V -> cc
I -> ca


> [!important] Truco
> Marcar los puntos de mayor y menor potencial en los esquemas de circuitos
