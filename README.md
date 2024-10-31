### Bank Marketing
El presente proyecto incluye dos archivos Jupyter Notebook, el principal [Comparing Classifiers](https://github.com/FernandoSanchezSar/Bank_marketing/blob/main/Comparing_Classifiers.ipynb)
 y un segundo de apoyo de nombre [Evaluation](https://github.com/FernandoSanchezSar/Bank_marketing/blob/main/Evaluation.ipynb). Estos archivos incluyen una declaración clara que demuestra la comprensión del problema comercial, una interpretación correcta y concisa de las estadísticas descriptivas e inferenciales y los próximos pasos y recomendaciones.
### Entendimiento del Negocio
El objetivo comercial es aumentar la eficiencia de las campañas dirigidas para las suscripciones de depósitos a largo plazo reduciendo el número de contactos a realizar.
Para alcanzar este  objetivo debemos comparar el rendimiento de los clasificadores (k vecinos más cercanos, regresión logística, árboles de decisión y máquinas de vectores de soporte) que encontramos en esta sección del programa.
### Evaluación de Resultados
#### Primera iteración
1.	Los modelos de Logistic Regression y Support Vector Machine son los mas adecuados porque alcanza los mejores valores de accuracy. 
2.	Se observa que el modelo Logistic Regression tiene una mínima diferencia entre las métricas Train Accuracy y Test Accuracy.
3.	En relación con los tiempos de entrenamiento es evidente que el modelo Support Vector Machine es mucho mayor a los otros modelos. 
4.	El AUC traza la Tasa de Falsos Positivos (FPR) frente a la Tasa de Verdaderos Positivos (TPR) y permite identificar qué tan buena es la discriminación de clases: cuanto más alta, mejor, con el modelo ideal teniendo un valor de 1.0. Los resultados muestran que hubo una clara evolución en las capacidades de predicción de los modelos Logistic Regression 0.94 y SVM 0.93
#### Segunda iteración
Después de realizar los ajustes a los hiperparámetros de los diferentes modelos de clasificación vemos que SVM y Decision Tree son los que tienen mejores Train Accuracy, pero si nos enfocamos en el Test Accuracy, los modelos Decision Tree y Logistic Regression son los que tienen mejor precisión. Por otro lado, SVM es un modelo que también ha obtenido buena precisión, sin embargo, su velocidad baja de entrenamiento, mala adecuación a clases desequilibradas y baja interpretabilidad no lo hace viable.
### Próximos pasos y Recomendaciones
1.	Se recomienda que, en trabajos futuros, se recopile más datos basados en el cliente, con el fin de verificar si se pueden lograr modelos predictivos de alta calidad sin información basada en contacto. 
2.	Dentro de la información ha recopilar puede estar el número de hijos del cliente, si están en edad escolar, si tienen preferencias por tomar vacaciones, fecha próxima de cambio de vehículo o si tienen preferencia por hacer una maestría. 
3.	También planeamos aplicar los mejores modelos de DM / ML en un entorno real, con una interacción más estrecha con los gerentes de marketing, con el fin de obtener una retroalimentación valiosa.
### Conclusiones
1.	Los modelos de Logistic Regression, Decision Tree y SVM, han logrado altos rendimientos predictivos. Sin embargo, se recomienda usar el modelo Logistic Regression o Decision Tree por su adpatación a clases desequilibradas, velocidad de entrenamiento y alta interpretabilidad.
2.	El análisis de sensibilidad indica que la característica de duración de las llamadas es importante para la adquisición del producto, por lo que se propone que los agentes aumenten la duración de las llamadas telefónicas y/o programándolas en campañas en los meses más favorables
3.	Otro resultado importante es la confirmación de la tecnología de código abierto de sklearn, matplotlib y seaborn y pandas en el campo de ML son capaces de proporcionar modelos de alta calidad para aplicaciones reales, lo que permite una reducción de costos de los proyectos de ML. 
4.	La metodología CRISP-DM se adecua para proyectos que tienen un enfoque a Machine Learning sobre las campañas de marketing directo de los bancos. En efecto, cada iteración de CRISP-DM ha demostrado ser de gran valor, ya que los rendimientos predictivos obtenidos aumentan. 
