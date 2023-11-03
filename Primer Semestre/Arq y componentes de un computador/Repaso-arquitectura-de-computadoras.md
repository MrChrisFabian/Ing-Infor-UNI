
## Preguntas sobre los procesadores y el funcionamiento de las computadoras
1. ¿Qué es una CPU y cuál es su función principal en una computadora?
   - Una CPU (Unidad Central de Procesamiento) es el componente principal de una computadora responsable de ejecutar instrucciones y realizar cálculos. Funciona como el cerebro de la computadora y procesa datos y programas.

2. ¿Explica brevemente la diferencia entre la Unidad de Control y la Unidad Aritmético-Lógica en una CPU?
   - La Unidad de Control (UC) es responsable de coordinar y controlar las operaciones en la CPU, mientras que la Unidad Aritmético-Lógica (UAL) realiza operaciones matemáticas y lógicas, como sumas, restas y comparaciones. La UC se encarga de buscar, decodificar y ejecutar las instrucciones, mientras que la UAL realiza los cálculos y operaciones necesarios.

3. ¿Cuáles son los componentes básicos de una CPU y cómo trabajan juntos para ejecutar instrucciones?
   - Los componentes básicos de una CPU son la Unidad de Control (UC), la Unidad Aritmético-Lógica (UAL) y los registros. La UC coordina las operaciones, la UAL realiza cálculos y los registros almacenan datos temporales y resultados. Estos componentes trabajan juntos al buscar, decodificar y ejecutar instrucciones almacenadas en la memoria.

4. ¿Qué es una arquitectura de CPU y cómo puede influir en el rendimiento de una computadora?
   - La arquitectura de la CPU se refiere al diseño y la organización interna de la CPU. Puede influir en el rendimiento de una computadora, ya que determina cómo se ejecutan las instrucciones y se gestionan los recursos. Diferentes arquitecturas pueden tener impactos significativos en la velocidad de procesamiento y la eficiencia energética.
   - Existen arquitecturas:
	   - RISC: con conjuntos de instrucciones reducidos arquitecturas
	   - CISC: con conjuntos más complejos.
- Cada tipo tiene sus propias implicaciones en cuanto a velocidad y complejidad. También pueden manejar direcciones de memoria de diferente longitud

5. ¿En qué se diferencian las arquitecturas RISC y CISC en cuanto a sus conjuntos de instrucciones?
   - Las arquitecturas RISC (Reduced Instruction Set Computer) utilizan un conjunto de instrucciones más simple y generalmente ejecutan instrucciones en un solo ciclo de reloj, mientras que las arquitecturas CISC (Complex Instruction Set Computer) tienen un conjunto de instrucciones más complejo con múltiples ciclos de reloj por instrucción. RISC tiende a ser más eficiente en términos de velocidad, mientras que CISC puede ser más versátil.

6. ¿Explica qué son los bits en el contexto de la informática y cómo se relacionan con las arquitecturas de CPU?
   - Los bits son la unidad más pequeña de información en informática, representando valores binarios 0 o 1. En las arquitecturas de CPU, los bits se utilizan para determinar el tamaño de los registros y la capacidad de direccionamiento. Las arquitecturas de 32 bits usan registros y direcciones de 32 bits, mientras que las de 64 bits utilizan 64 bits.
   
   >_Nota: En el sistema binario, cada bit puede tener dos posibles valores: 0 o 1. Para calcular cuántos números diferentes puedes representar con una cierta cantidad de bits, puedes usar la fórmula 2^n, donde "n" es el número de bits. Entonces, con 32 bits, puedes representar 2^32 números diferentes. Con 64 bits, puedes representar 2^64 números diferentes.
   
1. ¿Cuál es la principal diferencia entre una CPU de 32 bits y una de 64 bits en términos de capacidad de memoria?
   - La principal diferencia entre una CPU de 32 bits y una de 64 bits es su capacidad de dirección. Una CPU de 32 bits puede direccionar un máximo de 4 GB de memoria, mientras que una de 64 bits puede direccionar una cantidad mucho mayor, teóricamente hasta 18.4 millones de TB (terabytes) de memoria.

2. Enumera al menos dos ventajas de utilizar una arquitectura de 64 bits en comparación con una de 32 bits
   - Las ventajas de una arquitectura de 64 bits incluyen una mayor capacidad de memoria, lo que permite manejar aplicaciones y datos más grandes. También permite un mejor rendimiento en tareas que requieren operaciones de números grandes pudiendo manejar calculos más grandes.

