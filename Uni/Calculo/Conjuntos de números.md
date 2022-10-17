# Numeros naturales $\pmb{\mathbb{N}}$
##### $$\mathbb{N}=\{1,2,3,...\}$$
- $\{0\}$ puede o no incluirse
---
# Numeros enteros $\pmb{\mathbb{Z}}$
##### $$\mathbb{Z}=\{...,-2, -1, 0, 1, 2, ...\}$$
---
# Numeros racionales $\pmb{\mathbb{Q}}$
##### $$\mathbb{Q}=\{ p/q,\quad p\in\mathbb{Z},\quad q\in\mathbb{N}\}$$
---
# Numeros irracionales $\pmb{\mathbb{I}}$
##### $$\mathbb{I}=\{p\notin\mathbb{Q}\}$$
---
# Numeros reales $\pmb{\mathbb{R}}$
##### $$\mathbb{R}=\mathbb{Q}\cup\mathbb{I}$$
- Es un conjunto continuo
#### Propiedad arquimediana
- Dados 2 numeros reales siempre podemos crear un número menor que el primero y mayor que el segundo
#### 2. Propiedad. Densidad de $\mathbb{Q}$ en $\mathbb{R}$
- Dados 2 numeros reales siempre va a haber un numero racional entre ellos
---

# Numeros complejos $\pmb{\mathbb{C}}$
Los numeros complejos se componen de una parte real y una imaginaria
##### $$a+bi$$
Siendo i = $\sqrt{-1}$

Surgen para dar solucion a la siguiente equiacion:
$$x^2+1=0$$

los numeros complejos se representan en el eje cartesiano $$\mathbb{C}=\{a\ +\ b*i,\ a,b \in \mathbb{R}\}$$
# Representaciones de números complejos
## 1. Cartesiana $$(a,b)$$
## 2. Binomica $$a + bi$$

### Operaciones
Si las partes imaginarias son 0 las operaciones deben ser consistentes con las operaciones del conjunto $\mathbb{R}$
- ###### Suma: $$a+bi+c+di= (a+c)\ +\ (b+d)i$$
Se suman las partes reales con las reales y las imaginarias con las imaginarias

- ##### Multiplicacion: $$(a + bi)(c + di) = ac + adi + bci + bd i^2 = (ac-bd) + (bci+adi)$$
Se distribuye como en la multiplicacion de polinomios
- **Elemento neutro**: al multiplicar por el no cambia el resultado$$a*b = a$$En el caso de la multiplicacion de $\mathbb{C}$ es el mismo que en la multiplicacion en $\mathbb{R}$, es decir $1$
- **Elemento inverso**: el resultado al multiplicar un numero por su inverso es $1$$$a*a^{-1} = 1$$Dado el numero complejo: $z=a+bi$
  Su inverso será: $$z^{-1}=\frac{a}{a^2+b^2}-\frac{b}{a^2+b^2}i$$ 
##### Potenciacion
$$i^n = i^{n\mod 4}$$ 

##### Division
$$\frac{a}{b} = a * b^{-1}$$


##### Conjugado de un complejo
- el conjugado de $a + bi$ es $a - bi$
- el producto de un complejo por su conjugado es un numero real


## 3. Polar 
Representa un punto por la magnitud del vector $M$ (del punto a 0,0) y el angulo $\theta$ con $x$ positivo
### $$z = a + bi = M_\theta$$
$$M = \sqrt{a^2 + b^2}$$$M$ será la hipotenusa del triangulo que se forma al usar $a$ y $b$ como lados
$$\theta = arctan\left(\frac{b}{a}\right)$$Y $\theta$ será la inversa de la tangente
$$\cos{\theta} = \frac{a}{M} \longrightarrow a = M\cos{\theta}$$
$$\sin{\theta}=\frac{b}{M}\longrightarrow b=M\sin{\theta}$$Por lo que:$$a+bi = M\cos{\theta}+M\sin{\theta}\ i=M(\cos{\theta}+\sin{\theta}\ i) $$
> [!warning] Si el complejo esta en otro sector distinto del 1º $\theta$ no sale directamente de la arcotangente de la calculadora

La forma polar facilita los calculos pues:
#### $$a_b *c_d=(a*c)_{b+d}$$
La division queda: 
#### $$\frac{a_b}{c_d}=\left(\frac{a}{c}\right)_{b-d}$$
Y la potenciacion: 
#### $$(a_b)^n=(a^n)_{nb}$$
#### Propiedad(Formula de De Moivre)$$\left(\cos{x}+i\sin{x}\right)^n=\cos{nx}+i\sin{nx}$$
Raizes de un numero complejo (Para mañana)

- [ ] #Ejercicio Hacer los ejercicios del jupyter notebook

---

Se da que:
### $$\mathbb{N}\in\mathbb{Z}\in\mathbb{Q}\in\mathbb{R}\in\mathbb{C}$$

> [!b] ### Conjunto acotado
>Decimos que un conjunto esta acotado si hay numeros mayores o menores no pertenecientes a el, de ello surgen los siguientes terminos:
>
> **Cota inferior de un conjunto**: todo numero menor que el conjunto
>- **Infimo** del conjunto: la mayor de las cotas inferiores
>- **Minimo** del conjunto: el infimo si este forma parte del conjunto
>- Un conjunto esta **acotado inferiormente** si tiene cota inferior 
>
> **Cota superior de un conjunto**: todo numeros mayor que el conjunto
>- **Supremo** del conjunto: la menor de las cotas superiores
>- **Maximo** del conjunto: el supremo si este forma parte del conjunto
>- Un conjunto esta **acotado superiormente** si tiene cota superior

^Conjuntos-acotados
