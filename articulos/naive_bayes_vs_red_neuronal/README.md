# Naive Bayes vs una red neuronal simple en reseñas de películas: lo que aprendí comparando ambos

*   **Fecha de Publicación:** 11 de Marzo
*   **Autor:** Juan Pedro R.F.
*   **Enlace de Lectura Directa:** [Leer en Medium](https://medium.com/@criticamascritica)

---

## 📌 Resumen Ejecutivo del Artículo

En este proyecto final, analicé el dataset clásico `movie_reviews` de NLTK para realizar una comparativa técnica entre un clasificador probabilístico clásico (Naive Bayes) y un perceptrón multicapa básico (una red neuronal simple de clasificación de texto).

### Hallazgos Clave:
*   **Naive Bayes:** Demostró ser un modelo extremadamente eficiente en cuanto a consumo de CPU y velocidad de entrenamiento, sirviendo como una línea base (*baseline*) insuperable para datasets pequeños debido a su alta interpretabilidad.
*   **Red Neuronal:** Ofrece una capacidad superior para capturar relaciones no lineales y patrones complejos de vocabulario, pero con un coste computacional significativamente mayor y menor transparencia (caja negra).
*   **Conclusión:** Para la mayoría de los análisis rápidos de sentimiento, un baseline probabilístico (Naive Bayes) optimizado con una buena curación de tokens es superior y más rentable que una red neuronal simple en producción.

---
*Nota: Este directorio está reservado para la versión en Markdown del artículo completo con sus bloques de código en Python. Puedes leer el texto original completo directamente en mi perfil de Medium.*