3. ¿Qué tipo de aplicaciones o tareas pueden beneficiarse más de una arquitectura de 64 bits?
   - Las aplicaciones que se benefician más de una arquitectura de 64 bits son aquellas que manejan grandes conjuntos de datos, realizan cálculos intensivos o requieren acceso a una cantidad significativa de memoria. Esto incluye software de diseño gráfico, edición de video, simulaciones científicas y bases de datos de gran escala.

4. ¿Por qué es importante que el sistema operativo y las aplicaciones sean compatibles con la arquitectura de la CPU?
    - Es importante que el sistema operativo y las aplicaciones sean compatibles con la arquitectura de la CPU para garantizar un rendimiento óptimo. Si no son compatibles, es posible que no funcionen o que funcionen de manera ineficiente en una CPU específica. La compatibilidad garantiza que el software pueda aprovechar todas las capacidades de la CPU y acceder a la memoria disponible.

**Memoria Principal**
	La memoria principal se puede ver funcionalmente como un módulo que:
- Recibe una dirección y una orden de lectura / escritura y almacena / entrega la información en/de una celda.
- Puede considerarse como un conjunto de celdas (o palabras), cada una con la posibilidad de almacenar una información: dato o instrucción.
- Las celdas están numeradas y la unidad de control conoce cada celda por su número, llamado dirección.

## Representación de la información en computadoras
#### Nociones básicas sobre representación de la información:
- Datos y patrones de bits.
- Detección automática de errores.
- Concepto de comprensión de datos.
- Formas/tipos de información

**Datos** son conjuntos de simbolos utilizados para expresar o representar un valor bumérico, un hecho, un objeto o una idea; en la forma adecuada para ser objeto de tratamiento
**Patrón de bits**
- El código que representa un carácter
- L aplitud de una muestra de señal de audio (voz, música, etc)
- La información de un punto de una imagen (pixel), intrucciones, etc


**Normalizacion IEEE754 para representación de numeros reales**


## Memorias
Los tipos de memoria en una computadora son fundamentales para su funcionamiento y rendimiento. Aquí tienes un resumen de los principales tipos de memoria:

1. **Memoria Caché:**
   - Velocidad: Muy alta.
   - Capacidad: Pequeña (KB o MB).
   - Función: Almacena datos e instrucciones frecuentemente utilizados para acelerar el acceso a ellos.

2. **Memoria RAM (Random Access Memory):**
   - Velocidad: Alta (más lenta que la caché).
   - Capacidad: Moderada (GB).
   - Función: Almacena datos y programas en uso, proporcionando espacio de trabajo para la CPU.

3. **Memoria ROM (Read-Only Memory):**
   - Almacena firmware o software permanentemente grabado, como BIOS o firmware de arranque.

4. **Memoria de Almacenamiento en Disco:**
   - Velocidad: Media (más lenta que la RAM).
   - Capacidad: Alta (TB o más).
   - Función: Almacena datos y programas a largo plazo (HDD más lento, SSD más rápido).

5. **Memoria Virtual:**
   - Velocidad: Lenta (más lenta que la RAM y el almacenamiento).
   - Capacidad: Depende del espacio disponible en el disco duro o SSD.
   - Función: Extiende la RAM al usar espacio en disco cuando la RAM se llena.

6. **Memoria de Video (VRAM):**
   - Velocidad: Alta (específica para gráficos).
   - Capacidad: Moderada a alta (depende de la tarjeta de video).
   - Función: Almacena datos e imágenes para la salida de video, acelerando la renderización de gráficos y videos.

7. **Memoria de Dispositivos Externos:**
   - Velocidad: Varía según el dispositivo.
   - Capacidad: Varía según el dispositivo.
   - Función: Almacena datos y programas portátiles que se pueden conectar a la computadora.


### Memoria Caché

- **Memoria Caché de Nivel 1 (L1):**
    
    - Función: La caché L1 es la más pequeña y rápida de todas las cachés. Almacena datos e instrucciones de uso frecuente para proporcionar acceso rápido a la CPU.
    - Ubicación: Normalmente, la caché L1 se encuentra dentro de la CPU.
- **Memoria Caché de Nivel 2 (L2):**
    
    - Función: La caché L2 es más grande que la caché L1 y proporciona una capa adicional de almacenamiento en caché. Su función es respaldar la caché L1 y proporcionar más espacio para datos e instrucciones de uso común.
    - Ubicación: Puede estar dentro de la CPU o ubicada cerca de ella en el mismo chip, pero es más lenta que la caché L1.
