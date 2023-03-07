Objectivo transmitir y atolmacenar información atendiendo a:
- Confidecialidad (A envia un mensaje a B, solo a B)
- Autenticidad (B sabe que lo envia A)
- Integridad (B puede asegurar que el mensaje no está alterado)
- No repudio (A no puede negar haber enviado el mensaje)

## Componentes de un sistema criptografico
Conjunto de mensajes para cifrar, M
Conjunto de mensajes cifrados, C
Conjunto de claves, K
Funciones de transformación de cifrado, $E = \{E_k:M\to C, k\in K\}$
Funciones de transformación de descifrado, $D = \{D_k:C\to M, k\in K\}$

Debe verificarse que $D_k^{-1} = E_k$ 
- [ ] imagen [similar to category theory schemas]

# Criptografía simetrica o de clave privada
Simetrica: Misma clave para cifrar y descifrar
- Trasposición: cada letra cambia de lugar
- Substitución: cada letra cambia de identidad

### Cifrado afin
Es un cifrado por substitución
$M=C=\mathbb Z_n, n\in\mathbb Z, n > 1$
Clave $K = \{(a, b)\in\mathbb Z \times \mathbb Z / mcd(a, n = 1)$  
a, b, n son conocidos tanto por A como por B

$E_{(a, b)}: M\to C$ 
$E_{(a, b)}(m) = c\equiv_n am+b$

Codificar letras como números, aplicar la función afin al mensaje codificado, descodificar el resultado, enviar a B que conoce a, b y n

# Criptografía asimetrica o de clave publica
Asimetrica: Se usan distintas claves para cifrar y descifrar
Cada usuario U tiene una clave publica $k_u^1$ y otra privada $k_u^2$

Si A envia un mensaje a B, A envia: $s= E_{k_u^1}(m)$ un mensaje encriptado con su clave publica
B descifra el mensaje con su clave privada: $m=E_{K_u^2}(s)$

Luego $E_{k_u^2}\circ E_{k_u^1}$

### Firma digital
A encripta el mensaje usando su clave privada, La envía con su clave publica a B, B desencripta el mensaje con su clave privada y lo desvela con la clave publica de A

$A'\to B\to B'\to A$ 

### RSA
B elije p, q números primos grandes
$n = p* q$ 

Considera $\phi(n) = (p-1)(q-1)$ y un e con $mcd(\phi(n), e)= 1$ 
$d\equiv_{\phi(n)} e^{-1}$ 

Clave privada de B (p, q, d)
Clave publica de B (n, e)

Algoritmo de encriptado: 
$c\equiv_n m^e$ 

Algoritmo de desencriptado:
$m\equiv_n c^d$

Funciona gracias al teorema: 
$a^{ed}\equiv_n a$



