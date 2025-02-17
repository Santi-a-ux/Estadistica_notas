# Notas de Estudio: Teoría de Conjuntos, Técnicas de Conteo y Probabilidad

## 1. Teoría de Conjuntos

### Definiciones Clave

+ Conjunto: Colección de elementos bien definidos y únicos, representados entre llaves. Ejemplo: A = {1, 2, 3, 4}.

+ Subconjunto: Un conjunto cuyos elementos están completamente contenidos en otro conjunto mayor. Se denota como A ⊆ B.

+ Conjunto vacío: Conjunto sin elementos. Se denota como ∅.

+ Conjunto universal: Conjunto que contiene todos los elementos posibles dentro de un contexto dado. Se denota como U.

+ Espacio muestral: Conjunto de todos los posibles resultados de un experimento aleatorio.

+ Evento muestral: Subconjunto del espacio muestral.

### Ejemplos Prácticos

Si A = {1, 2, 3} y B = {2, 3, 4}:

+ A ∪ B = {1, 2, 3, 4} (Unión).

+ A ∩ B = {2, 3} (Intersección).

+ A - B = {1} (Diferencia).

### Diagrama Visual: Operaciones Básicas con Diagramas de Venn

+ Dibuja un diagrama de Venn que represente dos conjuntos A y B y sus operaciones de unión, intersección y diferencia.

### Problema Resuelto

#### Problema: En un proyecto de software:

+ A: Programadores que conocen Java (20).

+ B: Programadores que conocen Python (15).

+ A ∩ B: 8 programadores que conocen ambos lenguajes.

#### Solución:

+ Programadores que conocen al menos un lenguaje: |A ∪ B| = |A| + |B| - |A ∩ B| = 20 + 15 - 8 = 27.

### Tips de Estudio

+ Usa diagramas de Venn para visualizar relaciones entre conjuntos.

+ Memoriza las operaciones básicas y sus símbolos (∪, ∩, -).

## 2. Técnicas de Conteo

### Definiciones Clave

+ Regla de la multiplicación: Si un evento puede ocurrir de m maneras y otro de n maneras, el total de combinaciones es m × n.

+ Permutaciones: Arreglos de elementos donde el orden importa.

+ Sin repetición: P(n, r) = n! / (n - r)!

+ Con repetición: n^r.

+ Combinaciones: Selección de elementos donde el orden no importa. C(n, r) = n! / [r!(n - r)!].

### Ejemplo Práctico

#### Una empresa ofrece:

+ 3 bases de datos (MySQL, PostgreSQL, Oracle).

+ 2 frameworks (Spring, Django).

+ 4 niveles de seguridad.

#### Total de combinaciones posibles: 3 × 2 × 4 = 24.

### Problema Resuelto

#### Problema: ¿Cuántas combinaciones de equipos de 3 personas pueden formarse con 15 estudiantes?

#### Solución:

+ C(15, 3) = 15! / [3!(15 - 3)!] = 455.

### Tips de Estudio

+ Usa ejemplos prácticos para entender combinaciones y permutaciones.

+ Practica la regla de la multiplicación con situaciones reales.

## 3. Teoría de la Probabilidad

### Definiciones Clave

+ Probabilidad clásica: P(A) = n(A) / n(S), donde n(A) es el número de resultados favorables y n(S) es el tamaño del espacio muestral.

+ Probabilidad frecuentista: Aproximación basada en la frecuencia relativa de un evento tras muchas repeticiones.

+ Eventos mutuamente excluyentes: Dos eventos que no pueden ocurrir simultáneamente.

+ Eventos independientes: La ocurrencia de un evento no afecta la probabilidad del otro.

### Ejemplo Práctico

#### Lanzar una moneda:

+ P(cara) = 1/2.

+ P(cara o cruz) = 1 (evento seguro).

#### Problema Resuelto

#### Problema: En un proyecto:

+ 20 programadores conocen Java.

+ 15 conocen Python.

+ 18 conocen JavaScript.

+ 5 conocen los tres lenguajes.

##### ¿Cuál es la probabilidad de seleccionar un programador que solo conozca JavaScript?

### Solución:

+ |Solo C| = |C| - |A ∩ C| - |B ∩ C| + |A ∩ B ∩ C| = 6.

+ P(Solo JavaScript) = 6 / 33 ≈ 0.182 (18.2%).

### Tips de Estudio

+ Practica problemas con diferentes tipos de eventos (excluyentes e independientes).

+ Memoriza las definiciones y sus aplicaciones prácticas.

## 4. Resumen General y Estrategias de Estudio

+ Utiliza diagramas para visualizar conjuntos y operaciones.

+ Aplica la regla de la multiplicación en situaciones cotidianas para familiarizarte con su uso.

+ Resuelve ejercicios paso a paso para reforzar los conceptos teóricos.

+ Trabaja en problemas aplicados para entender la relación entre teoría y práctica.
