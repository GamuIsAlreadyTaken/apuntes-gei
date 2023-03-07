1. Nodo: punto del circuito donde se unen 3 o mas conductores
2. Rama: cualquier camino entre dos nodos consecutivos
3. Bucle: cualquier camino cerrado

## Leyes de Kirchhoff
1. **Ley de las corrientes** (Principio de conservación de carga)
$$\sum I_{in} = \sum I_{out}$$
Se pueden sacar (nodos - 1) de ecuaciones linealmente independientes
2. **Ley de los voltajes** (Principio de conservación de energía)
Sumatorio de las caidas de potencial en un bucle tienen que ser igual a 0
$$\sum V_{bucle} = 0$$
Se pueden sacar (ramas - numdos + 1) de ecuaciones linealmente independientes
- [ ] Hacer ejercicios

## Teoremas para simplificar circuitos
Para simplificar circuitos apagamos los generadores
V -> cortocircuito, si no hay diferencia de potencial el comportamiento es de un cable normal
I -> circuito abierto, si no pasa corriente actua como si no hubiese cable 
#### Teorema de Thévenin
Reducir un circuito a un generador de tension en serie con una resistencia donde
$$V_{TH} = V_{ab_{\text{en circuito abierto}}}$$
$$R_{TH} = R_{eq_{\text{al eliminar los generadores}}}$$
<img src="https://upload.wikimedia.org/wikipedia/commons/9/9f/Thevenin_equivalent.png" class="center">
#### Teorema de Norton
Reducir un circuito a un generacor de corriente en paralelo con una resistencia
$$R_{N} = R_{TH}$$
$$I_{N}=I_{ab_{\text{en cortocircuito}}}$$
#### Equivalencia de generadores
Entregan igual V e I a cualquier carga conectada entre sus terminales
N: Norton
g: Thévenin
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


