## Señales
Variación de un valor en función del tiempo
- Señales no periodicas
	- Función escalón
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d9/Dirac_distribution_CDF.svg/325px-Dirac_distribution_CDF.svg.png" class="center">	
 - Función exponencial
<img src="https://qph.cf2.quoracdn.net/main-qimg-9c9abe3691f16c5111643244eaef84f7.webp" class="center">
- Señales periodicas
	- Función seno
	- Función cuadrada
	- Función diente de sierra
	- Función triangular
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/77/Waveforms.svg/350px-Waveforms.svg.png" class="center">


Periodo: tiempo que tarda en repetirse $[s]$
Frecuencia: Numero de repeticiones en un segundo $[s^{-1}] = [Hz]$

Señales alternas puras, el area bajo la curva es 0
Señales alternas compuestas, el area bajo la curva no es cero, se pueden descomponer en señales puras

Propiedades de una señal
Valor maximo: $X_m$
Valor de pico a pico: $2 * X_m$
frecuencia angular: $w = 2n * f$ [rad/s]
Amplitud: $X_m - X_{\text{medio}}$
Valor eficaz: $X_ef = \sqrt{X_c^2 + \frac{X_m^2}{2}}$ 
Valor continuo: $X_c$
p: fase
- [ ] poner bien el latex
$$X(t) = X_m\sin(wt+p)$$

Calcular el valor medio, $X_{\text{medio}}$
$$X_{med} = \overline{X(t)} = \dfrac 1 T\int_0^{x_m}X(t)dt$$
Señal alterna pura
$$X(t) = X_n\sin{wt+\varphi}$$
## Condensadores
Almacena energía utilizando campos electricos y la libera rapidamente
- [ ] Imagen de condensador signo
$$\dfrac Q V = C [F]$$
C = capacidad del condensador, medido en Faradios [F]
Q = carga
V = Tension

#### Circuitos RC
Circuitos con condensadores
Energía almacenada por un condensador: $$W[J]=\dfrac 1 2 QV = \dfrac 1 2 \dfrac {Q^2} C = \dfrac 1 2 CV^2$$
Se mide en Julios [J]
##### Asociación de condensadores 
- Serie: 
$$\dfrac 1 C = \dfrac 1 {C_1} = \dfrac 1 {C_2}$$
$$V = V_1 + V_2$$
$$Q = Q_1 = Q_2$$
- Paralelo:
$$C = C_1 + C_2$$
$$V = V_1 = V_2$$
$$Q = Q_1 + Q_2$$





