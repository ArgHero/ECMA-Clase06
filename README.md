# Proyecto: Recursión y Backtracking
>Saul Omar Arguello Hernandez

## Descripción
La **recursión** y el **backtracking** son herramientas fundamentales para resolver problemas complejos dividiéndolos en partes más pequeñas. Este proyecto se centra en la aplicación de recursión para **buscar un regalo específico** dentro de una lista de regalos, proporcionando una práctica clave en la programación.

## Objetivo
Desarrollar una función recursiva que:
1. Busque un objeto específico en un arreglo de regalos.
2. Devuelva un mensaje indicando la posición del regalo si se encuentra.
3. Devuelva un mensaje indicando que el regalo no está en la lista si no se encuentra.

## Problema: Buscar un objeto en una lista de regalos
Es Navidad, y necesitas identificar un regalo en una lista proporcionada por tu familia. El propósito de este ejercicio es resolver el problema utilizando **recursión**, lo que te ayudará a practicar la división de tareas en problemas más pequeños y a implementar un caso base.

## Instrucciones
1. Escribe una función recursiva que busque un regalo específico en un arreglo.
2. Implementa los casos base:
   - Si el índice actual (`index`) alcanza la longitud del arreglo (`gifts.length`), el regalo no está en la lista.
   - Si el elemento actual (`gifts[index]`)

## Funcionalidades

Esta solución implementa una búsqueda recursiva para encontrar un objeto específico en un arreglo de regalos. Las funcionalidades incluidas son las siguientes:

1. **Búsqueda Recursiva de Regalos**:
   - La función `findGift` utiliza un enfoque recursivo para buscar un regalo en la lista proporcionada.
   - Si el regalo se encuentra, devuelve su posición en la lista.
   - Si el regalo no está en la lista, devuelve un mensaje indicando que no se encontró.

2. **Casos Base**:
   - La búsqueda finaliza si el índice actual supera la longitud del arreglo (`index >= gifts.length`).
   - Si el regalo buscado coincide con el elemento actual (`gifts[index] === giftName`), se devuelve la posición del regalo.

3. **Flexibilidad**:
   - Permite realizar pruebas con diferentes listas de regalos y nombres de regalo utilizando datos de entrada dinámicos.
   - Es capaz de manejar listas de regalos de cualquier longitud.

4. **Mensajes Informativos**:
   - Proporciona mensajes claros que indican si el regalo se encuentra en la lista o si no está presente.

5. **Optimización**:
   - Implementación simple y eficiente que divide el problema en partes más pequeñas para resolverlo de manera progresiva.

### Ejemplo de Uso
**Entrada**:
```javascript
const gifts = ["Muñeca", "Carro de juguete", "Rompecabezas", "Lego", "Pelota"];
const giftToFind = "Lego";
console.log(findGift(gifts, giftToFind));
```
