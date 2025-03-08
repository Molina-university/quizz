Un número amigo es aquel que tiene exactamente dos divisores distintos diferentes de 1 y él mismo. Por ejemplo, 6 es un número amigo porque sus únicos divisores son 2 y 3. Escribe un programa que:

- Solicite al usuario un rango de números (inicio y fin)
- Encuentre todos los números amigos dentro de ese rango
- Para cada número amigo encontrado, muestre también sus divisores

rt/

Primero buscaria una funcion scanner para pedir los numeros al usuario
suponiendo un rango normal 1-10 usaria una funcion for y determinaria el siguiente criterio

primero: si el numero es primo se descarta porque solo tiene divisor el 1 y el mismo (descarta todos los numeros primos y los numeros impares)
segundo: si el numero es divisible por mas de dos se descarta (quitaria algunos pares y numeros grandes)
tercero: si el numero cumple la condicion de tener dos divisores diferentes de 1 y el mismo tendria que almacenarlo en otra variable para crear una especie de lista

una vez encontrado la manera de hacer que eso funcione milagrosamente, se muestra la lista y despues tendria que mostrar a cada elemento de la lista los numeros que le son divisibles a el (lo cual no tengo ni la menor idea de como xD)
