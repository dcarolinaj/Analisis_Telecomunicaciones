EN English

## 📡Telecommunications Analysis

### 🎯 Objective

The objective of this project is to understand customer behaviour and analyse how customers use mobile services, particularly calls and messages. The analysis also aims to classify customers into different segments to help optimise commercial offerings, improve the customer experience, and understand how usage patterns vary across different user groups.

### 📂 Datasets Used

- plans.csv: Plan catalogue containing current plan information, including prices, included minutes, included GB, and additional usage costs.
- users_latam.csv: Customer information including age, city, churn status, registration date, and subscribed plan.
- usage.csv: Customer activity data, including calls (duration) and messages (length).

### 🛠️ Tools & Technologies

- Jupyter Notebook
- Python: Pandas, NumPy, Seaborn, Matplotlib

### 💼 Business Questions

- Which customer segments show higher or lower usage of calls and messages?
- Which users present outliers that could indicate unusual behaviour, potential fraud, or data-recording errors?
- How does service usage vary according to customer age and subscription plan?
- What patterns could help design better plans, optimise commercial offerings, and improve customer satisfaction?

### 🔄 Project Workflow

📥 Data Loading & Exploration: Load and explore the plans, users_latam, and usage datasets.

🔎 Data Quality Assessment: Identify missing values, detect sentinel values, and review dates outside expected ranges.

🧹 Data Cleaning: Replace sentinel values, convert dates to appropriate formats, and impute or flag missing values according to defined rules.

📊 Summary Statistics: Analyse key descriptive statistics for categorical and numerical variables.

📈 Visualisation & Outlier Analysis: Create histograms and boxplots to explore distributions and identify potential outliers.

👥 Customer Segmentation: Create customer segments based on clearly defined rules and visualise their proportions using countplots.

💡 Executive Insights: Develop business conclusions and commercial recommendations based on the findings from the analysis.

### 🚀 How to Reproduce the Analysis

- Open GitHub.
- Review the README for an overview of the project and analysis.
- Open the Analisis_telecomunicaciones repository.
- Open S7-Project-ConnectaTel.ipynb.
- Run the notebook cells in order.


</p>

<br>

<hr>

<br>

<h2>🇪🇸 Español</h2>

## 📡 Analisis de Telecomunicaciones

### 🎯Objetivo:

El objetivo del proyecto es entender el **comportamiento de los clientes**, entender cómo usan los servicios móviles especialmente en llamadas y mensajes, clasificar los clientes por **segmentos** con el fin de optimizar la oferta comercial, mejorar la experiencia del usuario y ver cómo varía entre diferentes grupos de usuarios.


### 📂 Datasets utilizados:

•	plans.csv: Catálogo de planes con sus precios y beneficios. Los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra).

•	users_latam.csv:  Información de cada cliente: edad, ciudad, churn, fecha de registro, plan contratado.

•	usage.csv: Actividad generada por los usuarios: llamadas (duración), mensajes (longitud).


### 🛠️ Herramientas  utilizadas:

•	Jupyter Notebook

•	Python: pandas, numpy, seaborn, matplotlib


### 💼 Preguntas del negocio:

•	¿Qué segmentos de clientes muestran **mayor o menor uso** de llamadas y mensajes?

•	¿Qué usuarios presentan **valores atípicos** que puedan indicar comportamientos inusuales, fraude o errores de registro?

•	¿Cómo varía el uso según la **edad** y el **tipo de plan contratado**?

•	¿Qué patrones pueden ayudar a **diseñar mejores planes**, optimizar la oferta y mejorar la satisfacción del cliente?


### 🔄 Flujo general del proyecto:

📥 Cargar y explorer: Cargar y explorar plans, users_latam, usage

🔎 Identificación de problemas de calidad: Contar nulos, detectar sentinels, revisar fechas fuera de rango.

🧹 Limpieza básica: Reemplazar sentinels, convertir fechas, imputar o marcar NA según reglas.

📊 Summary statistics: Revisar las medidas clave en variables categóricas y numéricas.

📈 Visualización & outliers: Creación de histogramas y boxplots.

👥 Segmentación: Crear segmentaciones basadas en reglas claras; visualizar proporciones con countplots.

💡Insight ejecutivo: Redactar conclusiones y recomendaciones comerciales basadas en los pasos anteriores.


### 🚀 Cómo reproducir el análisis:

•	Abre GitHub. 

•	Ver README para obtener información general del análisis.

•	Abrir el repositorio ‘Analisis_telecomunicaciones’

•	Abril  **S7-Project-ConnectaTel.ipynb**

•	Ejecuta las celdas en orden
