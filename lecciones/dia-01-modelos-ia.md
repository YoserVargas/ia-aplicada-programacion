# Día 01 - Cómo funciona un modelo de IA

## 🎯 Objetivo

Comprender cómo funciona un modelo de inteligencia artificial cuando recibe una petición, cómo genera respuestas y cuál es la función de una aplicación al comunicarse con un modelo.

## 1. Modelo de IA vs. aplicación

**Modelo de IA:**
Es el sistema entrenado para procesar información y generar respuestas.

**Aplicación:**
Es el programa o interfaz que permite a los usuarios interactuar con un modelo de IA.

Ejemplo:
- GPT es una familia de modelos de inteligencia artificial.
- ChatGPT es una aplicación que permite interactuar con modelos.
- Una aplicación desarrollada en JavaScript también puede utilizar un modelo de IA.

## 2. ¿Qué sucede cuando enviamos una petición?

El proceso simplificado es:

1. El usuario escribe una pregunta.
2. La aplicación recibe la petición.
3. La aplicación envía la información al modelo de IA.
4. El modelo procesa la petición y genera una respuesta.
5. La aplicación recibe y muestra el resultado.

**Importante:** el modelo no modifica automáticamente los archivos de un proyecto. Normalmente devuelve una respuesta y la aplicación decide qué hacer con ella.

## 3. ¿Cómo genera respuestas la IA?

Los modelos de lenguaje utilizan patrones aprendidos durante su entrenamiento para generar respuestas.

Una parte importante de este proceso es la predicción de tokens.

Un token puede representar:
- Una palabra.
- Una parte de una palabra.
- Un signo de puntuación.
- Otro fragmento de texto.

El modelo genera tokens progresivamente hasta construir una respuesta.

## 4. ¿Qué es el contexto?

El contexto es la información disponible para que el modelo interprete correctamente una petición.

Ejemplo:

Petición sencilla:
"Explícame qué son los arrays".

Petición con contexto:
"Estoy aprendiendo JavaScript. Explícame qué son los arrays con ejemplos sencillos para principiantes".

La segunda petición proporciona más información para adaptar la respuesta.

**Conclusión:** un contexto claro y relevante puede ayudar a obtener mejores respuestas.

## 5. ¿Qué es una API?

Una API permite que diferentes aplicaciones o sistemas se comuniquen entre sí.

En el desarrollo de software, podemos utilizar una API para conectar una aplicación JavaScript con un modelo de inteligencia artificial.

La aplicación envía una petición y recibe una respuesta del servicio de IA.

## 6. Conceptos aprendidos

- Diferencia entre modelo de IA y aplicación.
- Flujo de una petición a un modelo.
- Generación de respuestas mediante tokens.
- Importancia del contexto.
- Función de una API para conectar aplicaciones con modelos de IA.

## 7. Pregunta de repaso

**¿Cuál es la función de una API al integrar inteligencia artificial en una aplicación?**

Respuesta correcta:

Permitir que la aplicación envíe peticiones a un modelo de IA y reciba sus respuestas.

## 8. Conclusión personal

Aprendí que una aplicación y un modelo de IA cumplen funciones diferentes. La aplicación permite interactuar con el modelo, mientras que este procesa la información y genera respuestas.

También comprendí que las APIs permiten conectar nuestros programas con servicios de inteligencia artificial.

Este conocimiento será importante para desarrollar aplicaciones propias que integren IA utilizando JavaScript.

---

**Estado:** Lección 01 documentada.