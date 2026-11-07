# Día 03 - Cómo evaluar las respuestas de la IA

## 1. Objetivo

Aprender a evaluar las respuestas y el código generado por una inteligencia artificial, verificando que sean correctos, comprensibles y útiles.

## 2. ¿Por qué debemos evaluar las respuestas de la IA?

La IA puede generar respuestas útiles, pero también puede cometer errores, interpretar mal una instrucción o producir código que no funcione como esperamos.

Por eso, no debemos aceptar automáticamente todo lo que genera.

Debemos revisar, comprender y probar sus respuestas.

## 3. ¿Cómo evaluar código generado por IA?

Podemos seguir estos pasos:

1. **Revisar el código:** observar qué cambios propone la IA.
2. **Comprenderlo:** identificar qué hace cada parte del código.
3. **Probar diferentes entradas:** comprobar cómo funciona con distintos valores.
4. **Verificar los resultados:** comparar los resultados obtenidos con los esperados.
5. **Probar casos especiales:** comprobar qué sucede con entradas vacías o inesperadas.
6. **Corregir errores:** modificar el código si encontramos problemas.

## 4. Ejemplo práctico con JavaScript

Tenemos una función que calcula el promedio de varias notas:

```javascript
function calcularPromedio(notas) {
  let suma = 0;

  for (let nota of notas) {
    suma += nota;
  }

  return suma / notas.length;
}
```

Podemos probarla con diferentes casos:

| Entrada | Resultado esperado |
|---|---|
| `[80, 90, 100]` | 90 |
| `[70, 70, 70]` | 70 |
| `[85]` | 85 |
| `[]` | Debe manejarse el caso especial |

La función original tiene un problema: si recibe un array vacío, divide entre cero y devuelve `NaN`.

Una posible mejora sería:

```javascript
function calcularPromedio(notas) {
  if (notas.length === 0) {
    return 0;
  }

  let suma = 0;

  for (let nota of notas) {
    suma += nota;
  }

  return suma / notas.length;
}
```

Ahora la función contempla el caso de no recibir notas.

## 5. Buenas prácticas al utilizar IA para programar

- No aceptar código sin revisarlo.
- Pedir explicaciones paso a paso.
- Probar el código con diferentes valores.
- Verificar los resultados.
- Comprobar situaciones especiales.
- Aprender de los errores en lugar de copiar soluciones sin comprenderlas.

## 6. Ejercicio realizado

**Situación:**

Estoy aprendiendo JavaScript y tengo una función que calcula el promedio de las notas. Necesito modificaciones para que funcione correctamente y que me expliquen paso a paso cómo solucionar los problemas y mejorar el código.

**Mi respuesta:**

Para evaluar el código, debemos probarlo con diferentes promedios y revisar que los resultados sean correctos. También debemos explicar y verificar cada modificación.

## 7. Pregunta de repaso

**¿Cuál es la mejor práctica antes de aceptar una solución de código generada por IA?**

Respuesta correcta: B.

Revisar el código, entender los cambios y probarlo con diferentes casos.

## 8. Conclusión personal

Aprendí que no debemos confiar ciegamente en el código generado por una inteligencia artificial. Es importante revisar cómo funciona, comprender los cambios y probar diferentes situaciones para verificar que los resultados sean correctos.

La IA puede ayudarnos a programar, pero nosotros somos responsables de comprobar que el código funcione correctamente.

---

**Estado:** Lección 03 completada y documentada.