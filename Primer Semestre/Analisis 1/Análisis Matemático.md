18/10/23
Ing Daniel Mlot
Ing Abundio López
# Analizar Funciones con Derivadas
### Derivar una Función con Exponente

$$\Huge{f(x)=x^x}$$
Para poder obtener la derivada de esta funcion debemos aprovecharnos de una propiedad de los $\normalsize{lnx}$
La que nos expresa que $\large{lnx^x=x\cdot lnx}$
Resolveremos $\huge{f(x)=x^x}$

1. Expresamos en 
   $\Huge{y=x^x}$
2. Aplicamos $\large{ln}$ a ambos miembros utilizando la propiedad antes vista.
   $\large{ln(y)=x.ln(x)}$
3. Derivamos ambos miembros 
 $\Huge{\frac{y'}{y}=1\cdot ln(x)+\frac{1}{x}}$ 
 4. Despejamos $\large{y'}$ y reemplazamos $\large{y=x^x}$ 
 $\large{y'=x^x(ln(x)+1)}$ 
# Teorema de Rolle
Sea $f(x)$ continua en el intervalo cerrado $[a, b]$, derivable en el intervalo $(a , b)$ y tal que $f(a) = f(b)$. Entonces existe algun $c$ perteneciente al intervalo abierto $(a, b)$ tal que $f'(c) = 0$ 

# Teorema del Valor Medio
Si $f(x)$ es continua en el intervalo $[a, b]$ y derivable en el intervalo $(a, b)$, existe algún valor $c$ perteneciente al intervalo $(a, b)$, tal que:
$$\Huge{f'(c) = \frac{f(b)-f(a)}{b - a}}$$

- $f′(c)$ representa la derivada de la función $f(x)$ en un punto $c$ dentro del intervalo $(a,b)$. Esta derivada mide la tasa de cambio instantáneo de la función en ese punto.
- $\large{\frac{f(b)-f(a)}{b - a}}$​ representa la razón de cambio promedio de la función en el intervalo $[a,b]$. En otras palabras, es la pendiente de la línea secante que conecta los puntos $(a;f(a))$ y $(b;f(b))$.
![[Pasted image 20231018163552.png]]
{Hay que poner el grafico de valor medio }

Existe una pendiente que es el resultado de la derivada para el valor $f'(c)$ que resulta ser igual a la pendiente entre $f(a)$ y $f(b)$. 

## Problemas de ejemplo
Hallar un valor de $c$ que satsifage el teorema de Rolle para $\large{f(x) = x^3-3x^2+2x+2}$ en el intervalo cerrado $\large[0, 1]$
1. El primer paso es evaluar la función en los puntos del intervalo, entonces:
$$\Large{f(a) \rightarrow f(0) = (0)^3 - 3(0)^2 + 2(0) + 2 \rightarrow f(0) = 2}$$
$$\Large{f(b) \rightarrow f(1) = (1)^3 - 3(1)^2 + 2(1) + 2 \rightarrow f(1) = 2}$$
2. Como $f(a) = f(b)$ entonces el teorema se cumple, seguidamente derivamos la función $f(x)$:
$$\Large{f(x) \rightarrow f'(x) = 3x^2 - 6x + 2}$$
3. Ahora, evaluamos $f'(x)$ en el punto $\large{c \rightarrow 3c^2 - 6c + 2 = 0}$ 
4. Hallamos los dos valores de $c$ en $f'(c)$, entonces obtenemos lo siguiente $\large \rightarrow \large{c_{1} = 1.57; c_{2} = 0.42}$    