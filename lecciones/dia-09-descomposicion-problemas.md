# Día 9 – Descomposición de problemas

## 1. ¿Qué significa descomponer un problema?

La descomposición de problemas consiste en dividir un proyecto grande en tareas pequeñas para poder entenderlo, organizarlo y resolverlo paso a paso.

Por ejemplo, si queremos desarrollar un videojuego parecido a GTA, podemos dividirlo en diferentes sistemas:

- Jugador.
- Dinero.
- Misiones.
- Inventario.
- Guardado del progreso.

En lugar de intentar desarrollar todo al mismo tiempo, trabajamos en cada parte por separado.

## 2. ¿Cómo puede ayudarnos la IA?

Podemos pedirle a una IA que divida un proyecto en tareas pequeñas, explique cada una y proponga un orden lógico para desarrollarlas.

Ejemplo de prompt:

```text
Actúa como un desarrollador senior de JavaScript.

Quiero crear un videojuego sencillo.

Antes de escribir código, divide el proyecto
en tareas pequeñas.

Para cada tarea:
- Explica qué debemos construir.
- Indica qué necesitamos aprender.
- Propón un orden de desarrollo.
- No avances a la siguiente tarea
  hasta que haya terminado la anterior.

Adapta las explicaciones a un estudiante junior.
```

Esto permite utilizar la IA como una herramienta de planificación y aprendizaje, en lugar de pedirle que haga todo el trabajo de una vez.

## 3. Ejemplo práctico en JavaScript

Queremos crear una función para calcular el promedio de las puntuaciones de un jugador.

```js
function calcularPromedioPartidas(puntuaciones) {
  // Aquí calcularemos el promedio
}
```

Antes de escribir la solución, podemos dividir el problema en cinco pasos:

1. Recibir las puntuaciones mediante un array.
2. Comprobar si el array está vacío.
3. Sumar todas las puntuaciones.
4. Dividir el total entre la cantidad de partidas.
5. Devolver el resultado.

Esto nos permite entender qué necesitamos hacer antes de programar.

## 4. Preguntas para resolver problemas

Cuando tenemos un problema de programación, podemos hacernos cuatro preguntas:

1. ¿Qué quiero construir?
2. ¿Qué partes forman ese problema?
3. ¿En qué orden debo resolverlas?
4. ¿Cómo puedo comprobar que cada parte funciona?

La IA puede ayudarnos a responder estas preguntas, pero debemos revisar y comprobar sus propuestas.

## 5. Ejercicios realizados

- [x] Identificar por qué es mejor dividir un proyecto en tareas pequeñas.
- [x] Elegir un prompt adecuado para planificar un proyecto.
- [x] Identificar el orden correcto para desarrollar una funcionalidad.
- [x] Reconocer la importancia de revisar los planes generados por IA.
- [x] Crear una planificación propia para un sistema de monedas.

## 6. Ejercicio práctico: sistema de monedas

Imaginé que estaba desarrollando un videojuego sencillo en JavaScript con un sistema de monedas.

El jugador debe poder:

- Consultar cuántas monedas tiene.
- Ganar monedas al completar misiones.
- Sumar las recompensas al saldo existente.
- Comprar objetos y consultar sus precios.
- Descontar las monedas después de cada compra.
- Evitar que el saldo sea negativo.
- Recibir un mensaje indicando cuántas monedas le faltan cuando no puede comprar algo.
- Ver misiones recomendadas para conseguir las monedas necesarias.

### Planificación del sistema

Dividí el proyecto en seis tareas:

1. Crear el saldo inicial del jugador.
2. Crear una función para consultar las monedas.
3. Crear una función para ganar monedas.
4. Crear una función para comprar objetos.
5. Validar las compras para evitar saldos negativos.
6. Mostrar misiones recomendadas cuando falten monedas.

### Ejemplo de pruebas esperadas

| Acción | Operación | Saldo esperado |
|---|---:|---:|
| Inicio | 500 | 500 |
| Completar misión | +200 | 700 |
| Comprar espada | -300 | 400 |
| Intentar comprar armadura de 600 | Compra rechazada | 400 |

Si el jugador tiene 400 monedas y la armadura cuesta 600, la compra debe rechazarse y el juego debe informar que faltan 200 monedas.

Estas son pruebas planificadas con resultados esperados. Todavía no se ha implementado ni ejecutado el sistema.

## 7. Conclusión

Aprendí que antes de programar es importante comprender el problema, dividirlo en tareas pequeñas y organizarlas en un orden lógico.

También aprendí que puedo utilizar la IA para planificar proyectos, revisar las tareas y detectar elementos que podrían faltar.

**Lo más importante:** no debemos intentar resolver un proyecto completo de una sola vez. Es mejor avanzar paso a paso, comprobar cada parte y entender cómo funciona.