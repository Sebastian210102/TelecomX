# 📉 Análisis de Evasión de Clientes (Churn) - TelecomX

Este proyecto tiene como objetivo analizar los factores que influyen en la evasión de clientes (churn) dentro de una empresa de telecomunicaciones, utilizando un enfoque de análisis exploratorio de datos (EDA). El estudio se desarrolló en un notebook de Jupyter, combinando limpieza de datos, visualizaciones e insights accionables.

## 📁 Contenido del Proyecto

- `TelecomX_con_informe.ipynb`: Notebook completo con el análisis, visualizaciones e informe final incluido.
- `dataset.csv`: Dataset original utilizado (no incluido aquí, asegúrate de cargar el tuyo si lo necesitas).
- `README.md`: Documento descriptivo del proyecto.

## 🎯 Objetivo

Identificar los patrones que llevan a los clientes a abandonar el servicio, con el fin de proponer estrategias que permitan a la empresa:

- Disminuir la tasa de churn.
- Detectar a tiempo a los clientes en riesgo.
- Mejorar la retención a través de estrategias basadas en datos.

## 🧹 Limpieza y Procesamiento

- Manejo de valores nulos y conversión de tipos de datos.
- Codificación de variables categóricas.
- Generación de variables como `tenure`, `TotalCharges`, etc.
- Filtrado y segmentación de usuarios para análisis específicos.

## 📊 Análisis Exploratorio

Se analizaron variables clave como:

- `Tenure`: Clientes con menos tiempo en la empresa tienden a irse más rápido.
- `MonthlyCharges`: Altos costos mensuales se relacionan con mayor churn.
- `PaymentMethod`: Métodos automáticos como tarjetas se asocian a mayor evasión.
- `Services`: Clientes con menos servicios contratados suelen irse antes.

Se utilizaron visualizaciones como histogramas, gráficos de barras y boxplots para detectar patrones.

## 🧠 Principales Insights

- La antigüedad del cliente es uno de los factores más determinantes.
- Clientes con gastos altos y poco valor percibido tienden a irse.
- El método de pago influye: tarjetas automáticas tienen más churn.
- Usuarios con servicios mínimos son menos fieles.

## 💡 Recomendaciones

- Programas de fidelización temprana.
- Ofrecer paquetes integrales de servicios.
- Revisar la experiencia en métodos de pago automáticos.
- Foco en soporte a clientes de alto valor.
- Desarrollar modelos predictivos para actuar antes de la fuga.

## 🚀 Tecnologías Utilizadas

- Python (Pandas, Matplotlib, Seaborn, NumPy)
- Jupyter Notebook
- Visualización de datos
- Análisis exploratorio (EDA)

## 📌 Cómo Ejecutar

1. Clona este repositorio.
2. Asegúrate de tener Jupyter Notebook y dependencias instaladas.
3. Abre `TelecomX_con_informe.ipynb` y ejecuta las celdas en orden.
4. Carga el dataset original si no está incluido.

```bash
pip install pandas matplotlib seaborn jupyter
