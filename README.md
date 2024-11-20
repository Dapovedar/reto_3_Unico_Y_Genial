# reto_3_Unico_Y_Genial
Se ha puesto en práctica la habilidad para generar algoritmos.
## Pregunta
A partir del algoritmo de identificación de los divisores, plantear la serie de pasos para determinar los números primos hasta un natural n.
## Respuesta
### Paso 1
Crear una lista de números naturales desde el 2 hasta n.
### Paso 2
Para cada número i de la lista, hacer la división entre 2 e i/2.
### Paso 3
Evaluar, según el residuo de la operación, si pertenecen a los primos, o no, según lo siguiente:
### 3.1
Es primo sí: El residuo de todas las operaciones de 2 a i/2 fue distinto a "0".
### 3.2
No es primo sí: El residuo de alguna de las operaciones de 2 a i/2 fue igual a "0".
### 3.3
El "1" automaticamente se descarta como no primo.
### 3.4
El "2" automáticamente se descarta como primo.
### Fin
