# Notas de Estudio: Teoría de Conjuntos, Técnicas de Conteo y Probabilidad

## 1. Definiciones Clave

**Conjunto:** Colección de elementos bien definidos, únicos y sin orden específico. Se representa con letras mayúsculas y sus elementos entre llaves.

*Ejemplo:* `A = {1, 2, 3}`.

**Subconjunto:** Un conjunto `B` es subconjunto de `A` si todos los elementos de `B` pertenecen a `A`.

*Ejemplo:* Si `A = {1, 2, 3}`, entonces `B = {1, 2}` es un subconjunto de `A`.

**Espacio Muestral (`S`):** Conjunto de todos los posibles resultados de un experimento aleatorio.

*Ejemplo:* Al lanzar un dado, `S = {1, 2, 3, 4, 5, 6}`.

**Evento Muestral:** Subconjunto del espacio muestral.

*Ejemplo:* En el lanzamiento de un dado, el evento "sacar un número par" es `{2, 4, 6}`.

**Permutación:** Arreglo de elementos donde importa el orden.

*Ejemplo:* Las permutaciones de `{A, B, C}` son `ABC, ACB, BAC, BCA, CAB, CBA`.

**Combinación:** Selección de elementos donde no importa el orden.

*Ejemplo:* Las combinaciones de 2 elementos de `{A, B, C}` son `AB, AC, BC`.

**Probabilidad Clásica:** Si todos los resultados son igualmente probables, la probabilidad de un evento `A` es:

`P(A) = Número de resultados favorables / Número total de resultados`

---

## 2. Ejemplos Prácticos

### Teoría de Conjuntos:

**Problema:** En un equipo de programadores, 20 conocen Java, 15 Python y 18 JavaScript. Además, 8 conocen Java y Python, 10 Java y JavaScript, 7 Python y JavaScript, y 5 conocen los tres lenguajes.

**Solución:** Usar diagramas de Venn para calcular cuántos programadores conocen al menos un lenguaje.

`|A ∪ B ∪ C| = |A| + |B| + |C| − |A ∩ B| − |A ∩ C| − |B ∩ C| + |A ∩ B ∩ C|`

`|A ∪ B ∪ C| = 20 + 15 + 18 − 8 − 10 − 7 + 5 = 33`

### Técnicas de Conteo:

**Problema:** ¿Cuántas contraseñas de 8 caracteres se pueden crear si deben incluir letras mayúsculas, minúsculas, números y al menos un carácter especial?

**Solución:** Usar la regla de la multiplicación. Si hay 26 letras mayúsculas, 26 minúsculas, 10 números y 10 caracteres especiales, el número total de contraseñas es:

`26 × 26 × 10 × 10 × 10 × 10 × 10 × 10 = 26^2 × 10^6`

### Probabilidad:

**Problema:** En una fábrica, 25 productos tienen defectos de diseño, 30 de manufactura y 20 de empaque. Si se selecciona un producto al azar, ¿cuál es la probabilidad de que tenga solo un tipo de defecto?

**Solución:** Calcular la probabilidad usando la definición clásica.

`P(solo un defecto) = (15 + 19 + 12) / 200 = 46 / 200 = 0.23`

---

## 3. Diagramas Visuales

**Diagrama de Venn:** Representación gráfica de conjuntos y sus relaciones.

*Ejemplo:* Para los conjuntos `A`, `B` y `C`, el diagrama muestra las intersecciones y uniones.

**Árbol de Probabilidades:** Herramienta para visualizar eventos secuenciales y calcular probabilidades condicionales.

*Ejemplo:* Lanzar una moneda dos veces.

---

## 4. Fórmulas Importantes

**Unión de Conjuntos:**

`|A ∪ B| = |A| + |B| − |A ∩ B|`

*Explicación:* Suma los elementos de `A` y `B`, luego resta los elementos que se cuentan dos veces (intersección).

**Permutaciones:**

`P(n, r) = n! / (n − r)!`

*Explicación:* Número de formas de ordenar `r` elementos de un total de `n`.

**Combinaciones:**

`C(n, r) = n! / [r!(n − r)!]`

*Explicación:* Número de formas de seleccionar `r` elementos de un total de `n` sin importar el orden.

**Probabilidad de Eventos Independientes:**

`P(A ∩ B) = P(A) × P(B)`

*Explicación:* La probabilidad de que dos eventos independientes ocurran juntos es el producto de sus probabilidades individuales.

---

## 5. Resúmenes de Problemas Resueltos

**Problema de Conjuntos:**

**Enunciado:** En un equipo de programadores, calcular cuántos conocen exactamente dos lenguajes.

**Solución:**

`Java y Python (solo) = |A ∩ B| − |A ∩ B ∩ C| = 8 − 5 = 3`

`Java y JavaScript (solo) = |A ∩ C| − |A ∩ B ∩ C| = 10 − 5 = 5`

`Python y JavaScript (solo) = |B ∩ C| − |A ∩ B ∩ C| = 7 − 5 = 2`

`Total = 3 + 5 + 2 = 10 programadores`

**Problema de Probabilidad:**

**Enunciado:** Calcular la probabilidad de seleccionar un programador que conozca solo JavaScript.

**Solución:**

`P(solo JavaScript) = 6 / 33 ≈ 0.182`

---

## 6. Tips y Estrategias de Estudio

**Memorización de Fórmulas:** Usa reglas mnemotécnicas para recordar fórmulas. Por ejemplo, para la unión de conjuntos: "Suma todo, resta lo que se repite".

**Práctica Constante:** Resuelve problemas diariamente para reforzar los conceptos. Usa plataformas como Brilliant.org o Khan Academy.

**Uso de Diagramas:** Dibuja diagramas de Venn para visualizar problemas de conjuntos y árboles de probabilidad para eventos secuenciales.

**Resolución Paso a Paso:** Divide los problemas en partes más pequeñas y resuelve cada una por separado.

**Revisión de Errores:** Analiza tus errores en ejercicios y exámenes para identificar patrones y mejorar.

