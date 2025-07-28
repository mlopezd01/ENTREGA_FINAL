**Segmentación de Películas y Series mediante Clustering**

Este proyecto aplica técnicas de reducción de dimensionalidad (PCA) y supervisaje no supervisado (clustering) para segmentar un catálogo de películas y series según sus características técnicas, de género, distribución geográfica y recepción del público.

*Objetivo*

Descubrir patrones latentes en el contenido audiovisual que permitan entender su estructura interna y mejorar su análisis o recomendación personalizada.


*Metodología*

**Reducción de dimensionalidad**: Se aplicó PCA para facilitar la visualización y mejorar el desempeño de los algoritmos de clustering.

**Clustering**: Se utilizaron K-Means y DBSCAN para agrupar el contenido.

    - K-Means generó grupos significativos relacionados con géneros, puntuaciones y regiones.

    - DBSCAN no produjo resultados tan útiles para el objetivo inicial.

***Principales hallazgos***

1) El uso combinado de PCA + K-Means permitió identificar clusters coherentes, útiles para sistemas de recomendación.

2) Se observaron agrupamientos relacionados con duración, puntuación, géneros predominantes y alcance geográfico.

3) DBSCAN resultó menos eficaz en este caso, posiblemente por la naturaleza de los datos y su dispersión.

**Conclusión**

La segmentación no supervisada es una herramienta útil para analizar catálogos audiovisuales. K-Means, en combinación con PCA, demostró ser una estrategia adecuada para identificar perfiles de contenido y orientar recomendaciones personalizadas.
