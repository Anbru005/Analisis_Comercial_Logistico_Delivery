## 📊 Análisis Comercial y Logístico de Delivery (Excel End-to-End)

🔗 **[Haz clic aquí para interactuar con el Dashboard en vivo en OneDrive](PEGA_AQUÍ_TU_ENLACE)**

El objetivo de este proyecto es analizar de principio a fin el flujo operativo de una aplicación de delivery, integrando datos de tráfico (funnel), transacciones (pedidos) y puntos de venta. A través de este análisis, se busca identificar cuellos de botella logísticos, evaluar la rentabilidad por canal y proponer estrategias basadas en datos para impulsar las conversiones.

## 🛠️ Arquitectura y Procesamiento de Datos

* **ETL con Power Query:** Limpieza, normalización y unión (merge/append) de más de [NÚMERO] registros provenientes de las tablas `Datos_tiendas`, `Funnel_tiendas` y `Pedidos_tiendas`. Se crearon columnas calculadas críticas como tiempos de entrega, márgenes netos y ratios de conversión.
* **Modelado Relacional (Power Pivot):** Diseño de un modelo de datos estructurado. Desarrollo de medidas DAX para KPIs dinámicos, incluyendo Ventas Totales, Margen, Ticket Promedio y Porcentaje de Cumplimiento Logístico (entregas < 45 min).
* **Automatización (VBA):** Se implementaron macros orientadas a [DESCRIBE BREVEMENTE QUÉ AUTOMATIZASTE, ej: la actualización automática de las fuentes de datos y limpieza de filtros con un solo clic], optimizando el tiempo de reporte.

## 📈 Dashboard y Métricas Clave

*(Arrastra aquí la imagen de tu dashboard principal)*
![Dashboard Principal](dashboard_principal.png)

* **Desempeño Comercial:** La tienda [NOMBRE] lidera la facturación, mientras que el canal [CANAL] presenta la mejor tasa de conversión histórica.
* **Logística y Cumplimiento:** El [PORCENTAJE]% de los pedidos superan el plazo comprometido de 45 minutos, concentrándose principalmente en la región [REGIÓN]. Existe una correlación [POSITIVA/NEGATIVA] entre el monto de venta y el tiempo promedio de entrega.
* **Rentabilidad y Fidelización:** Los meses de [MESES] mostraron un alto volumen de ventas pero una caída en el margen debido a [RAZÓN]. La combinación de la categoría [CATEGORÍA] con el canal [CANAL] genera la mayor rentabilidad del negocio.

## 💡 Conclusiones y Recomendaciones

* **Crecimiento Comercial:** Se recomienda replicar la estrategia de la tienda [TIENDA TOP] en las sucursales de [TIENDAS BAJAS] para estandarizar la tasa de conversión.
* **Optimización Logística:** Es crítico reestructurar las rutas o ampliar la flota en [ZONA PROBLEMÁTICA] para reducir la tasa de entregas tardías, lo cual está impactando directamente en las devoluciones de la categoría [CATEGORÍA].
* **Impacto del Flujo de Datos:** La automatización de este pipeline en Excel demuestra que un flujo de datos estructurado reduce el tiempo operativo en un [X]% y permite transicionar de un análisis descriptivo a la toma de decisiones estratégicas.
