# Bitácora de Autoevaluación: Unidad 2 - Inferencia Estadística

## 1. Resumen del aprendizaje

Durante esta unidad comprendí cómo pasar de la estadística descriptiva a la inferencia estadística. Aprendí que herramientas como `scipy.stats` no funcionan como una "caja negra", sino que aplican fundamentos matemáticos para analizar y tomar decisiones a partir de los datos.

### Principales aprendizajes



- Aprendí a plantear correctamente la hipótesis nula y la hipótesis alternativa para comprobar si la media de una muestra es igual a un valor de referencia.

- Comprendí que la **prueba *t* de Student para una muestra** se utiliza cuando la varianza poblacional es desconocida, permitiendo determinar si la diferencia entre la media muestral y la media propuesta es estadísticamente significativa.
- **Estimación por intervalos:** Entendí la importancia de utilizar intervalos de confianza en lugar de depender únicamente de estimaciones puntuales.
- **Pruebas de hipótesis y valor-p:** Aprendí a interpretar correctamente el valor-p para decidir si existe evidencia suficiente para rechazar la hipótesis nula.

---

## 2. Dificultades superadas

Durante la implementación en Python encontré algunos desafíos que logré resolver.

- Fue necesario limpiar la variable **fexp** para corregir inconsistencias y convertir correctamente los datos al tipo `float`.
- Aprendí cuándo utilizar una **Prueba Z** y cuándo aplicar una **Prueba t de Student**, entendiendo que la varianza poblacional era desconocida.
- Al inicio se me dificultaba identificar en qué casos debía aplicar la **prueba *t* de Student** y en cuáles correspondía utilizar la **distribución *Z***. Sin embargo, con la práctica comprendí los criterios para seleccionar la prueba estadística adecuada según las características de los datos.
---

## 3. Impacto en el Proyecto Integrador Regional

El análisis que más aportó al proyecto fue el **A/B Testing** entre los sectores urbano y rural de Loja. El resultado obtenido (**valor-p = 4.0440 × 10⁻⁴**) evidenció una diferencia estadísticamente significativa entre ambos grupos. Esto me permitió comprender que las decisiones de ingeniería deben adaptarse a las características de cada sector y no tratar a toda la población de la misma manera.
