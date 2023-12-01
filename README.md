# Soluciones de Ecuaciones en Diferencia con Matlab
*por Diego Fernando Camacho Castiblanco*

Las ecuaciones en diferencia son, en su gran mayoría, la representación de comportamientos de sistemas, situaciones y modelos físicos, químicos, sociales, económicos, etc. Donde la variable principal o tasa de cambio es el tiempo, teniendo en cuenta que el comportamiento de esta variable es discreto, tomando valores como t=1,2,3,4,5...

Las ecuaciones en diferencias se expresan de la siguiente manera:
\[ G(n,f(n),f(n+1),\ldots,f(n+k))=0, \forall n \in \mathbb{Z} \]
Donde \( f \) es una función definida en \( \mathbb{Z} \).

Para definir el orden de una ecuación en diferencias, podemos calcular la diferencia entre los valores de \( k \) mayores y menores, como se muestra en las siguientes fórmulas:
\[ \text{Ecuación simplificada de la forma } f(n+k_{\text{mayor}}) \text{ y } f(n+k_{\text{menor}}) \]
Orden = \( k_{\text{mayor}} - k_{\text{menor}} \)

Se define que una ecuación en diferencias es homogénea cuando \( G(n) = 0 \) y es una ecuación en diferencia completa cuando \( G(n) \neq 0 \).

Para abordar y resolver estas ecuaciones, utilizaremos MATLAB, una herramienta poderosa que facilita la manipulación simbólica y numérica, brindando soluciones precisas a problemas complejos. A lo largo de este documento, exploraremos ejemplos concretos que ilustran cómo MATLAB puede ser empleado para resolver y analizar ecuaciones en diferencia, proporcionando una visión práctica y aplicada de este importante concepto matemático.


# Soluci-n-de-Ecuaciones-en-diferencia-en-Matlab
Solucion de Ecuaciones en diferencia en matlab
