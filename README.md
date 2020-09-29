# DNA-CGR
Algoritmo para organizar secuencias de ADN, obtener vectores de frecuencia y realizar una imagen CGR (Chaos Game Representation) de la secuencia de ADN.

Éste algoritmo utiliza un vector de frecuencias de una secuencia de ADN para crear una representación del juego de caos. Para crear el vector de frecuencias busca el notebook "vector de frecuencias"
El algoritmo es capaz de crear la imágen utilizando cualquier numero de cifras significativas.
La imágen se forma con el nucleotido A en la esquina superior izquierda, el C en la esquina superior derecha, el G en la esquina inferior izquierda y el nucleotido T en la esquina inferior derecha.
Los tonos en cada cuadro indican la frecuencia de esa subsecuencia de ADN, mientras más obscuro, mayor frecuencia.

Ejemplo:
Tomamos una cadena de ADN de la forma "ACGAGACAGTTATAGCAGATA.....". Ésta cadena la dividimos en subsecuencias de longitud n, luego se cuenta cuantas veces aparece la subsecuencia y finalmente se acomodan en el CGR.
