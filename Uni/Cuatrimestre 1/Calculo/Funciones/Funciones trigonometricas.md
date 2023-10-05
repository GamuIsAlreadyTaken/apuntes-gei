# Seno $\sin{x}$
Representa la $y$ en la circunferencia unitaria

> [!code] En sympy
> $$sp.sin(x)\to\sin{x}$$

> [!y] ### Propiedades del seno
> - $Dom\ \sin=\mathbb{R}$
> - $Im\ f=[-1,1]$
> - Es una función [[Definiciones basicas#^Simetria-en-funciones|impar]]
> - Su [[Definiciones basicas#^Periodo-en-funciones|periodo]] es $2\pi$ 
> 
# Coseno $\cos{x}$
Representa la $x$ en la circunferencia unitaria

> [!code] En sympy
> $$sp.cos(x)\to\cos{x}$$

> [!g] ### Propiedades
> - $Dom\ \cos=\mathbb{R}$
> - $Im\ f=[-1,1]$
> - Es una funcion [[Definiciones basicas#^Simetria-en-funciones|par]]
> - Su [[Definiciones basicas#^Periodo-en-funciones|periodo]] es $2\pi$

<img src="https://i.pinimg.com/originals/ec/f5/ba/ecf5ba982ff3de01fb074a8dc58d6715.gif" class="center" height="400">
> [!important] Identidades del coseno y el seno
> Primarias
> - $\sin^2(x)+cos^2(x)=1,\qquad\forall x\in\mathbb{R}$
> - $\sin(x+y)=\sin(x)\cos(y)+\cos(x)\sin(y),\qquad\forall x,y\in\mathbb{R}$
> - $\cos(x+y)=\cos(x)\cos(y)-\sin(x)\sin(y),\qquad\forall x\in\mathbb{R}$
>
> Secundarias
> - $\sin(-x)=-\sin(x)$
> - $\cos(-x)=\cos(x)$
> - $\sin(x+\frac{\pi}{2})=\cos(x)$
> - $\sin x = - \cos\left(x + \frac{\pi}{2}\right)$

> [!r] # Tangente $\tan x := \frac{\sin x}{\cos x}$
> - $Dom\ \tan=x\in\mathbb{R}\,|\cos x \neq 0\rightarrow \frac{\pi}{2}*nx,\,n\in\mathbb{Z}$
> - $Im\ \tan=\mathbb{R}$
> - Es una funcion [[Definiciones basicas#^Simetria-en-funciones|impar]]
> - Su [[Definiciones basicas#^Periodo-en-funciones|periodo]] es $\pi$



### Funciones inversas
Al no ser inyectivas no existe la funcion inversa para resolverlo se coge un intervalo de las funciones donde si sean inyectivas

> [!y] ## Arcoseno
> - $Dom\ \arcsin=[-1, 1]$
> - $Im\ \arcsin=[-\frac{\pi}{2}, \frac{\pi}{2}]$
> - Es una función [[Definiciones basicas#^Simetria-en-funciones|impar]]
> - No es periodica
> <img src="https://luishervella.github.io/JB_Calculo1_UDC/_images/cap3_funcion_asin.png" class="center" >

> [!g] ## Arco coseno
> - $Dom\ \arccos=[-1,1]$
> - $Im\ \arccos=[0,\pi]$
> - No es simetrica
> - No es periodica
> <img src="https://luishervella.github.io/JB_Calculo1_UDC/_images/cap3_funcion_acos.png" class="center">

> [!r] ## Arcotangente
> - $Dom\ \arctan=\left[-\frac{\pi}{2},\frac{\pi}{2}\right]$
> - $Im\ \arctan=\left[-\frac{\pi}{2},\frac{\pi}{2}\right]$
> - Es una funcion impar
> - No es simetrica
> <img src="https://luishervella.github.io/JB_Calculo1_UDC/_images/cap3_funcion_atan.png" class="center">


> [!important] Mermaid can be used in code blocks
> ```mermaid 
> 	stateDiagram
> 		a --> b
> 		b --> a
> ```

