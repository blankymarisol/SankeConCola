# 🐍 Juego de Snake con Estructura de Datos de Cola 🎮

Este proyecto contiene dos ramas principales:

- **`master`**: Contiene el código base proporcionado, sin adaptaciones.
- **`Cola`**: Contiene el código adaptado para utilizar una estructura de datos de tipo **cola**.

## 🔧 Cambios Realizados para Adaptar el Código a una Cola

Para adaptar el código a una estructura de datos de tipo cola, se realizaron los siguientes cambios:

- **Encolar**: Cuando la serpiente se mueve, se añade una nueva cabeza al principio del array de la cola utilizando `unshift`. 🚀
  
- **Desencolar**: Cuando la serpiente no come la comida, se elimina el último elemento del array utilizando `pop`. 🗑️

### 💡 Dato Importante
La serpiente sigue siendo un array, pero ahora se maneja explícitamente como una **cola**, donde:
- **La cabeza** es el primer elemento.
- **La cola** es el último elemento.

Además, el juego verifica si la nueva cabeza choca con los bordes del canvas o con cualquier parte del cuerpo de la serpiente. Esto determina si el jugador ha ganado o perdido el juego. 🎯

## 🤔 ¿Por qué es una Buena Idea Utilizar una Cola?

En el juego de Snake, la serpiente crece y se mueve en una dirección específica. La cola de la serpiente debe seguir a la cabeza, y cuando la serpiente come, la cola crece. Esto se modela perfectamente con una cola, donde:

- **Encolar**: Añade una nueva cabeza cuando la serpiente se mueve. ➕
- **Desencolar**: Elimina la cola cuando la serpiente no come. ➖

Este enfoque es **eficiente** y **fácil de entender**, lo que hace que la cola sea una estructura de datos ideal para este tipo de problema. 🎯

---

¡Espero que disfrutes explorando el código y jugando al Snake! 🕹️
