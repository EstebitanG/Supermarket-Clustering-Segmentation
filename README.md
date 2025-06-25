# Supermarket Clustering Segmentation
Este proyecto forma parte de mi portfolio de Data Analytics y Data Science, donde se usa el lenguaje de programación Python aplicando técnicas estadísticas y de Machine Learning para segmentar clientes de un supermercado acorde a sus variables sociodemográficas y comportamiento de compra.

# Descripción General 
Este proyecto busca agrupar clientes con comportamientos y características en común, usando técnicas de aprendizaje no supervisado. Se obtienen 3 clusters finales: "Exploradores Digitales de Bajo Consumo", “Compradores Premium Multicanal” y “Digitales Sofisticados con Consumo Selectivo”.

Los datos fueron sacados del sitio web Kaggle: https://www.kaggle.com/datasets/vishakhdapat/customer-segmentation-clustering

Se hace primerante la importación del archivo csv a Python, para posteriormente realizar un preprocesamiento y exploración de los datos usando Pandas y Numpy. Dentro de esta etapa fue necesario tomar decisiones respecto al tratamiento de "outliers" (valores atípicos), lo cual fue crucial su correcto manejo para la menor pérdida de información posible sin afectar los algoritmos de clustering. Posterior a ello, se realizan la codificación y estandarización necesaria para aplicar los siguientes algoritmos: KMeans, DBSCAN, Clustering Jerárquico Aglomerativo y Gaussian Mixture Model (GMM con y sin PCA). Los resultados de cada algoritmo aplicado a nuestro dataset particular, si bien no son totalmente desfavorables, distan de ser suficientemente buenos para garantizar una segmentación exitosa, sin embargo, este percance tiene más que ver con la naturaleza del dataset en sí mismo que con los algoritmos aplicados. Se evalúa la calidad de estos algoritmos principalmente con Silhouette Score y Davis Boudin Index. Finalmente se decide por usar Clustering Jerárquico Aglomerativo al ser el algoritmo que entregó las mejores métricas de calidad, para proceder con el análisis cruzado y perfilamiento de los 3 clusters finales.

Para este proyecto se utilizó principalmente Python para cumplir con la ruta de analista y científico de datos, desde la importación de la información, su procesamiento, aplicación de modelos y exportación de la clasificación.

![customer-segmentation](https://github.com/user-attachments/assets/2bc7205f-3c7a-414e-9321-ddbaf82c7edb)

