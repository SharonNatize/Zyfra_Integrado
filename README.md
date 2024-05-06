# Zyfra_Integrado
La empresa desarrolla soluciones de eficiencia para la industria pesada. El modelo debe predecir la cantidad de oro extraído del mineral de oro. Se dispone de datos de extracción y purificación.

**Los datos se almacenan en tres archivos**

gold_recovery_train.csv — el dataset de entrenamiento 

gold_recovery_test.csv —el dataset de prueba 

gold_recovery_full.csv — el dataset fuente 

Los datos se indexan con la fecha y la hora de adquisición (date). Los parámetros cercanos en el tiempo suelen ser similares.

Algunos parámetros no están disponibles porque fueron medidos o calculados mucho más tarde. Por eso, algunas de las características que están presentes en el conjunto de entrenamiento pueden estar ausentes en el conjunto de prueba. El conjunto de prueba tampoco contiene objetivos.

El dataset fuente contiene los conjuntos de entrenamiento y prueba con todas las características.

Tienes a tu disposición los datos en bruto que solamente fueron descargados del almacén de datos. Antes de construir el modelo, comprueba que los datos sean correctos. Para ello, utiliza nuestras instrucciones.

**Construye el modelo**

-Escribe una función para calcular el valor final de sMAPE.

-Entrena diferentes modelos. Evalúalos aplicando la validación cruzada. Elige el mejor modelo y pruébalo utilizando la muestra de prueba. Facilita los resultados.
