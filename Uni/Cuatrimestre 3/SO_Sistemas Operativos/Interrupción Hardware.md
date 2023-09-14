Las peticiones de interrupción son prioritarias

IRQ 0 -> Timer, entre otras cosas avisa cada 25ms para cambiar de programa en la CPU



[Stack del procesador]: Hardware para cada rutina del CPU

### El procesador tiene 2 modos de ejecución
Desde el punto de vista del procesador:
- Modo normal: No se puede ejecutar instrucciones de I/O
- Modo privilegiado: Se pueden ejecutar todas las instrucciones máquina
Cuando se ejecuta una interrupción hardware el procesador pasa a modo privilegiado

Desde el punto de vista del sistema operativo:
- Modo usuario
- Modo núcleo o sistema

# Interrupción Software
Emula una interrupción hardware a través de software `INT86`

# System Calls
Son el puente entre usuario y kernel

Cuando el compilador encuentra una system call: 
1. Carga el tipo de interrupción en un registro especifico
2. Activa la interrupción hardware
3. Se lee la condición de error de un registro especifico

Al tener que usar llamadas preestablecidas (System calls) el acceso a los recursos del sistema esta limitado desde la parte del usuario:
- Numero de entradas finito
- El acceso está limitado
- El control está en el SO
