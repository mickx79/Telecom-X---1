
# Proyecto Telecom X: Análisis de Evasión de Clientes

## 📌 Descripción

Este proyecto forma parte del programa **Oracle Next Education (ONE) – Alura Latam**.
El objetivo fue analizar los factores que influyen en la **evasión de clientes (churn)** en la compañía ficticia **Telecom X**.

El análisis busca aportar **insights estratégicos** para futuros modelos predictivos y planes de retención de clientes.

---

## 🛠️ Tecnologías utilizadas

* **Python 3**
* **Pandas** (manipulación y limpieza de datos)
* **Matplotlib / Seaborn** (visualización de datos)
* **Jupyter Notebook** (desarrollo del análisis)

---

## 📂 Datos

* El dataset fue obtenido desde un **repositorio en GitHub** (Alura Latam) en formato **JSON**.
* Se utilizó el método `json_normalize` para aplanar la estructura del archivo.

### Procesamiento de datos:

* Verificación de duplicados y valores nulos (no se encontraron).
* Eliminación de strings vacíos (`" "`) que dificultaban la lectura.
* Conversión de la columna `Charges.Total` de **str** a **float**.
* Creación de la variable `Cuentas_Diarias`, basada en `Charges.Monthly`.
* No se normalizaron variables categóricas.

---

## 🔍 Análisis Exploratorio (EDA)

Se analizaron variables **numéricas y categóricas** para identificar patrones relacionados con el churn.

**Principales hallazgos:**

1. **Tenure:** El abandono es más frecuente en los **primeros meses** de contrato.
2. **Gasto mensual:** Los clientes con **menor facturación mensual** son los que más abandonan.
3. **Método de pago:** El **Electronic Check** está altamente asociado con el churn.
4. **Tipo de contrato:** Los contratos **mensuales** concentran la mayor tasa de evasión.

---

## 📊 Conclusiones

* Los **primeros meses de contrato** son críticos para la retención.
* Los clientes con **contratos flexibles** y **menor gasto mensual** presentan mayor probabilidad de abandonar.
* Los **métodos de pago automáticos** y los **contratos de mayor plazo** reducen la tasa de churn.

---

## 💡 Recomendaciones

* Mejorar el **onboarding** de los clientes en los primeros meses.
* Incentivar **contratos de largo plazo** con beneficios exclusivos.
* Promover métodos de pago más estables (tarjeta o débito automático).
* Diseñar planes de fidelización para clientes de bajo gasto mensual.

---

## 📎 Autores

Proyecto realizado por **Miqueas Córdoba** como parte de la formación en Data Science del programa **ONE – Alura Latam**.

