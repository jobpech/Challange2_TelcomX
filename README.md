# 📊 Análisis de Evasión de Clientes de Telecomunicaciones (TELECOMX)

## 1. Descripción

Este proyecto analiza la evasión de clientes (Churn) en una empresa de telecomunicaciones, con el objetivo de identificar patrones de abandono según variables demográficas, de servicio y financieras.
Se busca entender qué factores influyen más en la permanencia de los clientes y proponer posibles estrategias de retención.


## 2. Instrucciones del Proyecto TelecomX_LATAM Repositorio

Este repositorio contiene los archivos y recursos necesarios para el análisis de datos del proyecto TelecomX_LATAM.

Acceso a los documentos del análisis  (GitHub)
Enlace directo: [Repositorio](https://github.com/jobpech/Challange2_TelcomX)

![README](https://raw.githubusercontent.com/jobpech/Challange2_TelcomX/refs/heads/desarrollo/img/README.jpg)

### **Contenido del repositorio**

- **README.md**
Documento que contiene las instrucciones de uso y guía general del proyecto.

- **TelecomX_LATAM.ipynb**
Notebook de Google Colab con el análisis de datos realizado.

- **TelecomX_diccionario.json**
Diccionario de términos y definiciones utilizados en el proyecto.

- **TelecomX_Data.json**
Archivo JSON que contiene la base de datos utilizada para el análisis.

- **Img/**
Carpeta que contiene las imágenes utilizadas en el análisis y documentación.

### **Cómo utilizar este proyecto**

- Abra el archivo TelecomX_LATAM.ipynb en Google Colab.

- Asegúrese de cargar el archivo TelecomX_Data.json en el entorno de ejecución.

- Utilice TelecomX_diccionario.json como referencia para entender los términos técnicos.

- Consulte la carpeta /Img/ para ver las imágenes que complementan el análisis.

**Nota:** Para una mejor comprensión del proyecto, se recomienda leer primero este archivo **README.md** antes de abrir el Notebook.


## 3. Datos

**Fuente:** Datos internos de clientes de telecomunicaciones.

**Registros:** 7043

**Columnas:** 22, incluyendo:

**Churn:** si el cliente abandonó (0 = No, 1 = Sí)

**Contract:** tipo de contrato

**Charges.Monthly:** cobro mensual

**Charges.Total:** cobro acumulado

**Servicios contratados:** TechSupport, OnlineSecurity, DeviceProtection, StreamingTV, StreamingMovies

**Información demográfica:** gender, SeniorCitizen, Partner, Dependents

**Método de pago:** PaymentMethod, PaperlessBilling

## 4. Tecnologías utilizadas

Este proyecto de análisis de Churn de clientes fue desarrollado utilizando las siguientes tecnologías y herramientas:

**Lenguaje de programación**

**Python** → Lenguaje principal para el análisis de datos.

**Librerías para análisis y manipulación**

**Pandas** → Limpieza, manipulación y análisis de datos tabulares.

**NumPy** → Operaciones numéricas y manejo de arreglos.

**Visualización de datos**

**Matplotlib** → Gráficos básicos y personalización de visualizaciones.

**Seaborn** → Visualizaciones estadísticas (heatmaps, boxplots, countplots).

**Plotly** (opcional, si se utilizó) → Gráficos interactivos y dinámicos.

**Entorno de desarrollo**

**Google Colab** → Desarrollo iterativo, ejecución de código y visualización integrada.

**Control de versiones y documentación**

**Git & GitHub** → Control de versiones, colaboración y publicación del proyecto.

**Markdown** → Creación del README y documentación estructurada.


## 5. Objetivos

- Identificar variables y categorías asociadas a mayor riesgo de abandono.

- Visualizar patrones de Evasión - abandono de clientes (churn) según servicios y cargos.

- Generar insights que permitan diseñar estrategias de retención.


## 6. Metodología

**1. Limpieza y transformación de datos**

- Conversión de columnas numéricas y categóricas

- Manejo de valores faltantes o inconsistentes

**2. Análisis exploratorio**

- Distribución de churn por categoría (gráficos de barras)

- Comparación de cargos mensuales y totales por churn (boxplots)

- Correlaciones y mapa de calor de variables

**3. Visualización**

- Boxplots, barras y heatmaps para resumir patrones de abandono


## 7. Resultados / Insights

- **Contrato:** Clientes con Month-to-month tienen mayor Evasión (churn) (>40%).

- **Servicios adicionales:** Falta de TechSupport, OnlineSecurity o DeviceProtection se asocia a más abandono.

- **Cargos:**

  - Charges.Monthly altos → mayor riesgo de Evasión- abandono (Churn)

  - Charges.Total bajo → clientes recientes que abandonan rápido

- **Método de pago:** Clientes con Electronic check muestran mayor Evasión-bandono (churn) que pagos automáticos.

- **PaperlessBilling:** Usuarios de facturación electrónica presentan tendencia a mayor abandono.

## 8. Conclusiones y recomendaciones

- Incentivar contratos a largo plazo para reducir Evasión-Abandono (churn).

- Promover servicios adicionales que aumenten fidelidad permanencia.

- Revisar tarifas altas y ofrecer planes o descuentos para clientes con riesgo de abandono.

- Segmentar campañas de retención según método de pago y antigüedad del cliente.

## 9. Visualizaciones

- Gráficos incluidos en el notebook:

- Barras de Evasión (churn) por variable categórica
![barras](https://raw.githubusercontent.com/jobpech/Challange2_TelcomX/refs/heads/desarrollo/img/Evasion.png)

- Boxplots de Gasto total de servicio (Charges.Monthly) y Gasto  (Charges.Total) por churn
![box](https://raw.githubusercontent.com/jobpech/Challange2_TelcomX/refs/heads/desarrollo/img/totalgastado.png)

- Heatmap de categorías vs churn para visión global
![heatmap](https://raw.githubusercontent.com/jobpech/Challange2_TelcomX/refs/heads/desarrollo/img/mapa_correlaciones.png)
## 10. Licencia y Créditos

- Datos ficticios/internos para fines de análisis.

- Licencia: MIT (si aplicable)
- Autor: Job Rodolfo Pech Lara- Pagina personal :[jobpech.com](https://jobpech.com/)

## Agradecimientos

![one](https://www.oracle.com/a/ocom/img/rh03-one-logo-with-slogan-lad.png)

![ALURA](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTAEX-HY8btG6ccSdB_3oUIOg9QO1tRKnliIQ&s)

![ORACLE](https://upload.wikimedia.org/wikipedia/commons/thumb/5/50/Oracle_logo.svg/2560px-Oracle_logo.svg.png)