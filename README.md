# TAREA_3 

Realice un algoritmo que tenga como objetivo realizar un desayuno, el cual
debe contener café , pan caliente con palta, porción de panqueques rellenos
con manjar y un vaso de jugo de naranja. Las acciones que pueden utilizar
son; preparar, rellenar, servir, moler, calentar, calentar sartén y cortar, las
cuales podrán utilizar más de una vez, salvo “calentar sartén”.


Elementos (masa de panqueque; cafe; naranjas; pan; palta) ; elementos [pan, palta] pertecen al subconjunto "Pan con Palta"

INICIO

Seleccionar un elemento

¿El elemento sirve para hacer panqueque?

si es no -> seleccionar un elemento distinto al anterior sin repetición

si es sí -> preparar elemento (masa)

Calentar la sarten

Calentar elemento seleccionado en la sartén

Rellenar elemento (panqueques con manjar)

Servir elemento(*1)

Seleccionar un elemento distinto al anterior sin repetición

¿El elemento sirve para hacer jugo de naranja?

si es no -> seleccionar un nuevo elemento distinto a los anteriores sin repetición

si es sí ->  cortar elemento 

Preparar elemento seleccionado

Servir elemento (jugo de naranja)

Seleccionar un elemento sin utilizar

¿El elemento se puede calentar y es complementario(*2)?

si es no -> seleccionar otro elemento sin repetición

si es sí ->  calentar elemento (pan)

Seleccionar un elemento no procesado anteriormente (quedan 2; cafe y palta)

¿el elemento sirve para café?

si es no -> seleccionar un elemento distinto al anterior sin repetición

si es sí -> preparar elemento (cafe)

Seleccionar el elemento restante (palta)

Cortar elemento seleccionado (palta)

Moler elemento 

Preparar mezcla de elementos complementarios 

Servir elemento líquido y caliente (café)

Servir el subconjunto de elementos complementarios (pan con palta)

Bon Appetit!

* servir elemento ---> elemento que ha finalizado su proceso de elaboración. No aparecerá en la lista de selección de elementos en procesos futuros dado que los recursos ya han sido utilizados. Mientras no se complete el proceso de servir, se entiende que está en preparación.
* elemento complementario ---> elementos que forman parte de un subconjunto. En este caso el pan y la palta pertenecen al subconjunto "pan con palta".
