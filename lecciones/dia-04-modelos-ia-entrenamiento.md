# Día 04 - Modelos de IA y entrenamiento

## 1. Objetivo

Comprender cómo se entrenan los modelos de inteligencia artificial, cómo aprenden patrones a partir de datos y cuál es la diferencia entre entrenar un modelo y utilizar uno que ya está entrenado.

## 2. ¿Qué significa entrenar un modelo de IA?

Entrenar un modelo significa proporcionarle grandes cantidades de datos para que aprenda patrones y relaciones.

Ejemplo: queremos crear un modelo que reconozca gatos.

1. Proporcionamos miles de imágenes de gatos y otros animales.
2. El modelo procesa las imágenes.
3. Ajusta sus parámetros para aprender patrones.
4. Evaluamos sus resultados con imágenes nuevas.
5. Si funciona correctamente, podemos utilizarlo para reconocer otras imágenes.

El modelo no aprende como una persona. Ajusta parámetros matemáticos para identificar patrones en los datos.

## 3. ¿Qué es un modelo entrenado?

Un modelo entrenado es aquel que ya pasó por un proceso de aprendizaje y cuyos parámetros fueron ajustados.

Por ejemplo, cuando utilizamos ChatGPT, normalmente no estamos entrenando un modelo desde cero. Estamos utilizando un modelo que ya fue entrenado.

## 4. Entrenar un modelo vs. utilizar un modelo

| Entrenar un modelo | Utilizar un modelo |
|---|---|
| Requiere datos de entrenamiento. | Enviamos instrucciones y datos. |
| Ajusta parámetros del modelo. | Utiliza parámetros ya entrenados. |
| Puede requerir muchos recursos. | Puede utilizarse mediante una API. |
| Es un proceso de aprendizaje. | Es un proceso de inferencia. |

Como desarrolladores, podemos utilizar modelos existentes mediante APIs para integrar inteligencia artificial en nuestras aplicaciones JavaScript.

## 5. ¿Qué es el fine-tuning?

El fine-tuning o ajuste fino consiste en continuar el entrenamiento de un modelo previamente entrenado utilizando datos más específicos.

Ejemplo:

- Tenemos un modelo que comprende lenguaje general.
- Queremos adaptarlo a tareas especializadas.
- Utilizamos ejemplos específicos para ajustarlo.
- Evaluamos si ahora responde mejor a esas tareas.

No debemos confundir el fine-tuning con escribir un buen prompt.

| Concepto | Función |
|---|---|
| Prompt | Proporciona instrucciones al modelo. |
| Fine-tuning | Ajusta el modelo mediante entrenamiento adicional. |
| Entrenamiento desde cero | Entrena un modelo sin partir de uno previamente entrenado. |

## 6. ¿Qué es la inferencia?

La inferencia ocurre cuando utilizamos un modelo ya entrenado para generar una predicción o respuesta a partir de una entrada.

Ejemplo:

1. El usuario pregunta: ¿Qué es un array en JavaScript?
2. La aplicación envía la pregunta al modelo.
3. El modelo procesa la información y genera una respuesta.
4. La aplicación muestra la respuesta al usuario.

Cuando integremos una API de IA en una aplicación JavaScript, estaremos utilizando principalmente este proceso.

## 7. Ejercicio de comprensión

**Pregunta 1: ¿Qué significa entrenar un modelo de IA?**

Respuesta: Proporcionar datos para que ajuste sus parámetros y aprenda patrones.

**Pregunta 2: Cuando utilizamos ChatGPT, normalmente estamos:**

Respuesta: Utilizando un modelo que ya fue entrenado.

**Pregunta 3: ¿Qué es el fine-tuning?**

Respuesta: Un ajuste adicional de un modelo previamente entrenado utilizando datos específicos.

**Pregunta 4: ¿Qué es la inferencia?**

Respuesta: El uso de un modelo entrenado para generar predicciones o respuestas.

**Resultado:** 4 de 4 respuestas correctas.

## 8. Ejercicio práctico y reflexión

**Situación:** Quiero aprender inteligencia artificial desde cero para comprender sus fundamentos y no limitarme a utilizar herramientas sin entender cómo funcionan.

Mi elección inicial fue construir y entrenar un modelo desde cero porque quiero comprender todo el proceso.

Después comprendí que aprender los fundamentos de IA no significa necesariamente tener que entrenar un modelo propio.

Para desarrollar aplicaciones con JavaScript, es más práctico comenzar utilizando modelos existentes mediante APIs. Más adelante puedo estudiar cómo construir y entrenar modelos sencillos.

## 9. Conclusión personal

Aprendí que los modelos de inteligencia artificial necesitan un proceso de entrenamiento para aprender patrones a partir de datos.

También comprendí que utilizar un modelo ya entrenado es diferente de entrenarlo, y que el fine-tuning permite adaptarlo mediante entrenamiento adicional.

Como futuro desarrollador, puedo integrar inteligencia artificial en mis aplicaciones utilizando modelos existentes y APIs, sin tener que construir un modelo desde cero.

Mi objetivo es comprender primero los fundamentos y después aprender a integrar estas tecnologías en proyectos reales.

---

**Estado:** Lección 04 completada y documentada.