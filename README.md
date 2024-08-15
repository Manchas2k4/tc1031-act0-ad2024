# Suma exacta
Peter recibió dinero de sus padres esta semana y quiere gastarlo todo en comprar libros. Pero no lee un libro tan rápido, porque le gusta disfrutar de cada palabra mientras lee. De esta manera, le toma una semana terminar un libro.

Como Peter recibe dinero cada dos semanas, decidió comprar dos libros, luego podrá leerlos hasta recibir más dinero. Como desea gastar todo el dinero, debe elegir dos libros cuyos precios sumados sean iguales al dinero que tiene. Es un poco difícil encontrar estos libros, por lo que Peter le pide ayuda para encontrarlos.

## Entrada
Cada caso de prueba comienza con 2 ≤ N ≤ 10000, la cantidad de libros disponibles. La siguiente línea tendrá N números enteros, que representan el precio de cada libro, un libro cuesta menos de 1000001. Luego hay otra línea con un número entero M, que representa cuánto dinero tiene Peter. Hay una línea en blanco después de cada caso de prueba. La entrada termina con el final del archivo (EOF).

## Salida
Para cada caso de prueba, debe imprimir el mensaje: ```Peter should buy books whose prices are i and j.```, donde i y j son los precios de los libros cuya suma es igual a M e i ≤ j. Puede considerar que siempre es posible encontrar una solución, si hay múltiples soluciones imprima la solución que minimice la diferencia entre los precios i y j. Después de cada caso de prueba, debe imprimir una línea en blanco.

## Entrada de muestra
```
2
40 40 
80

5 
10 2 6 8 4
10
```

## Salida de muestra
```
Peter should buy books whose prices are 40 and 40.

Peter should buy books whose prices are 4 and 6.

```