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

