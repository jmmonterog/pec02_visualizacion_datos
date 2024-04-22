## Cartogramas (Cartograms)

*	**Origen:**

Los cartogramas tienen un origen histórico que se remonta a principios del siglo XX, siendo utilizados inicialmente por economistas y geógrafos para representar información estadística de manera espacial y visual. El cartograma como técnica fue popularizado por el geógrafo alemán Waldo R. Tobler en la década de 1960, quien desarrolló métodos sistemáticos para su creación.

*	**Descripción/Funcionamiento:**

Un cartograma es un tipo de mapa temático en el que las áreas geográficas, como países o regiones, se redimensionan de acuerdo con una variable específica que se desea representar. Esta variable puede ser cualquier dato cuantitativo, como población, producto Interno Bruto (PIB), número de incidentes de un evento, etc. En un cartograma, la representación geográfica tradicional se distorsiona para reflejar la importancia relativa de la variable seleccionada en lugar de la superficie terrestre real.

*	**Funcionamiento:**

+ Selección de la Variable: El primer paso en la creación de un cartograma es elegir la variable que afectará el tamaño de las áreas en el mapa.
+ Redimensionamiento de Áreas: Las áreas geográficas se redimensionan proporcionalmente según la magnitud de la variable seleccionada, lo cual puede llevar a una distorsión significativa de las formas geográficas habituales.
+ Ajuste de la Distorsión: En algunos casos, se intenta mantener cierta contigüidad y una mínima distorsión de las fronteras originales para que las áreas sigan siendo reconocibles.
+ Visualización: Finalmente, el cartograma se visualiza con diferentes colores o tonos para indicar la magnitud de la variable de interés, facilitando la comparación visual entre las regiones.

*	**Ejemplos de Aplicación:**

+	Demografía: Visualización de la población por país o región, donde cada área se redimensiona proporcionalmente a su población total.
+	Economía: Representación del PIB por país, mostrando la economía relativa de diferentes naciones.
+ Salud Pública: Mapas de prevalencia de enfermedades, donde las áreas se ajustan según el número de casos registrados o la tasa de incidencia.
+	Elecciones: En análisis electoral, donde los cartogramas pueden mostrar el número de votos o escaños en diferentes regiones, reflejando la importancia política en lugar del tamaño geográfico.
	Medio Ambiente: Cartogramas de emisiones de carbono o uso de recursos naturales, destacando los mayores contribuyentes o consumidores en comparación con otros.

*	**Ventajas y Limitaciones:**

*	**Ventajas:**

+	Los cartogramas proporcionan una representación visual impactante de las diferencias cuantitativas, facilitando la identificación de tendencias y anomalías.
+	Son especialmente útiles para evitar la sobreinterpretación de áreas geográficamente grandes que tienen valores relativamente pequeños de la variable de interés.

*	**Limitaciones:**

+	La distorsión de las formas geográficas puede hacer que las áreas sean difíciles de reconocer, especialmente si la transformación es extrema.
+	Puede ser complicado mantener la contigüidad y la proporcionalidad, especialmente en áreas con muchas pequeñas entidades geográficas.
+	Los cartogramas son una herramienta poderosa en visualización de datos que, cuando se utilizan correctamente, pueden revelar patrones ocultos y proporcionar insights profundos sobre distribuciones complejas de datos.

*	**Tipo de Datos Representables con Cartogramas**

Los cartogramas son más efectivos cuando se utilizan para representar datos cuantitativos. Estos datos deben ser medibles y expresables en forma numérica, ya que el propósito principal del cartograma es redimensionar áreas geográficas basadas en valores numéricos que reflejan una magnitud o frecuencia de un fenómeno particular. Algunos ejemplos de datos cuantitativos incluyen población, ingresos, tasas de enfermedades, producción económica, entre otros.

*	**Estructura de los Datos para Cartogramas**

Para crear un cartograma, los datos deben estar estructurados de manera que cada unidad geográfica (como un país, estado, o condado) esté asociada con un valor numérico específico de la variable que se desea visualizar. Idealmente, la estructura de los datos incluirá:

+	Identificador Geográfico: Nombre o código que identifica de manera única cada área geográfica.
+	Variable Cuantitativa: Valor numérico que se utilizará para redimensionar cada área en el cartograma.

