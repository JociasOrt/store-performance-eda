# 📊 store-performance-eda

Análisis exploratorio de datos (EDA) centrado en el rendimiento de una cadena retail de 4 sucursales. Este proyecto utiliza Python para transformar datos brutos en insights estratégicos que facilitan la toma de decisiones ejecutivas.

## 🎯 Objetivo del Proyecto
El Sr. João busca financiamiento para un nuevo emprendimiento y debe decidir de qué sucursal desinvertir. Este análisis evalúa las tiendas basándose en tres pilares críticos:
* **Desempeño Financiero:** Ingresos brutos totales por cada sucursal.
* **Satisfacción del Cliente:** Calificaciones promedio recolectadas de los consumidores.
* **Eficiencia Logística:** Distribución y comportamiento de los costos de envío.

## 📈 Hallazgos Destacados
1. **Facturación:** La **Tienda 2** lidera en ingresos, mientras que la **Tienda 4** y la **Tienda (1)** presentan los niveles de facturación más bajos del grupo.
2. **Opinión del Cliente:** Existe una oportunidad de mejora en la **Tienda 4**, la cual registra la valoración promedio más baja, impactando directamente en la retención de usuarios.
3. **Estandarización Logística:** Mediante un análisis de dispersión, confirmamos que todas las tiendas operan bajo el mismo modelo de cobro de envío (proporcional al precio del producto). Esto indica que ninguna tienda tiene una ineficiencia logística aislada; el comportamiento es uniforme en toda la cadena.

> **💡 Conclusión Estratégica:** Se recomienda proceder con la venta de la **Tienda 4**. Es la sucursal con menor facturación y menor nivel de satisfacción al cliente, sin presentar ventajas operativas en costos de envío que justifiquen su permanencia frente a las otras opciones.

## 🛠️ Herramientas utilizadas
* **Lenguaje:** Python 3
* **Librerías principales:** * `Pandas` (Procesamiento y limpieza)
    * `Matplotlib` & `Seaborn` (Visualización estadística avanzada)
* **Entorno:** Jupyter Notebook / Google Colab

## 🚀 Cómo utilizar este repositorio
1. **Clonar el proyecto:** ```bash
   git clone [https://github.com/JociasOrt/store-performance-eda.git](https://github.com/JociasOrt/store-performance-eda.git)
