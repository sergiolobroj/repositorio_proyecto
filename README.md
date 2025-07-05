Proyecto Final – Introducción a la Inteligencia Artificial

Clasificación de estilo de lucha de peleadores de UFC

Definición del problema:
En las artes marciales mixtas, comprender el estilo de pelea de un atleta es esencial para analizar su estrategia, evaluar su desempeño y proyectar y/o predecir futuros resultados. Sin embargo, esta clasificación rara vez está disponible de forma estructurada en los datos disponibles.
El proyecto en cuestión tiene como objetivo predecir el estilo de lucha de un peleador de UFC dentro de tres categorías: Striker, Grappler o Táctico. Esto se llevará a cabo utilizando datos estadísticos cuantitativos disponibles. Para esto, se entrenará un modelo de clasificación supervisado, permitiendo de esta manera asignar a cada peleador su estilo según el perfil determinado.

Plan de acción:
Se utilizará un dataset real de estadísticas de peleadores de la UFC (https://www.kaggle.com/datasets/asaniczka/ufc-fighters-statistics), el cual incluye variables como golpes significativos por minuto, derribos, sumisiones, precisión y defensa.
Los pasos a ejecutar son los siguientes:
1.	Limpieza de datos y creación de la variable objetivo, la cual llamaremos “estilo_lucha”.
2.	EDA  y Feature Engineering.
3.	División de datos en entrenamiento y prueba.
4.	Entrenamiento de un modelo de clasificación.
5.	Evaluación del modelo con las métricas correspondientes y visualización de resultados.

Justicación del modelo:
Se eligió el modelo de Árbol de Decisión ya que es altamente interpretable, fácil de entrenar y adecuado para clasificación multiclase con datos tabulares. Este modelo nos permitirá visualizar cómo las distintas estadísticas determinan el estilo de pelea, siendo coherente con el objetivo del proyecto.
