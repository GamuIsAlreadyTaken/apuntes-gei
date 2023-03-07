
## Experimento aleatorio
- Todos los posibles resultados son conocidos de antemano
- Puede repetirse en identicas condiciones cualquier cantidad de veces
- El resultado de cada realizacion concreta del experimento es impredecible

> [!r] #### Ley de estabilidad de las frecuencias 
> Cuando las repeticiones tienden a infinito las frecuencias relativas se estabilizan

Espacio muestral ($\Omega$): conjunto formado por todos los posibles resultados. Puede ser:
- Discreto
- Continuo

Suceso: cualquier subconjunto del espacio muestral
Suceso seguro: otro nombre para el espacio muestral $\Omega$
Suceso elemental: suceso de un solo elemento
Suceso imposible ($\emptyset$): conjunto no contenido en el espacio muestral
$P(\Omega)$: partes del espacio muestral

Union de sucesos: $\cup$ (or)
Unterseccion de sucesos: $\cap$ (and)
Suceso complementario: A (superrallado)

Sucesos compatibles: si su interseccion es != $\emptyset$ 
- [ ] Latex...

Partición de un espacio muestral: igual que una partición normal
- La unión de todos da el espacio mustral
- Ninguno se interseca con el resto de subconjuntos


> [!g] Definición de probabilidad
> La probabilidad es una aplicación $P: P(\Omega)\to[0, 1]$ que cumple las siguientes condiciones:
> - El suceso seguro tiene $P(\Omega) = 1$
> - La probabilidad de la unión de sucesos incompatibles es igual a la suma de las probabilidades individuales $$P(A_1 \cup A_2)=P(A_1) + P(A_2)$$
> - $P(\emptyset) = 0$
> - $P(\overline{A}) = 1 - P(A)$
> - $P(A\cup B) = P(A) + P(B) - P(A\cap B)$

- [ ] descubrir como poner complementario de A

## Probabilidad condicionada
$$P(A|B) = \dfrac{P(A\cap B)}{P(B)}$$
Probabilidad de b sabiendo que a
o
Probabilidad de a antes que b
$$P(A\cap B)\cdot P^{-1}(B)$$