# Analisis 1
##### Pequeño Recordatorio que cuando hacemos el metodo de la segunda derivada para analizar una curva si el resultado es + es un punto minimo el analizado y viceversa
## Concavidad(Hacia Arriba las Rt) o Convexidad(Hacia Abajo las Rt) de la curva
(Rt = Rectas Tangentes de la curva)
### Concavidad
La Grafica de la curva en un punto empieza a cambiar de concava a conveza o viceversa, ese punto es llamado "Punto de Inflexión"

#### Demostración Matematica.
- Desmotramos que es convexo cuando la 2nda derivada cumple: $f''(x)<0$ 
- Demostramos que es un punto de inflexión cuando la 2nda derivada cumple: - Desmotramos que es convexo cuando: $f''(x)=0$
- Desmotramos que es convexo cuando la 2nda derivada cumple: $f''(x)>0$ 

![Imagen representativa](https://calculo.cc/temas/temas_bachillerato/primero_ciencias_sociales/funciones_derivadas_apli/imagenes/teoria/concavidad_convexidad/concava_convexa_graf.gif)

#### Analizar donde es Concava y donde convexa. Esbozar una grafica que demuestre todos los rasgos significativos de la función
$f(x)=2x^3+9x^2-24x-10$ 
<iframe src="https://www.geogebra.org/calculator/uqr8u6dw?embed" width="600" height="400" allowfullscreen style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0"></iframe>

- 1era Derivada $f'(x)=6x^2+18x-24$ 
    - Obtenemos los puntos criticos resolviendo la ecuación: $f'(x)=6x^2+18x-24 = 0$ 
    obtenemos como resultados:
        - $x=1$
        - $x=-4$

- 2da Derivada $f''(x)=12x+18$
    - Analizaremos estos puntos para identificarlos
        - $f(1)=12(1)+18=-23$ (Obtuvimos un valor negativo entonces este resulta ser un punto Maximo)
        - $f(-4)=12(-4)+18=102$ (Obtuvimos un valor positivo entonces este resulta un punto minimo)
- Para hallar el punto de inflexión utilizamos la 2nda derivada y sabemos que debe ser un punto neutral donde no debe ser ni positivo ni negativo porque por ende serian puntos minimos y maximos.
    - $f''(x)=12x+18$
    - $12x+18=0$
    - $x=1.5$
El punto de inflexión resulta ser ($x = 1.5$)

## Ejercicios de optimización con derivadas.
###  Se desea acotar un terreno rectangular de $1800m^2$ limitado con un río (recto). Si los otros 3 lados se vallan 
    - ¿Cual es el minimo perimetro de valla ? 
    - ¿Cuales son las dimensiones del terreno optimo? 
- Resolución:
Como existen infinitas formas de vallar nuestro perimetro lo que debemos es optimizar a traves del uso de derivadas
    - 1er Paso:
        - Establecemos que el Perimetro de un rectangulo se Calcula con: $P = 2\cdot y+x$
        - El valor que sabemos que no variara es el area de $1800m^2$ y podemos utilizar: $Area= x \cdot y$ que se veria $1800 = x \cdot y$ del cual despejaremos el valor de $y = \frac {1800}{x}$
        
    - 2do Paso:
        - Insertamos la ecuación del Area en función de $y = \frac {1800}{x}$ en la ecuación del Perimetro: $P = 2\cdot (\frac {1800}{x})+x$
        - Podemos Derivar $P = 2\cdot (\frac {1800}{x})+x$
        - En $P' = 3600x^{-2} + 1$
        - Igualamos a $0$ para Hallar el punto critico
        - $3600x^{-2} + 1=0$
        - $x=60$
    - 3er Paso:
        - Ahora que tenemos este punto critico debemos analizar si es un punto maximo o minimo, necesitamos que sea el punto minimo para obtener la cantidad de minima de vallas necesarias. Lo haremos con el metodo de la 2nda derivada.
        - $P''=7200x^{-3}$
        - Cuando ya tenemos la 2nda derivada la igualaremos a 0 para analizar si es el punto minimo que necesitamos.
        - $0=7200x^{-3}$
        - Nos resulta un x positivo entonces si se cumple que sea un valor minimo :)
    - 4to Paso:
        - Para obtener el 2ndo valor que necesitamos reemplazamos $x=60$ en nuestra primera formula de Area
        - $Area= x \cdot y $
        - $Area= 60 \cdot y $
        - $y = 30$
    - Ya obtuvimos los valores necesarios y el ejercicio esta resuelto.
### Se va a construir un corral doble en forma de dos rectangulos identicos con un lado en común, si se dispone $120ft$ de valla 
    - ¿Que dimensiones del corral hacen máxima el area total?
- Resolución:
    - 1er Paso: 
        - Sabemos que la figura que nos describieron su perimetro se calculara de la siguiente manera: $P= 3y + 4x$
        - Su Area se calcularia de la misma manera que un rectangulo calquiera. $Area= x \cdot y $ y como necesitamos el area de los rectangulos seria $Area = 2\cdot x\cdot y$
        - Tenemos como dato $120ft de Perimetro entonces podemos despejar en función de $x = \frac {120-3y}{4}$
        - Este valor de $y$ insertamos en nuestro calculo de Area: $Area = 2 \cdot(\frac {120-3y}{4}) \cdot y $
    - 2do Paso Derivamos esta función para encontrar un punto critico.
        - $Area = 2 \cdot(\frac {120-3y}{4}) \cdot y $
        - $Area' = 60-3y $
        - $60-3y=0$
        - $y=20$
    - 3er Paso:
        - Ahora que tenemos este punto critico debemos analizar si es un punto maximo o minimo, necesitamos que sea el punto minimo para obtener la cantidad de minima de vallas necesarias. Lo haremos con el metodo de la 2nda derivada.
        - $A''=-3$
        - Como directamente obtuvimos un valor negativo es un punto maximo por ende podemos obtener la maxima cantidad de area.
    - 4to Paso;
        - Ahora podemos reemplazar el valor para Obtener el segundo valor en nuestros rectangulos. 
        - $P= 3y + 4x$
        - $120= 3y + 4x$
        - $120= 3(20) + 4x$
        - $x = 15$
    

