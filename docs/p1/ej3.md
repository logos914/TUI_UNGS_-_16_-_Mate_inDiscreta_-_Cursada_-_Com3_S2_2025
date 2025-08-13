## Ej3
Se construyen señales izando 5 banderas en un mástil ¿Cuántas señales pueden construirse si se dispone de una cantidad ilimitada de banderas en 7 colores distintos? 

¿Qué implicancia tiene en la forma de contar que se disponga de una cantidad ilimitada de banderas de cada color?

¿Si de un determinado color solo hubiesen 5 banderas se podría contar de igual forma? 

Reflecione sobre qué aspecto tendría que tener en cuenta.

---

Tenemos 5 eventos de elección. Al ser la cantidad de banderas ilimitadas. Si elijo el color A, sigue habiendo posibilidad de elegir la misma cantidad de colores, porque son ilimitadas. Entonces puedo elegir de nuevo el color A y los demás colores.

Por lo que los 5 eventos de elección de la bandera, son independientes entre si.

Sea $S$ la solución que contiene todas las posibles señales que pueden construirse. Y por principio multiplicativo.

$$ |S| = |S_1| * |S_2| * |S_3| * |S_4| * |S_5|
$$


$$ |S| = 7 * 7 * 7 * 7 * 7
$$

$$ |S| = 7⁵$$

---
Si hubiesen solamente 5 banderas de color, no podría contar de la misma forma. Los eventos ahora no son independientes. 

Puesto que al elegir un color en la primera bandera (el primer evento), no puedo elegir ese mismo para el segundo.

Por lo tanto, puedo aplicar el principio multiplicativo pero $|S_2|$ ya no es igual que antes, porque ahora tiene una opción menos.

Recordemos que ahora la cantidad de opciones para elegir son 5. Aunque el principio sea el mismo.

$$ |S| = |S_1| * |S_2| * |S_3| * |S_4| * |S_5|
$$


$$ |S| = 5 * 4 * 3 * 2 * 1
$$

$$ |S| = 5!$$