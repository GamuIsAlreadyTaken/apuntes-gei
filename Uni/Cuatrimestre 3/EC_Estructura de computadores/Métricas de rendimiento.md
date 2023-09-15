> [!warning] Resumen de la asignatura:
> Algo simple con demasiados nombres


1. Tiempo de respuesta(latencia): $\frac{1}{\text{Tiempo de ejecucion}}$

2. Productividad(ancho de banda)

$T_{CPU} = N^o ciclos * T_{ciclo}$  

3. $\text{CPI}$ = Ciclos por instrucción: Número medio de ciclos necesarios para ejecutar una instrucción

$$
\text{CPI} = \dfrac{\overset{m}{\underset{i=n}\sum}\text{CPI}_i\text{NI}_i}{N}
$$
Donde $\text{NI}_i$ es el número total de instrucciones de tipo $i$, $\text{CPI}_i$ es el número de ciclos de reloj para esa clase de instrucciones, $N$ es el número total de instrucciones, y $m$ es el número total de tipos de instrucciones diferentes

4. MIPS: millones de instrucciones por segundo

5. FLOPS: operaciones de punto flotante por segundo

# Ley de Amdahl
La mejora obtenida en el rendimiento al utilizar una parte optimizada está limitada por la fracción de tiempo que se puede utilizar esa parte




