# reto_3_Unico_Y_Genial
Se ha puesto en práctica la habilidad para generar algoritmos sencillos resolviendo los siguiente problemas:
## Pregunta
1.A partir del algoritmo de identificación de los divisores, plantear la serie de pasos para determinar los números primos hasta un natural n.
2.Plantear el algoritmo para obtener los números primos hasta n, usando pseudocódigo y diagramas de flujo.
## Respuesta
### Paso 2
Para cada número i de 0 hasta n, hacer la división entre 2 e i/2.
### Paso 3
Evaluar, según el residuo de la operación, si pertenecen a los primos, o no, según lo siguiente:
### 3.1
Es primo sí: El residuo de todas las operaciones de 2 a i/2 fue distinto a "0".
### 3.2
No es primo sí: El residuo de alguna de las operaciones de 2 a i/2 fue igual a "0".
### 3.3
El "1" y el "0" automaticamente se descarta como no primo.
### 3.4
El "2" automáticamente se tiene como primo.
### 3.5
Guardar los números primos en una lista.
### 4
Imprimir lista de primos.

## Pseudocódigo
```
[variables]
n : entero
i : 2
inicio
  Mientras (i<=n) hacer
    Si modulo(i,2 hasta i/2) != 0 o i es 2 entonces
      guardar i en lista de primos
    sino
      descartar número
    i=i+1
   escribir(lista de primos)
  
fin
```
## Diagrama de flujo
[![](https://mermaid.ink/img/pako:eNpNUstu20AM_BViTwpqo0mOBtyiiRTnVcNAfKqUAyExNlFp19hdpShkfVJPveVSoP6xklJcWBcNyeHwsexM6SoyM_NSux_lFn2EdVpYkO9Lvjy8NeRdgJ3nRn5bDBHBPk-nn-A6WaFH4Pm5uEvyUPErBz78tkA2eoJLIOCPl2ej2DVoUtplr1i36CcQaHN4E24NngJXrYOKoEZwO_JYqs5EhGb9mJ5q-l230j4gcA8nbrjplm5sUUNj5EYjizx7_C9PAc5FEbDetPa0zvNJBtznPDIdXLwH7qYSyPKsPpWqOES20QEKNzA1O09HvgrdJoPOcfxMXOt8IZNX6MG2ulZtpmbdqEw-bnhQuFWugoWAhySlUMqzaNr7cwya9xpU8CBg1f39w3P7udfS-6fDr_1jwo1qsh9rnA0bWytXwUp5S7e_SnjOHy4GxSvxpWZipEaDXMlNdOouTNxSQ4WZCZTuvxemsL3wsI3u6actzSz6libGu3azPRrtrsJIKePGY3N07tB-c07MF6yD2FRxdP7reIDDHfb_AOO71BM?type=png)](https://mermaid.live/edit#pako:eNpNUstu20AM_BViTwpqo0mOBtyiiRTnVcNAfKqUAyExNlFp19hdpShkfVJPveVSoP6xklJcWBcNyeHwsexM6SoyM_NSux_lFn2EdVpYkO9Lvjy8NeRdgJ3nRn5bDBHBPk-nn-A6WaFH4Pm5uEvyUPErBz78tkA2eoJLIOCPl2ej2DVoUtplr1i36CcQaHN4E24NngJXrYOKoEZwO_JYqs5EhGb9mJ5q-l230j4gcA8nbrjplm5sUUNj5EYjizx7_C9PAc5FEbDetPa0zvNJBtznPDIdXLwH7qYSyPKsPpWqOES20QEKNzA1O09HvgrdJoPOcfxMXOt8IZNX6MG2ulZtpmbdqEw-bnhQuFWugoWAhySlUMqzaNr7cwya9xpU8CBg1f39w3P7udfS-6fDr_1jwo1qsh9rnA0bWytXwUp5S7e_SnjOHy4GxSvxpWZipEaDXMlNdOouTNxSQ4WZCZTuvxemsL3wsI3u6actzSz6libGu3azPRrtrsJIKePGY3N07tB-c07MF6yD2FRxdP7reIDDHfb_AOO71BM)

### Fin
