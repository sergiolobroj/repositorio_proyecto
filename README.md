Proyecto Final – Introducción a la Inteligencia Artificial

Predicción del ganador en peleas de UFC

- Definición del problema:
En este proyecto se busca predecir el resultado de una pelea de UFC, específicamente si el peleador en la esquina roja ganará o no. Para eso, se usan estadísticas previas al combate, como altura, alcance y rendimiento ofensivo y defensivo de ambos peleadores.

El objetivo es entrenar un modelo supervisado que aprenda a predecir el ganador usando datos reales. Se trata de un problema de clasificación binaria, donde el modelo debe anticipar si el peleador rojo gana (1) o no (0).

- Plan de acción:
Se utilizará un dataset real de resultados de peleas de la UFC desde mediados del 2010 al 2024 (https://www.kaggle.com/datasets/mdabbert/ultimate-ufc-dataset). Los pasos a ejecutar son los siguientes:
1.	Cargar y limpiar el dataset.
2.	Crear la variable objetivo 'red_win' a partir de la columna 'winner'.
3.	Explorar los datos (EDA) y generar visualizaciones.
4.	Construir nuevas variables si es necesario.
5.	Entrenar un modelo de clasificación binaria (un árbol de decisión).
6. Evaluar el modelo y analizar los resultados.

- Justicación del modelo:
Se utilizará el modelo de Árbol de Decisión (DecisionTreeClassifier), por ser interpretativo, fácil de entrenar y coherente con el enfoque del curso. Este modelo permite visualizar qué características de los peleadores tienen mayor peso al momento de predecir el resultado de una pelea.

En etapas posteriores también podrían compararse otros modelos (como Regresión Logística o KNN) para observar mejoras en el rendimiento.

- Resultado esperado:
Lo que se busca es construir un modelo que pueda predecir con buena precisión si el peleador rojo ganará, basándose solo en datos previos al combate. Esto podría ser útil para análisis deportivos, predicciones y visualizaciones dentro del mundo de las MMA.
