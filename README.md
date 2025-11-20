# Entrega_Final_Data_Mining

Integrantes:
Bautista Abanto, Mildred Belinda
Masaki Perales, Aiko Valentina 
Munayco Meneses, Alessandra Solany

El presente estudio analiza el desempeño de las películas utilizando un enfoque que combina técnicas de análisis exploratorio, modelamiento predictivo y sistemas de recomendación. Se emplea el IMDb 5000 Movie Dataset, compuesto por 5,043 películas y 28 variables mixtas, para aplicar  Factor Analysis of Mixed Data (FAMD), con el fin de identificar patrones estructurales en datos numéricos y categóricos, y Non-Negative Matrix Factorization (NMF) para la extracción de temas  a partir de palabras clave. Asimismo, se entrena un modelo de clasificación basado en Random Forest con hiperparámetros optimizados mediante GridSearchCV, el cual predice la calidad de las películas según tres categorías propuestas (Good, Neutral, Not Good). Finalmente, se integra un sistema de recomendación basado en similitud de contenido y filtrado por calidad, permitiendo sugerir títulos de acuerdo con la calificación prevista. Los resultados evidencian que los primeros ocho componentes de FAMD explican cerca del 80\% de la varianza del conjunto de datos, mientras que NMF identifica doce temas principales de contenido cinematográfico. El modelo alcanza un recall promedio de 0.61 y se muestra especialmente eficaz en la categoría Good. El enfoque propuesto ofrece una estructura para comprender el comportamiento de las películas y mejorar la calidad de las recomendaciones.
