# Bitácora de Autoevaluación: Unidad 2 - Inferencia Estadística

## 1. Resumen del aprendizaje

Durante esta unidad comprendí cómo pasar de la estadística descriptiva a la inferencia estadística. Aprendí que herramientas como `scipy.stats` no funcionan como una "caja negra", sino que aplican fundamentos matemáticos para analizar y tomar decisiones a partir de los datos.

### Principales aprendizajes

- **Diagnóstico de normalidad:** Aprendí a verificar si los datos siguen una distribución normal utilizando gráficos Q-Q y la prueba de Shapiro-Wilk.
- **Teorema del Límite Central:** Comprendí que, al aumentar el tamaño de la muestra, las medias muestrales tienden a seguir una distribución normal, lo que permite realizar inferencias más confiables.
- **Estimación por intervalos:** Entendí la importancia de utilizar intervalos de confianza en lugar de depender únicamente de estimaciones puntuales.
- **Pruebas de hipótesis y valor-p:** Aprendí a interpretar correctamente el valor-p para decidir si existe evidencia suficiente para rechazar la hipótesis nula.

---

## 2. Dificultades superadas

Durante la implementación en Python encontré algunos desafíos que logré resolver.

- Fue necesario limpiar la variable **fexp** para corregir inconsistencias y convertir correctamente los datos al tipo `float`.
- Aprendí cuándo utilizar una **Prueba Z** y cuándo aplicar una **Prueba t de Student**, entendiendo que la varianza poblacional era desconocida.
- También comprendí la importancia de verificar la **homocedasticidad** mediante la prueba de Levene antes de realizar el A/B Testing.

---

## 3. Impacto en el Proyecto Integrador Regional

El análisis que más aportó al proyecto fue el **A/B Testing** entre los sectores urbano y rural de Loja. El resultado obtenido (**valor-p = 4.0440 × 10⁻⁴**) evidenció una diferencia estadísticamente significativa entre ambos grupos. Esto me permitió comprender que las decisiones de ingeniería deben adaptarse a las características de cada sector y no tratar a toda la población de la misma manera.
