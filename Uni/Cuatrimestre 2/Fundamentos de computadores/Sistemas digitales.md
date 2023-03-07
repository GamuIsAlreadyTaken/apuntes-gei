
Sistema analogico
- Puede obtener valores continuos
Sistema digital
- Solo puede obtener valores discretos
- Se representa por **Funciones digitales** $$F: X \mapsto Y$$

Ejemplo de sistema digital: 
- Sistema binario( {0, 1} )
	- Función digital binaria: $$F: K^n\mapsto K \qquad(K=\{0,1\})$$
	- Toda función digital se puede **Codificar** como una función digital binaria


Sistemas secuenciales y combinacionales
 Sistemas combinacionales: La salida es función exclusiva de las entradas$$F: X\mapsto Y$$
 Sistemas secuenciales: La salida es función del tiempo y las entradas (Tienen "memoria")
$$\begin{split}
F_1: S\times X &\mapsto S \\ 
F_2: S\times X &\mapsto Y \qquad\text{Mealy} \\
F_2: X&\mapsto Y \qquad\text{Moore}
\end{split}$$
![[Mealy-moore-machines.png]]


## Funciones lógicas básicas
El numero de funciones binarias posibles es $2^{2^n}$ siendo $n$ el numero de entradas

Puertas logicas basicas (Reciben 2 entradas)
<img src="https://www.schoolphysics.co.uk/age16-19/Electronics/Logic%20gates/text/Logic_gates/images/2.png" width="70%" class="center">

Las puertas logicas se pueden usar en 
- logica positiva: donde HIGH corresponde a 1 y LOW a 0, 
- logica negativa: donde HIGH corresponde a 0 y LOW a 1


## Circuitos integrados
<img src="https://s.alicdn.com/@sc04/kf/Hfcdd173ba5fa42e58dea7514b3484f766.jpg" width="70%" class="center">

> [!r]
> Tecnologías
> - Transistores bipolares: TTL, ECL
> - Transistores MOSFET: CMOS, NMOS
> - Combinación bipolar-MOSFET: BiCMOS
> 

> [!y] Niveles de integración
> - SSI (Small–Scale Integration): < 10 puertas  
> - MSI (Medium–Scale Integration): 10 – 100 puertas  
> - LSI (Large–Scale Integration): 100 – 10.000 puertas  
> - VLSI (Very Large–Scale Integration): 10.000 – 100.000 puertas  
> - ULSI (Ultra Large–Scale Integration): > 100.000 puertas
^Escala-de-integracion

Las puertas lógicas en la realidad conllevan un retardo entre cambios en la entrada y la salida, esto puede dar lugar a errores en el resultado

# Half adder
- XOR
- AND
- [ ] Añadir imagen
# Full adder
Permite sumar encadenando full adders, no se usa en la realidad por que es muy lento
- [ ] Añadir imagen

# Restas con sumas
Para restar numeros en complemento a 2 es tan sencillo compo hacer el opuesto del número que se quiere restar y sumar de forma normal
- [ ] Imagen
# Overflow
Ocurre cuando sumamos dos números con mismo signo y el resultado es un número con otro signo
- [ ] Imagen
# Sumador/Restador
- [ ] imagen

## Comparador
- [ ] imagen

## Multiplexores
- [ ] imagen
