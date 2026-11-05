# Día 02 - Tokens, contexto y límites de la IA

## 1. Objetivo

Comprender cómo los modelos de inteligencia artificial procesan información mediante tokens, qué es la ventana de contexto y cuáles son sus límites al trabajar con programación.

## 2. ¿Qué es un token?

Un token es una unidad de texto que un modelo de IA utiliza para procesar y generar información.

Un token no necesariamente equivale a una palabra completa. Puede representar una palabra, una parte de una palabra o un símbolo.

Cuando enviamos código JavaScript a una IA, el código también se procesa mediante tokens.

## 3. ¿Qué es la ventana de contexto?

La ventana de contexto representa la cantidad máxima de información que un modelo puede tener en cuenta durante una interacción.

Por ejemplo, cuando trabajamos con React podemos proporcionar:

- Componentes.
- Archivos de configuración.
- Mensajes de error.
- Instrucciones.
- Información sobre el proyecto.

Toda esta información forma parte del contexto disponible.

## 4. Límites del contexto

Los modelos de IA tienen límites en la cantidad de información que pueden procesar.

Cuando enviamos demasiada información, puede ocurrir que:

- No podamos enviar todo el contenido.
- Sea necesario resumir o reducir la información.
- Parte del contexto anterior deje de estar disponible.
- La respuesta no considere algún detalle importante.

**Conclusión:** proporcionar más información no siempre significa obtener una mejor respuesta. Es importante compartir información relevante y organizada.

## 5. Aplicación práctica en programación

Al solicitar ayuda a una IA para modificar una función JavaScript, es importante proporcionar:

- Nuestro nivel de conocimiento.
- Qué hace actualmente el código.
- Qué modificación necesitamos.
- Qué resultado esperamos.
- Cómo queremos recibir la explicación.

### Ejemplo de prompt

Estoy aprendiendo JavaScript y tengo una función que calcula el promedio de un conjunto de notas.

Necesito modificarla para que ignore las notas negativas y solamente utilice las notas mayores o iguales a cero.

Quiero que me expliques los cambios paso a paso, manteniendo el código sencillo para un principiante.

## 6. Ejercicio práctico

Se presentó una función que calcula el promedio de varias notas.

El objetivo era construir un prompt para solicitar a la IA que modificara la función y excluyera las notas negativas.

Mi prompt inicial proporcionó:

- Mi nivel de conocimiento.
- La descripción de la función.
- El código original.
- La solicitud de una explicación paso a paso.

### Mejora del prompt

Se identificó que era necesario especificar exactamente qué comportamiento debía modificarse: ignorar las notas negativas.

Esto permitió construir una instrucción más clara y precisa.

## 7. Conceptos aprendidos

- Qué son los tokens.
- Cómo se procesa el código mediante tokens.
- Qué es la ventana de contexto.
- Qué sucede cuando se supera el límite de contexto.
- La importancia de proporcionar información relevante.
- Cómo construir prompts con contexto suficiente.

## 8. Pregunta de repaso

**¿Qué es mejor al solicitar ayuda para corregir un error en un proyecto React?**

Respuesta correcta: proporcionar el componente relacionado, el mensaje de error y el contexto necesario para comprender el problema.

## 9. Conclusión personal

Aprendí que los modelos de IA tienen límites en la cantidad de información que pueden procesar y que los tokens son las unidades que utilizan para trabajar con el texto y el código.

También comprendí que no es necesario enviar todo un proyecto para obtener ayuda. Es mejor proporcionar únicamente la información relevante para que la IA pueda entender el problema.

Este conocimiento me ayudará a trabajar de una manera más eficiente con herramientas de inteligencia artificial durante el desarrollo de aplicaciones.

---

**Estado:** Lección 02 documentada.