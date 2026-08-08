# Analisis_Telecomunicaciones

**Objetivo:**

El objetivo del proyecto es entender el **comportamiento de los clientes**, entender cómo usan los servicios móviles especialmente en llamadas y mensajes, clasificar los clientes por **segmentos** con el fin de optimizar la oferta comercial, mejorar la experiencia del usuario y ver cómo varía entre diferentes grupos de usuarios.


**Datasets utilizados:**

•	plans.csv: Catálogo de planes con sus precios y beneficios. Los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra).

•	users_latam.csv:  Información de cada cliente: edad, ciudad, churn, fecha de registro, plan contratado.

•	usage.csv: Actividad generada por los usuarios: llamadas (duración), mensajes (longitud).


**Herramientas  utilizadas:** 

•	Jupyter Notebook

•	Python: pandas, numpy, seaborn, matplotlib


**Preguntas del negocio:**

•	¿Qué segmentos de clientes muestran **mayor o menor uso** de llamadas y mensajes?

•	¿Qué usuarios presentan **valores atípicos** que puedan indicar comportamientos inusuales, fraude o errores de registro?

•	¿Cómo varía el uso según la **edad** y el **tipo de plan contratado**?

•	¿Qué patrones pueden ayudar a **diseñar mejores planes**, optimizar la oferta y mejorar la satisfacción del cliente?


**Flujo general del proyecto:**

•	Cargar y explorer: Cargar y explorar plans, users_latam, usage

•	Identificación de problemas de calidad: Contar nulos, detectar sentinels, revisar fechas fuera de rango.

•	Limpieza básica: Reemplazar sentinels, convertir fechas, imputar o marcar NA según reglas.

•	Summary statistics: Revisar las medidas clave en variables categóricas y numéricas.

•	Visualización & outliers: Creación de histogramas y boxplots.

•	Segmentación: Crear segmentaciones basadas en reglas claras; visualizar proporciones con countplots.

•	Insight ejecutivo: Redactar conclusiones y recomendaciones comerciales basadas en los pasos anteriores.


**Cómo reproducir el análisis:**

•	Abre GitHub. 

•	Ver README para obtener información general del análisis.

•	Abrir el repositorio ‘Analisis_telecomunicaciones’

•	Abril  **S7-Project-ConnectaTel.ipynb**

•	Ejecuta las celdas en orden
