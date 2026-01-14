📊 TelecomX: Análisis de Evasión de Clientes (Churn)
Este proyecto realiza un análisis exhaustivo sobre el comportamiento de deserción de clientes en una empresa de telecomunicaciones. El objetivo es identificar patrones críticos que permitan a la organización tomar decisiones estratégicas para mejorar la retención.

🚀 Cómo ejecutar el proyecto
Clonar el repositorio: git clone https://github.com/tu-usuario/telecom-churn-analysis.git

Abrir en VS Code: Abre la carpeta del proyecto y asegúrate de tener instalada la extensión de Python y Jupyter.
Instalar Dependencias: Ejecuta el siguiente comando en la terminal:
**pip install pandas numpy matplotlib seaborn requests**

Ejecutar el script: Abre el archivo .py o .ipynb y haz clic en "Run".

🛠️ Tecnologías utilizadas
Python 3.x
Pandas: Para la manipulación y normalización de datos.
Seaborn & Matplotlib: Para la generación de visualizaciones estadísticas.

Requests: Para el consumo de datos desde fuentes externas (JSON).

📁 Estructura y Procesamiento de Datos
El proyecto sigue un flujo de trabajo de Ciencia de Datos estructurado:

Ingesta de Datos: Carga de un archivo JSON anidado desde una URL remota.
Limpieza de Datos:
Normalización de diccionarios anidados (customer, phone, account).
Tratamiento de valores nulos y cadenas de texto vacías ('').
Conversión de variables categóricas ("Yes"/"No") a formato binario (1/0).
Casteo de tipos de datos para cálculos financieros.

📈 Hallazgos Principales (Insights)
Tras el Análisis Exploratorio de Datos (EDA), se identificaron los siguientes puntos clave:
Tasa de Churn: Se sitúa en un 25.7%, lo que representa un área de mejora significativa.
Riesgo por Contrato: Los clientes con contrato "Month-to-month" presentan la mayor tasa de abandono.
Perfil Crítico: Clientes nuevos (menos de 12 meses) con cargos mensuales superiores a $70 USD tienen una alta probabilidad de fuga.
Método de Pago: El pago por "Electronic Check" está fuertemente correlacionado con la evasión.

📝 Conclusiones y Recomendaciones
El informe detallado incluido en el código sugiere estrategias como incentivar la migración a contratos anuales y crear programas de fidelización para clientes en su primer semestre de servicio.
