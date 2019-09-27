# Optimizar operaciones de listas en Python

Tenemos una lista (Lista A) que contiene 2 millones de ID de los clientes que reciben un determinado servicio, por otro lado tenemos una lista (Lista B) que contiene 850,000 ID de clientes que han realizado el pago de su servicio del mes de Abril. Se necesita saber cuales son los ID de clientes que aún no han pagado su servicio.

## Solución

La solución parece resultar simple, debemos de saber que IDs de la Lista A no están en la Lista B. Si bien el algoritmo parece tener todo el sentido del mundo, es importante emplear las funciones y herramientas correctas en la codificación.

Vamos a resolver este problema con **3 alternativas distintas** (métodos getDifferent1, getDifferent2 y getDifferent3). El contenido de las listas se generarán de manera aleatoria y de manera secuencial. Finalmente el script mostrará en pantalla los tiempos de ejecución de las 3 alternativas.

## Ejecución

    $> py OperationList.py 2000000 850000 0 
    $> py OperationList.py 500000 2000 1

La cantidad de elementos que deben tener las listas A y B son enviadas como argumentos en la invocación del script. Puedes intentar cambiar estos valores si lo deseas. El tercer argumento es para indicarle al programa que genere los elementos de ambas listas de forma aleatoria o secuencial.

## Resultado

**Ejercicio 1:** No generando aleatoriamente los elementos de las listas A y B.

![](http://www.solocodigoweb.com/wp-content/uploads/2017/05/tiempo-ejecucion-no-aleatorio.jpg)

**Ejercicio 2:** Generando aleatoriamente los elementos de las listas A y B.

![](http://www.solocodigoweb.com/wp-content/uploads/2017/05/tiempo-ejecucion-aleatorio.jpg)

## Referencias

* [Optimizar operaciones de listas con pyhton](http://www.solocodigoweb.com/blog/2017/05/20/optimizar-operaciones-de-listas-en-python/)
