## 🚕 Resumen del Proyecto: Optimización de Ingresos para Taxistas

---

### 🎯 Objetivo Principal

Desarrollar un modelo de Machine Learning para recomendar la **mejor zona de recogida (Taxi Zone)** en Manhattan - NYC para cada **franja horaria** y **día de la semana**, con el fin de **maximizar la ganancia esperada** del taxista.

---

### 📊 Unidad de Análisis y Agregación de Datos

* **Unidad:** Cada fila representa una combinación única de **Zona – Hora – Día**.
* **Variables de Entrada (Features):**
    * **Temporal:** Franja Horaria (0-23) y Día de la Semana (1-7), derivadas de `tpep_pickup_datetime`.
* **Variable Objetivo (Target):**
    Zona en que se posiciona el taxi para maximizar revenue. pickup_zone.

---

### 🤖 Modelo y Recomendación

* **Modelo:** Regresión (Random Forest / XGBoost) entrenado para predecir el **Revenue Esperado** en función de la Zona, Hora y Día.
* **Flujo de Recomendación:**
    1.  Para la hora actual, el modelo predice el **Revenue Esperado** en todas las zonas.
    2.  Se recomienda al taxista la **Zona con el mayor Revenue Esperado**. 

---

### ✨ Resultado Esperado

* **Reducción del tiempo de inactividad** del taxista.
* **Aumento directo del ingreso promedio** por hora trabajada.

![alt](attachment:image.png)
![image-2.png](attachment:image-2.png)