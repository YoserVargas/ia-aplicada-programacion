# Día 8 – Prompts para obtener respuestas en formatos estructurados (JSON)

## 1. ¿Qué es JSON?

JSON significa JavaScript Object Notation.

Es un formato utilizado para organizar e intercambiar información mediante propiedades y valores.

Podemos imaginarlo como una caja organizada en compartimentos. Cada compartimento tiene una etiqueta que indica qué información contiene.

Ejemplo:

```json
{
  "nombre": "Carlos",
  "nivel": 15,
  "puntuacion": 2500,
  "activo": true
}
```

## 2. JSON vs. texto normal

Una respuesta en texto normal puede ser fácil de entender para una persona, pero puede resultar más difícil para un programa extraer los datos.

En cambio, JSON organiza la información mediante propiedades y valores, facilitando su utilización desde JavaScript.

Ejemplo:

```json
{
  "nombre": "Carlos",
  "nivel": 10,
  "puntuacion": 500
}
```

Desde JavaScript podemos acceder a los datos:

```js
jugador.nombre;
jugador.nivel;
jugador.puntuacion;
```

## 3. Tipos de datos en JSON

| Tipo | Ejemplo | Descripción |
|---|---|---|
| String | `"Carlos"` | Texto |
| Number | `25` | Número |
| Boolean | `true` | Verdadero o falso |
| Array | `[100, 200]` | Lista de valores |
| Object | `{"nivel": 5}` | Grupo de propiedades |
| Null | `null` | Ausencia de valor |

Ejemplo:

```json
{
  "nombre": "Carlos",
  "nivel": 15,
  "puntuaciones": [100, 200, 300],
  "activo": true,
  "equipo": null
}
```

## 4. ¿Cómo solicitar JSON a una IA?

Podemos crear un prompt que indique exactamente cómo queremos recibir la información.

Ejemplo:

```text
Actúa como un asistente para videojuegos.

Genera información de un jugador ficticio.

Devuelve la respuesta exclusivamente en formato JSON.

La estructura debe incluir:
- nombre: texto.
- nivel: número.
- puntuacion: número.
- activo: verdadero o falso.

No agregues explicaciones fuera del JSON.
```

La IA podría responder:

```json
{
  "nombre": "Carlos",
  "nivel": 15,
  "puntuacion": 2500,
  "activo": true
}
```

## 5. Errores comunes en JSON

Es importante respetar la sintaxis.

Ejemplo incorrecto:

```json
{
  "nombre": "Carlos",
  "nivel": 10,
  "puntuacion": 500,
}
```

El error es la coma adicional después del último valor.

Versión correcta:

```json
{
  "nombre": "Carlos",
  "nivel": 10,
  "puntuacion": 500
}
```

Las propiedades se separan con comas, pero la última propiedad no lleva una coma al final.

## 6. Ejercicios realizados

- [x] Identificar por qué JSON es más fácil de procesar que el texto libre.
- [x] Detectar errores de sintaxis en JSON.
- [x] Reconocer los tipos de datos.
- [x] Identificar un prompt adecuado para generar JSON.
- [x] Construir un prompt propio para generar información de una misión.

## 7. Ejercicio práctico: crear un prompt para una misión

Mi prompt:

```text
Genera una misión para un videojuego y devuelve exclusivamente JSON válido.

Incluye las siguientes propiedades:
- nombre: texto.
- dificultad: texto.
- recompensa: número.
- enemigos: array de textos.
- completada: booleano.

No agregues explicaciones fuera del JSON.
```

Ejemplo de respuesta esperada:

```json
{
  "nombre": "Infiltración nocturna",
  "dificultad": "Difícil",
  "recompensa": 1500,
  "enemigos": [
    "Guardia",
    "Francotirador",
    "Soldado"
  ],
  "completada": false
}
```

## 8. Conclusión

Aprendí que JSON permite organizar información de manera estructurada y que JavaScript puede utilizar esos datos mediante sus propiedades.

También aprendí que podemos diseñar prompts para solicitar a una IA respuestas con una estructura específica.

Un prompt que solicita JSON no garantiza por sí solo que la respuesta sea válida. En aplicaciones reales debemos revisar y validar los datos recibidos.

**Lo más importante:** la IA no solamente puede generar explicaciones o código; también puede generar información organizada que nuestras aplicaciones pueden utilizar.