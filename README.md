# 📊 Proyecto: Análisis de Evasión de Clientes (Churn) - Telecom X

👤 Autor: **Samuel Pérez**

---

## 🚀 Descripción

Este proyecto tiene como objetivo analizar la **evasión de clientes (Churn)** en la empresa ficticia **Telecom X**.  
La alta tasa de cancelaciones representa un reto estratégico, y mediante este análisis se busca **identificar patrones y factores clave que influyen en la pérdida de clientes**.

El trabajo incluye la limpieza, transformación y exploración de datos, generando insights que puedan servir como base para **modelos predictivos y estrategias de retención**.

---

## 🛠️ Tecnologías utilizadas

- **Python 3**
- **Pandas** → Manipulación de datos  
- **Matplotlib & Seaborn** → Visualización  
- **Google Colab** → Desarrollo del proyecto  

---

## 📌 Estructura del proyecto

1. **Importación y limpieza de datos**
   - Carga de datos desde archivo JSON.
   - Tratamiento de valores nulos, duplicados e inconsistencias.
   - Normalización de nombres de columnas y creación de nuevas variables.

2. **Transformación de datos**
   - Conversión de variables categóricas y binarias.
   - Creación de la variable `cargo_diario`.

3. **Análisis Exploratorio de Datos (EDA)**
   - Estadísticas descriptivas.
   - Distribución de evasión (churn).
   - Relación de churn con variables categóricas y numéricas.
   - Visualizaciones para identificar patrones.

4. **Conclusiones y recomendaciones**
   - Insights sobre contratos, métodos de pago y cargos mensuales.
   - Estrategias sugeridas para reducir la evasión.

---

## 📈 Resultados principales

- Los clientes con contrato **mensual** tienen mayor probabilidad de cancelar.  
- El pago con **“Electronic check”** está fuertemente asociado a la evasión.  
- Clientes con **menos meses de antigüedad** y **cargos más altos** son los más propensos a cancelar.  

---

## 📎 Cómo ejecutar

1. Clonar este repositorio:
   ```bash
   git clone https://github.com/tuusuario/telecomx-churn.git
   cd telecomx-churn
