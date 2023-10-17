# VC_P3

Tarea 1: Para esta tarea hemos realizado distintas fotografías de monedas con algún objeto que no lo sea. Una vez obtuvimos dichas fotografías analizamos el histograma de estas para obtener un valor umbral adecuado de cara a separar los objetos del fondo de la imagen. Una vez separados los objetos, utilizamos la "Transformada de Hough" para detectar las monedas y de esta forma poder calcular cuántas monedas hay en cada imagen.

<img href="https://github.com/ivanom2002/VC_P3/blob/main/ResultadoTarea1.png"/>

Tarea 2: Reutilizando el código de la tarea anterior que detectaba las monedas y usando unas proporciones basadas en las medidas en milímetros de las monedas hemos podido contar de forma aproximada el valor del dinero presente en la imagen. Como problemas hemos encontrado que los radios obtenidos para las monedas a través de la "Transformada de Hough" no son exactos y hay pequeños errores por lo que debemos tener una cierta tolerancia a la hora de comprobar si se cumplen las proporciones. Por otro lado, hemos detectado que al solapar monedas se confunden unas con otras, esto último puede deberse a que al no estar planas en la imagen el error a la hora de calcular el radio de la moneda sea aún mayor. 

<img href="https://github.com/ivanom2002/VC_P3/blob/main/ResultadoTarea2.1.png"/>
<img href="https://github.com/ivanom2002/VC_P3/blob/main/ResultadoTarea2.2.png"/>
<img href="https://github.com/ivanom2002/VC_P3/blob/main/ResultadoTarea2.3.png"/>
<img href="https://github.com/ivanom2002/VC_P3/blob/main/ResultadoTarea2.4.png"/>

Tarea 3: Para esta tarea hemos analizado las imágenes TAR.png, PEL.png y FRA.png. En cada una de ellas hemos separado lo que es el microplástico del fondo de la imagen usando umbralizado. Una vez hecho esto hemos obtenido diferentes datos usando los contornos entre ellos, el área mínima, máxima y media, los perímetros, las elípses ajustadas al contorno, e incluso los colores medios de los microplásticos. A simple vista, ya podíamos observar que los microplásticos de tipo TAR eran de media mucho más oscuros que los otros y que los microplásticos de tipo Pellet tienen una forma más redondeada. Finalmente, nos hemos valido de los datos obtenidos y de estas intuiciones a simple vista para crear una función que sea capaz de clasificar los distintos tipos de microplásticos. 

<img href="https://github.com/ivanom2002/VC_P3/blob/main/ResultadoTarea3.png"/>
