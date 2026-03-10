# tienda
challenge de tiendas
Análisis de Ventas y Recomendación Estratégica para el Sr. Juan
Resumen del Proyecto
Este proyecto tiene como objetivo analizar el rendimiento operativo y comercial de cuatro tiendas (Tienda 1, Tienda 2, Tienda 3 y Tienda 4) de un mismo propietario, el Sr. Juan. El análisis se enfoca en métricas clave para la toma de decisiones, con el fin de proporcionar una recomendación fundamentada sobre cuál de estas tiendas debería vender. Se cubren aspectos como la facturación total, el desempeño por categoría de producto, la satisfacción del cliente, los productos más y menos vendidos, y la eficiencia en los costos de envío. Además, se incluye un análisis geoespacial de las ventas.

Objetivos
Calcular la facturación total consolidada de todas las tiendas.
Identificar las categorías de productos con mayor y menor volumen de ventas.
Determinar la calificación promedio de los clientes para cada tienda.
Identificar los productos más y menos vendidos por tienda.
Analizar el costo de envío promedio por tienda.
Generar visualizaciones para facilitar la comprensión de los datos.
Proporcionar una recomendación clara y justificada al Sr. Juan sobre qué tienda vender.
Realizar un análisis geoespacial para entender la distribución de ventas.
Fuentes de Datos
Los datos se cargan desde cuatro archivos CSV alojados en GitHub, cada uno correspondiente a una tienda diferente:

tienda_1.csv
tienda_2.csv
tienda_3.csv
tienda_4.csv
Cada archivo contiene información detallada sobre las transacciones de ventas, incluyendo Producto, Categoría del Producto, Precio, Costo de envío, Fecha de Compra, Vendedor, Lugar de Compra, Calificación, Método de pago, Cantidad de cuotas, lat (latitud) y lon (longitud).

Análisis Realizado
El análisis se estructuró en las siguientes secciones:

Facturación Total: Cálculo de la suma total de ingresos de todas las tiendas combinadas.
Ventas por Categoría: Agrupamiento y suma de la facturación por Categoría del Producto para identificar las categorías más rentables.
Calificación Promedio por Tienda: Cálculo del promedio de la columna Calificación para cada tienda individual, evaluando la satisfacción del cliente.
Productos Más y Menos Vendidos: Identificación de los productos con mayor y menor frecuencia de venta en cada tienda, utilizando value_counts().
Costo de Envío Promedio por Tienda: Cálculo del costo promedio de envío para cada establecimiento, para evaluar la eficiencia logística.
Análisis Geoespacial: Creación de gráficos de dispersión y mapas de calor utilizando las coordenadas lat y lon para visualizar la distribución geográfica de las ventas y la concentración de la actividad comercial.
Visualizaciones Clave
Se generaron los siguientes gráficos para complementar el análisis:

Gráfico de barras de Facturación Total por Categoría de Producto: Muestra las categorías que más contribuyen a los ingresos.
Gráfico de barras de Calificación Promedio por Tienda: Compara la satisfacción del cliente entre las tiendas.
Gráfico de barras de Costo de Envío Promedio por Tienda: Visualiza la eficiencia en los costos de envío de cada establecimiento.
Distribución Geográfica General de las Ventas (por Facturación): Un scatter plot que muestra todos los puntos de venta, con el tamaño y color de los puntos indicando la facturación.
Distribución Geográfica de las Ventas por Tienda (por Facturación): Un scatter plot que diferencia las ventas por tienda, permitiendo observar su huella geográfica.
Mapa de Calor de la Densidad de Ventas (Geográfica): Un KDE plot que resalta las áreas con mayor concentración de transacciones.
Conclusión y Recomendación
Tras un análisis exhaustivo de todas las métricas operativas y comerciales, se recomienda al Sr. Juan que, si su objetivo principal es maximizar la eficiencia operativa y mantener una buena base de clientes con el menor costo de envío, la Tienda 4 podría ser la opción más atractiva para vender.

Justificación:

Eficiencia en Costos de Envío: La Tienda 4 registra el costo de envío promedio más bajo (23,459.46 COP) entre todas las tiendas. Esta eficiencia es una ventaja operativa significativa que puede impactar directamente la rentabilidad a largo plazo.
Satisfacción del Cliente Sólida: Aunque la Tienda 3 tiene una calificación promedio de clientes marginalmente superior (4.05 vs 4.00), la Tienda 4 mantiene una calificación muy cercana al promedio más alto, lo que indica que no hay un compromiso significativo en la satisfacción del cliente.
Facturación y Productos: Las diferencias en la facturación por categoría o en los productos más y menos vendidos no presentan desventajas críticas que hagan inviable la Tienda 4. Las tendencias son variadas entre las tiendas, y el factor del costo de envío es un diferenciador clave en los gastos de operación.
En resumen, la Tienda 4 ofrece un equilibrio óptimo entre la satisfacción del cliente y una ventaja competitiva en los costos operativos, posicionándola como la elección más lógica para una eventual venta.
