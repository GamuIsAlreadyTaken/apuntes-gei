Metodo para encontrar raices de funciones

## Prerrequisitos
- La función tiene que cumplir la hipotesis del [[Asintotas#^Teorema-de-bolzano|Teorema de Bolzano]]
- Se trata de una busqueda binaria sobre un intervalo
- Cada paso se divide el intervalo a la mitad y se descarta el subintervalo que no cumpla Bolzano
<img src="https://sites.google.com/site/pn20111/_/rsrc/1472863051082/home/metodos-cerrados/3-1-metodo-de-biseccion/bisec.JPG?height=320&width=312" class="center">

> [!info] Error de cada iteración
> Se puede estimar usando $$|x_k-\alpha|\leq\frac{b-a}{2^k}$$
## Cuando parar
Lo mas habitual es determinar cuando parar usando la diferencia relativa

> [!g] Diferencia relativa
> Mide el cambio relativo entre iteraciones consecutivas, $x_k$ y $x_{k-1}$, dado un parametro de tolerancia $tol$$$\qquad\frac{|x_k-x_{k-1}|}{|x_k|}<tol$$
^Diferencia-relativa

