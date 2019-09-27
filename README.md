# Optimizar operaciones de listas en Python

Tenemos una lista (Lista A) que contiene 2 millones de ID de los clientes que reciben un determinado servicio, por otro lado tenemos una lista (Lista B) que contiene 850,000 ID de clientes que han realizado el pago de su servicio del mes de Abril. Se necesita saber cuales son los ID de clientes que aún no han pagado su servicio.

## Solución

La solución parece resultar simple, debemos de saber que IDs de la Lista A no están en la Lista B. Si bien el algoritmo parece tener todo el sentido del mundo, es importante emplear las funciones y herramientas correctas en la codificación.

Vamos a resolver este problema con *3 alternativas distintas* (métodos getDifferent1, getDifferent2 y getDifferent3). El contenido de las listas se generarán de manera aleatoria y de manera secuencial. Finalmente el script mostrará en pantalla los tiempos de ejecución de las 3 alternativas.
