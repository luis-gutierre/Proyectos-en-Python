Segementacion de Clientes 🛍️

Este proyecto se centra en el análisis de datos y la segmentación de clientes de un centro comercial. Utilizando técnicas de clustering, el objetivo es dividir a los clientes en grupos con características similares para que el equipo de marketing pueda desarrollar estrategias dirigidas y personalizadas.

🎯 Objetivo del Proyecto
El objetivo principal es identificar y agrupar clientes con comportamientos de compra y características demográficas similares. Esta segmentación permite a la gerencia del centro comercial:

Entender mejor a sus clientes.

Crear campañas de marketing más efectivas.

Optimizar las ofertas y promociones.

Mejorar la experiencia de compra en general.

📊 Descripción del Conjunto de Datos
El análisis se realizó sobre el archivo Mall_Customers.csv, que contiene información de 200 clientes. Las columnas clave utilizadas para el análisis son:

Gender: Género del cliente.

Age: Edad del cliente.

Annual Income (k$): Ingresos anuales del cliente en miles de dólares.

Spending Score (1-100): Puntuación asignada por el centro comercial basada en el comportamiento del cliente y el gasto.

🛠️ Herramientas y Tecnologías Utilizadas
Lenguaje de Programación: Python

Librerías Clave:

pandas: Para la manipulación y análisis de datos.

matplotlib y seaborn: Para la visualización de datos y la exploración de patrones.

scikit-learn: Para la implementación del algoritmo de clustering K-Means y otras herramientas de preprocesamiento.

Entorno de Desarrollo: Jupyter Notebook

Repositorio: GitHub, para almacenar y versionar el código y la documentación.

📈 Metodología y Resultados Clave
El proyecto sigue un proceso estándar de análisis de datos:

Exploración de datos (EDA): Se analizó la distribución de las variables y la correlación entre ellas para obtener una visión inicial de los datos.

Preprocesamiento de Datos: Se escalaron las variables numéricas (Annual Income y Spending Score) utilizando StandardScaler para asegurar que el algoritmo de clustering no estuviera sesgado por la magnitud de los valores.

Selección del Número de Clusters: Se aplicó el método del codo (Elbow Method) para determinar el número óptimo de clusters, que resultó ser 5.

Aplicación de K-Means: Se entrenó el modelo de K-Means con el número de clusters óptimo.

Análisis de Clusters: Se visualizaron los clusters en un gráfico de dispersión para entender las características de cada grupo, basándose en el Ingreso Anual y el Spending Score. Se identificaron segmentos de clientes como:

Clientes de alto gasto y altos ingresos: El grupo más valioso.

Clientes de bajo gasto y bajos ingresos: Oportunidad para estrategias de crecimiento.

Clientes de alto gasto y bajos ingresos: Posiblemente clientes jóvenes o estudiantes.

Y otros segmentos intermedios.

✍️ Conclusión
Este proyecto de clustering demostró ser efectivo para segmentar a los clientes del centro comercial. Los resultados proporcionan información valiosa para diseñar estrategias de marketing específicas para cada grupo, lo que puede llevar a un aumento en la lealtad y los ingresos del cliente.
