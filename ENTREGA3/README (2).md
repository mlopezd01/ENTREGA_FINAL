# Contenidos de Netflix

Este proyecto aplica un modelo supervisado sobre un dataset de títulos de Netflix enriquecido con métricas de IMDb y TMDb. El objetivo es predecir correctamente una categoría de clasificación para cada contenido.

Se busca esarrollar un modelo de clasificación supervisada que, a partir de metadatos, permita predecir la categoría de cada título del catálogo de Netflix, con el fin de explorar patrones de calidad y facilitar análisis posteriores sobre el contenido disponible en la plataforma.

## Descripción del proyecto

Se entrenó un modelo de clasificación multiclase para predecir etiquetas de contenido (por ejemplo, tipo o grupo de calidad) utilizando variables como:

- Puntuaciones de IMDb (`imdb_score`, `imdb_votes`)
- Popularidad y puntuación de TMDb (`tmdb_popularity`, `tmdb_score`)
- Otros metadatos del contenido

## Evaluación del modelo

Se evaluó el modelo mediante una matriz de confusión, que permitió identificar:

- Buen rendimiento para la **clase 2**, con 457 aciertos.
- Desempeño moderado para la **clase 0**, aunque con errores hacia la clase 2.
- Bajo rendimiento en la **clase 1**, con mayoría de predicciones erróneas como clase 2.

