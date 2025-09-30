Curso: Metodología de Data Science
Grupo: 3 integrantes

👥 Miembros del equipo

Gustavo Arturo Poma Espinoza – Data Engineer
Jeffrey Ulises Díaz Villanueva – Data Analyst
Tomás Alonso Pastor Salazar – Data Scientist

🎯 Tema elegido

Detección de transacciones fraudulentas en tarjetas de crédito
El problema principal a resolver es identificar patrones en los datos que permitan distinguir entre transacciones legítimas y fraudulentas.

📝 Problema a resolver

El fraude con tarjetas de crédito representa una pérdida significativa para las instituciones financieras y genera desconfianza en los usuarios.
Nuestro objetivo es explorar y analizar el dataset creditcard.csv para comprender sus características y preparar el terreno hacia la construcción de un modelo de clasificación que apoye en la detección temprana de fraudes.

📂 Estructura de carpetas del repositorio

  ┣ creditcard.csv            
  ┣ TB1_CreditCard.ipynb        
  ┣ 📜 README.md         

🔍 Exploración inicial (EDA)

1. Verificación de tipos de datos, memoria, duplicados y valores faltantes.
2. Resumen de variables numéricas (V1..V28, Amount, Time).
3. Identificación de la variable objetivo Class (0 = no fraude, 1 = fraude).
4. Visualizaciones iniciales:
  - Distribución de la variable objetivo (balance de clases).
  - Distribución de Amount y Time con transformaciones logarítmicas.
  - Matriz de correlación de las variables numéricas principales.


📌 Limitaciones del dataset

1. Variables anónimas: Las columnas V1..V28 provienen de una transformación PCA, lo que limita la interpretación directa de los patrones.
2. Contexto temporal limitado: El dataset cubre solo dos días de transacciones, lo cual puede no reflejar patrones más largos o estacionales

🔗 Enlace al repositorio

- https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