- **Memoria Caché de Nivel 3 (L3):**
    
    - Función: La caché L3 es la más grande y la más lenta de todas las cachés de nivel. Proporciona una reserva aún más grande para datos e instrucciones de uso común y se utiliza para respaldar las cachés L1 y L2.
    - Ubicación: Generalmente, se encuentra fuera de la CPU.

1. **¿Qué es la Memoria Caché?**
   
   La memoria caché es una memoria de alta velocidad y capacidad limitada que se encuentra entre la CPU y la memoria principal de una computadora. Su función principal es almacenar temporalmente datos e instrucciones que la CPU necesita con frecuencia para acelerar el acceso a ellos, reduciendo así los tiempos de espera y mejorando el rendimiento del sistema.

2. **¿Qué es un acierto de caché?**
   
   Un acierto de caché (cache hit) ocurre cuando la CPU busca un dato o instrucción en la memoria caché y lo encuentra allí, evitando así la necesidad de acceder a la memoria principal. Esto resulta en una ejecución más rápida de las operaciones.

3. **¿Qué es la coherencia de cache?**
   
   La coherencia de caché es la propiedad que garantiza que todas las copias de un dato en diferentes niveles de la jerarquía de memoria caché sean consistentes y reflejen el valor más reciente. Esto se logra mediante protocolos de coherencia de caché para evitar problemas como lecturas o escrituras incorrectas debido a copias desactualizadas en cachés diferentes.

4. **¿Qué es la política de escritura inmediata?**
   
   La política de escritura inmediata (write-through) implica que cada escritura realizada por la CPU se copia tanto en la memoria caché como en la memoria principal de manera simultánea. Esto garantiza la coherencia de los datos entre la caché y la memoria principal, pero puede generar más tráfico de escritura y ralentizar las operaciones.

5. **¿Por qué se dice que la política de escritura inmediata reduce el índice de aciertos de caché?**
   
   La política de escritura inmediata reduce el índice de aciertos de caché porque cada escritura requiere que los datos se actualicen tanto en la caché como en la memoria principal. Esto significa que, en comparación con la escritura retardada (write-back), hay más operaciones de escritura que pueden llenar la caché con datos que luego se sobrescriben, reduciendo así la efectividad de la caché.

6. **¿Por qué la solución de dejar a la propia caché actualizar el dato en memoria no es del todo buena?**
   
   Dejar que la caché actualice los datos en memoria (escritura diferida o write-back) puede generar problemas de coherencia si varios núcleos de CPU acceden a la misma ubicación de memoria y mantienen copias desactualizadas. Se requieren protocolos de coherencia de caché complejos para manejar esta situación, lo que aumenta la complejidad del sistema.

7. **¿Qué es un fallo de cache?**
   
   Un fallo de caché (cache miss) ocurre cuando la CPU busca un dato o instrucción en la memoria caché pero no lo encuentra, lo que obliga a acceder a la memoria principal para obtenerlo. Esto resulta en una penalización de tiempo en el rendimiento.

8. **¿Qué es la política de escritura retardada?**
   
   La política de escritura retardada (write-back) permite a la caché retener los cambios realizados en los datos hasta que sea necesario reemplazarlos. Solo se actualiza la memoria principal cuando se elimina un bloque de caché o cuando se necesita espacio para nuevos datos.

9. **¿Cómo podemos mejorar el rendimiento de los retrasos en la caché cada vez que hay que reemplazar un bloque que está modificado usando escritura retardada?**
   
   Para mejorar el rendimiento en tales situaciones, se pueden utilizar estrategias como el uso de políticas de reemplazo de caché eficientes (por ejemplo, LRU - Least Recently Used) y la implementación de algoritmos de escritura que minimicen la necesidad de escribir datos de vuelta a la memoria principal de manera frecuente.

10. **Diferencia entre UMA y NUMA**
   
    - **UMA (Arquitectura de Memoria Uniforme - Uniform Memory Architecture):** En una arquitectura UMA, todas las CPUs tienen acceso a la misma memoria principal con tiempos de acceso similares. No hay distinción entre memoria local y remota. Esto simplifica la programación, pero puede limitar el rendimiento en sistemas con múltiples CPUs debido a la congestión de acceso a la memoria.

    - **NUMA (Arquitectura de Memoria No Uniforme - Non Uniform Memory Architecture):** En una arquitectura NUMA, las CPUs se agrupan en nodos, y cada nodo tiene su propia memoria local. Las CPUs pueden acceder a su memoria local más rápido que a la memoria de otros nodos, lo que puede resultar en un mejor rendimiento en sistemas con múltiples CPUs. Sin embargo, la programación NUMA puede ser más compleja debido a la necesidad de administrar la ubicación de los datos en la memoria.