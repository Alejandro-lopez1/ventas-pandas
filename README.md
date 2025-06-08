# 📊 Análisis de Ventas con Pandas en Google Colab

Este proyecto realiza un análisis de datos de ventas utilizando Python y la biblioteca Pandas. El objetivo es extraer insights útiles de un archivo Excel con registros de ventas y dejar todo listo para su visualización, exportación o publicación.

---

## ⚙️ Tecnologías utilizadas

- Python 3
- Pandas
- Google Colab
- Excel / LibreOffice Calc

---

## 📥 Datos de entrada

El archivo Excel debe contener columnas como:

- `Fecha`
- `Producto`
- `Cantidad`
- `Precio Unitario`
- `Total Venta`
- `Costo Unitario`
- `Total Costo`
- `Ganancia`

---

## 🧠 Insights generados

- ✅ Producto más vendido (por cantidad)
- ✅ Producto que más facturó
- ✅ Producto más rentable (ganancia neta)
- ✅ Total de ganancias por fecha
- ✅ Agrupaciones por producto con sumatorias
- ✅ Formateo en miles para mejorar legibilidad

---

## 📤 Exportación de resultados

El DataFrame modificado puede exportarse a Excel con:

```python
df.to_excel("ventas_modificado.xlsx", index=False)

