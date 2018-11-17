# TAREA_3 

Realice un algoritmo que tenga como objetivo realizar un desayuno, el cual
debe contener café , pan caliente con palta, porción de panqueques rellenos
con manjar y un vaso de jugo de naranja. Las acciones que pueden utilizar
son; preparar, rellenar, servir, moler, calentar, calentar sartén y cortar, las
cuales podrán utilizar más de una vez, salvo “calentar sartén”.


Elementos (huevos; harina ; café; naranjas; pan; palta) ; elementos [pan, palta] pertecen al subconjunto(*1) B="Pan con Palta"
elementos [huevos, harina] pertenecen al subconjunto A="masa para panqueque"

INICIO
Seleccionar un elemento

¿El elemento pertenece al subconjunto A?

Si es no-> seleccionar un elemento distinto al anterior sin repetición

Si es sí-> seleccionar un segundo elemento que permanezca al subconjunto A

¿El elemento pertenece al subconjunto A?

si es no-> seleccionar un elemento distinto al anterior sin repetición

Si es sí-> preparar mezcla de ambos elementos -> nuevo elemento creado="subconjunto A"

Seleccionar un elemento

¿El elemento sirve para hacer panqueque?

Si es no -> seleccionar un elemento distinto al anterior sin repetición

Si es sí -> preparar elemento 

Calentar la sartén

Calentar elemento seleccionado en la sartén

Rellenar elemento (panqueques con manjar)

Servir subconjunto A(*2)

Seleccionar un elemento distinto al anterior 

¿El elemento sirve para hacer jugo de naranja?

Si es no -> seleccionar un nuevo elemento distinto a los anteriores sin repetición

Si es sí ->  cortar elemento 

Preparar elemento seleccionado

Servir elemento (jugo de naranja)

Seleccionar un elemento sin utilizar

¿El elemento se puede calentar y es complementario(*3)?

Si es no -> seleccionar otro elemento sin repetición

Si es sí ->  calentar elemento (pan)

Seleccionar un elemento no procesado anteriormente (quedan 2; café y palta)

¿El elemento sirve para café?

Si es no -> seleccionar un elemento distinto al anterior sin repetición

Si es sí -> preparar elemento (cafe)

Seleccionar el elemento restante (palta)

Cortar elemento seleccionado (palta)

Moler elemento 

Preparar mezcla de elementos complementarios -> nuevo elemento creado="subconjunto B"

Servir elemento líquido y caliente (café)

Servir el subconjunto B

Bon Appetit!

*subconjunto ---> Estos subconjuntos son un elemento creado a partir de la mezcla y/o preparación de  2 elementos específicos.
*servir elemento ---> elemento que ha finalizado su proceso de elaboración. No aparecerá en la lista de selección de elementos en procesos futuros dado que los recursos ya han sido utilizados. Mientras no se complete el proceso de servir, se entiende que está en preparación.
* elemento complementario ---> elementos que forman parte de un subconjunto. 

