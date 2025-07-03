# 📊 Análisis de Evasión de Clientes en empresa de Telecomunicaciones

## 🔹 Descripción del Proyecto
Este proyecto presenta un **análisis de datos exploratorio (EDA)** sobre un conjunto de datos de una empresa de telecomunicaciones.  
El objetivo principal es identificar los **factores y características clave** de los clientes que abandonan el servicio (Churn), para **proponer estrategias de retención basadas en evidencia**.

A través de la limpieza de datos, la transformación de variables y la visualización, este análisis busca responder a la pregunta:  
**¿Por qué se van los clientes y cómo podemos evitarlo?**

---

## 📋 Tabla de Contenidos
- [Tecnologías Utilizadas](#️-tecnologías-utilizadas)
- [Estructura del Análisis](#-estructura-del-análisis)
- [Hallazgos Clave](#-hallazgos-clave)
- [Conclusiones y Recomendaciones](#-conclusiones-y-recomendaciones)
- [Cómo Utilizar este Proyecto](#cómo-utilizar-este-proyecto)

---

## 🛠️ Tecnologías Utilizadas

### Lenguaje de Programación
- Python 3.x

### Bibliotecas de Análisis
- **Pandas**: Manipulación y limpieza de datos.
- **NumPy**: Operaciones numéricas.

### Bibliotecas de Visualización
- **Matplotlib**: Creación de gráficos base.
- **Seaborn**: Visualizaciones estadísticas avanzadas.

---

## 🔬 Estructura del Análisis

### 1. Limpieza y Tratamiento de Datos
- Corrección de tipos de datos inconsistentes (ej. facturas totales como texto).
- Eliminación de filas con datos críticos faltantes (224 registros sin información de Churn).
- Estandarización de nombres de columnas para mayor legibilidad.

### 2. Ingeniería de Características y Transformación
- Creación de una nueva variable `Factura_Diaria` para normalizar los datos de facturación.
- Codificación de variables categóricas (ej. "Yes"/"No") a formato numérico (1/0).

### 3. Análisis Exploratorio Visual (EDA)
- Análisis de la distribución general de la tasa de Churn (**26.5%**).
- Gráficos comparativos (barras y cajas) cruzando Churn con variables demográficas, de servicio y numéricas.

---

## 🔑 Hallazgos Clave

El análisis reveló un perfil definido del cliente con **alto riesgo de evasión**.  
Los factores más correlacionados con el Churn fueron:

- **Tipo de Contrato**:  
  Los contratos *Mes a mes* presentan la mayor tasa de evasión.
  
- **Antigüedad**:  
  Los clientes nuevos (con pocos meses de servicio) son más propensos a cancelar.

- **Servicios Contratados**:  
  La *Fibra Óptica* y la **ausencia de Soporte Técnico** están asociados a mayor Churn.

- **Facturación**:  
  Una **factura mensual elevada** y el **pago mediante Cheque Electrónico** son indicadores de riesgo.

---

## 💡 Conclusiones y Recomendaciones

La evasión no es aleatoria: responde a **factores identificables y modificables**.  
Se recomienda a la empresa:

- **Incentivar Contratos Anuales**  
  → Ofrecer descuentos para migrar de mensual a anual.

- **Mejorar la Experiencia de Nuevos Clientes**  
  → Implementar onboarding y seguimiento durante los primeros 3-6 meses.

- **Revisar el Servicio de Fibra Óptica**  
  → Investigar problemas de precio o calidad asociados.

- **Optimizar Métodos de Pago**  
  → Promover la migración desde *Cheque Electrónico* a métodos automáticos.

- **Promover el Soporte Técnico**  
  → Incluirlo en paquetes de bienvenida o enfocados en clientes de alto riesgo.

---

## 🚀 Cómo Utilizar este Proyecto
1. Clona este repositorio.
2. Asegúrate de tener Python 3.x y las bibliotecas requeridas instaladas.
3. Ejecuta el notebook principal para ver el análisis completo.
4. Personaliza y adapta los insights a tus propios conjuntos de datos o casos de negocio.

---
