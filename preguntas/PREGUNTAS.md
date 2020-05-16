## Training Python I

Este es un entrenamiento basado en principios fundamentales de python, pero también un repaso de otras tecnologñías conocidas. 

Algunas consideraciones: 
 
- Las solución de cada consigna, deben ser en Python y también en Javascript. Excepto cuando se indique lo contrario. 
- Verán que hay casos que deben explicar, otros que deben aplicar algoritmos y otros donde a partir de la solución, deberán explicar que hace tal o cual cosa. 
- Cuando les pido "escriba una función..." no deben hacer más que eso. Es un error pretender mostrarme como "funciona".
- Cuando me ofrecen sus resultados, háganlo de tal manera que yo debería poder tomar la sola porción de código de la solución de un tópico y al ejecutarla, obtener el resultado o solución. 

#### A la práctica:(recuerden en Python y en Javascript)

##### 1. Complete en un script que muestre como resultado los elementos f, g y h. Explique la solución.

    `lettters = ["a", "b", "c", "d", "e", "f", "g", "h", "i", "j"]`
----

##### 2. Tomando dos valores del usuario, calculamos la multiplicación
---

##### 3. Mostrar la salida de una la lista de 5 números flotantes ingresados por el usuario.
---

##### 4. Como puedo saber si el archivo permisos.txt, está vació o no ?
---

##### 5. Como puedo leer la línea 4 del archivo test.txt cuyo contendio es el que sigue:

<pre>
línea 1
línea 2
línea 3
línea 4
línea 5
línea 6
</pre>
---

##### 6. Partiendo de la lista a continuación, mostrá solamente los números divisibles por 5. La iteración se debe detner cuando encuentre un número mayor a 150

    `list1 = [12, 15, 32, 42, 55, 75, 122, 132, 150, 180, 200]`
----

##### 7. Quiero que imprimas el siguiente patrón. Fundamenta la solución.
<pre>
5 4 3 2 1 
4 3 2 1 
3 2 1 
2 1 
1
</pre>
---

##### 8. (Solo en Python) Si ejecuto el siguiente script, pienso que tendré un error. Cómo puedo lograr evitarlo y que muestre un mensaje "Listo!" ?

```python
for i in range(5):
    print(i)
```
y quiero obtener esto: 
<pre>
0
1
2
3
4
Listo!
</pre>
---

##### 9. (Solo en Python) Partiendo de la siguiente función `dataEstudiante(nombre, edad)`, como podría llamarla usando esta función pero reutilizándola y asignándole un nuevo nombre como `mostrarEstudiante(nombre, edad)`
```python
def dataEstudiante(nombre, edad):
    print(nombre, edad)
dataEstudiante("Victor", 36)
```
----

##### 10. (Solo en Python) Explicar que hace esta función y por qué ?
```python
def dataEmpleado(nombre, salario=29000):
    print("Empleado", nombre, "El sueldo es:", salario)
```
Ejemplos posibles de resultado de la llamada a la función

<pre>
dataEmpleado("Juan", 29000)
dataEmpleado("Juan")
</pre>

---
##### 11. Partiendo de dos strings: `str1` y `str2`, necesito una función que cree una nueva y única cadena formada por el primero, el medio y el último carácter de `str1` y `str2`

Ejemplo: 
<pre>
mixStr(“Argentina”, “Uruguay”) = AUngay
</pre>
----

##### 12. Necesito saber que un script me pueda informar cuantas ocurrencias se dan por cada letra en el siguiente string “acoltrapersobrabilacodaNaNy!
----

##### 13. Un vecino de Cañuelas cría gallínas, vacas y cerdos. Necesitamos saber cuantas patas hay en total entre todas las especies. Ahora resulta que un programador anterior, le envió un e-mail al granjero con el siguiente array y el mensaje, "perdón, pero no puedo seguir"

<pre>
animales(12,23,11) = 12*2 23*4 11*4
</pre>























