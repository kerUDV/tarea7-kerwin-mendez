# Bitácora del Explorador Estelar – TDA Pila

Proyecto del curso **Estructuras de Datos**.

Este programa implementa una estructura de datos tipo **Pila (Stack)** mediante la clase `BitacoraStack`.  
La pila se utiliza para registrar eventos de una nave espacial, donde el **último evento registrado es el primero en consultarse o eliminarse (LIFO)**.

## Funcionalidades

La clase `BitacoraStack` implementa las siguientes operaciones:

- `registrar(String evento)` → agrega un evento a la pila (push)
- `consultarUltimo()` → devuelve el último evento sin eliminarlo (peek)
- `eliminarUltimo()` → elimina y devuelve el último evento (pop)
- `estaVacia()` → indica si la pila está vacía
- `totalEventos()` → devuelve la cantidad de eventos registrados

Si se intenta consultar o eliminar un evento cuando la pila está vacía, el sistema lanza una excepción.

## Compilar el programa

Desde la terminal ejecutar:
PS C:\Users\keruv\IdeaProjects\tarea7-kerwin-mendez> javac src/Main.java
PS C:\Users\keruv\IdeaProjects\tarea7-kerwin-mendez> java -cp src Main
Último evento registrado: ERROR CRÍTICO: fallo en sistema de navegación
Protocolo de revisión activado. Eliminando los últimos 3 eventos:
- ERROR CRÍTICO: fallo en sistema de navegación
- Escudos al 40%
- Anomalía detectada en sector 7
Estado actual de la bitácora:
Total de eventos restantes: 3
Evento actual en la cima: Señal de comunicación estable
PS C:\Users\keruv\IdeaProjects\tarea7-kerwin-mendez> 
