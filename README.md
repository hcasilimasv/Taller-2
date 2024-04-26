# Taller 2

1. Desarrollar un programa que ingrese un número entero n y separe todos los digitos que componen el número. **Pista:** Utilice los operadores módulo (%) y división entera (//).

``` python

```


2. Desarrollar un programa que ingrese un número flotante n y separe su parte entera de la parte decimal, y luego entregue los dígitos tanto de la parte entera como de la decimal.

``` python

```


3. Desarrollar un programa que permita ingresar dos números enteros y determinar si se tratan de números espejos, definiendo números espejos como dos números a y b tales que a se lee de izquierda a derecha igual que se lee b de derecha a izquierda, y viceversa.

``` python

```


4. Diseñar una función que permita calcular una aproximación de la función coseno alrededor de 0 para cualquier valor x (real), utilizando los primeros n términos de la serie de Taylor. **nota:** use *math* para traer la función coseno y mostrar la diferencia entre el valor real y la aproximación. Calcule con cuántos términos de la serie (i.e: cuáles valores de n), se tienen errores del 10%, 1%, 0.1% y 0.001%.
$$cos(x) \approx cos(x,n) \approx \sum_{i=0}^{n} (-1)^i \frac{x^{2i}}{(2i)!}$$

``` python

```


5. Desarrollar un programa que permita determinar el Minimo Comun Multiplo de dos numeros enteros. Abordar el problema desde una perpectiva tanto iterativa como recursiva. **Pista:** Puede ser de utilidad chequear el [Algoritmo de Euclides](https://es.wikipedia.org/wiki/Algoritmo_de_Euclides) para el cálculo del Máximo Común Divisor, y revisar cómo se relaciona este último con el Mínimo Común Múltiplo.

``` python

```


6. Desarrollar un programa que determine si en una lista existen o no elementos repetidos. **Pista:** Maneje valores booleanos y utilice el operador *in*.

``` python

```


7. Desarrollar un programa que determine si en una lista se encuentra una cadena de caracteres con dos o más vocales. Si la cadena existe debe imprimirla y si no existe debe imprimir 'No existe'.

``` python

```


8. Desarrollar un programa que dadas dos listas determine que elementos tiene la primer lista que no tenga la segunda lista. **Ejemplo:**
<center>
<table border="1">
<tr>
<td>
lista1: [1, 'Hola', -12.3 ,True]<br>
lista2: [11, -12.3, 'Hola', False]
</td>
</tr>
<tr>
<td>
salida: [1, True]
</td>
</tr>
</table>
</center>

``` python

```


9. Resolver el punto 7 del [taller 1](https://github.com/fegonzalez7/pdc_unal_clase8) usando operaciones con vectores.

``` python

```


10. Suponga que se tiene una lista A con ciertos números enteros. Desarrolle una función que, independientemente de los números que se encuentran en la lista A, tome aquellos números que son múltiplos de 3 y los guarde en una lista nueva, la cual debe ser **retornada** por la función. Implemente la perspectiva de un *patrón de acumulación* y también de *comprensión de listas*. **Desafío:** Si ya lo logró, inténtelo ahora sin utilizar el módulo (%). **Pista:** Un número es multiplo de 3 si la suma de sus dígitos también lo es, ¿verdad?

``` python

```


### Bono
11. Desarrollar un algoritmo que determine si una matriz es mágica. Se dice que una matriz cuadrada es mágica si la suma de cada una de sus filas, de cada una de sus columnas y de cada diagonal es igual.

``` python

```


