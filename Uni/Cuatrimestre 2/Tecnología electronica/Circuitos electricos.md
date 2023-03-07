Contenidos
- Fundamentos basicos de electricidad
- Ley de ohm
- Reducción de circuitos 
	- Thévenin
	- Norton
	- Superposición

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

## Potencia electrica (P)
Indica como varía la energía en función del tiempo
$$P=\dfrac{\delta W}{\delta t} = \dfrac{\delta W}{\delta q}\cdot\dfrac{\delta q}{\delta t} = V\cdot I$$
Watts: $[W]$ 

## Principio de conservación de la energía
$$\sum P_\text{entregada} = \sum P_\text{absorbida}$$
$Pe$: potencia entregada (P=V·I > 0)
$Pa$: potencia absorbida (P=V·I < 0)


## Ley de Ohm
$$V = I · R$$

## Ley de joule

$$P_{\text{disipada en R}} = V·I , siempre \ge 0$$

## Simplificación de circuitos
Asociación de resistencias
<img src="https://phys.libretexts.org/@api/deki/files/8222/CNX_UPhysics_27_01_SeriesRes.jpg?revision=1" class="center">
1. En serie (Seguidas): Divisor de tensión

$$
\begin{align*}
R_{eq} &= R_1 + R_2 \\
V &= I· R_{eq}
\end{align*}
$$

2. En paralelo (El camino se divide): Divisor de corriente
Si la corriente da negativa significa que la dirección de esta es la contraria a la asumida
$$
\begin{align*}
I &= \dfrac {V}{R_{eq}}\\
\dfrac 1 {R_{eq}} &= \dfrac 1 {R_1} + \dfrac 1 {R_2} \\
\end{align*}
$$

## Generadores
<img src="https://upload.wikimedia.org/wikipedia/en/thumb/9/9f/Non-ideal_voltage_and_current_sources.svg/1200px-Non-ideal_voltage_and_current_sources.svg.png" class="center">
### Fuentes de tensión
La ralla mas larga es el positivo, la mas corta el negativo

1. Generador ideal
El voltaje que emite es independiente de la corriente
2. Generador real
Representa las perdidas del mundo real, funciona en serie
$$V=V_g + I\cdot R_g$$
Conforme la corriente aumenta la carga disminuye
$$P_v=P_g-P_{R_g}$$
La potencia que da un generador real nunca es la maxima

### Fuentes de corriente
1. Generador ideal 
La corriente es independiente de la carga
2. Generador real
Representa las perdidas del mundo real, funciona en paralelo
$$I= I_g - \dfrac V {R_g} $$
Conforme la carga aumenta la corriente disminuye
$$P_I=P_g - P_{R_g}$$

- [ ] Hacer ejercicios del boletin!

## Asociación de generadores
- 2 generadores de corriente en serie
	$I_1 = I_2$
- 2 generadores de corriente en paralelo
	$I = I_1 + I_2$
- 2 generadores de tensión en serie
	$V = V_1 + V_2$
- 2 generadores de tensión en paralelo
	$V_1 = V_2$

