## Diagramas de matriz de puntos (Dot matrix plot)

*	**Origen:**

El Dot Matrix Chart no tiene un origen específico documentado en la literatura de visualización de datos como otros gráficos más tradicionales, pero es un tipo de visualización que ha ganado popularidad con el aumento del uso de herramientas de visualización de datos computarizadas como Tableau, que facilitan la creación de visualizaciones personalizadas y complejas.

*	**Descripción/Funcionamiento:**

Un Dot Matrix Chart es una forma de visualización que utiliza una matriz de puntos para representar datos cuantitativos. Cada punto en el gráfico representa una unidad, cantidad o frecuencia de ocurrencia de un evento, y los puntos se organizan en filas y columnas para formar una matriz. La posición de los puntos puede ser arbitraria o puede representar categorías específicas en los ejes horizontal y vertical.

*	**Funcionamiento:**

+ Datos: Este gráfico es adecuado para visualizar datos cuantitativos donde cada punto representa una unidad de medida.
+	Estructura de la Matriz: Los puntos se organizan típicamente en un número fijo de columnas, mientras que el número de filas varía según la cantidad de datos a representar. Alternativamente, las filas pueden representar categorías y las columnas subcategorías o grupos.
+	Visualización: Los puntos pueden ser de un color uniforme o codificados por color para representar diferentes categorías o grupos dentro de los datos.

*	**Ejemplos de Aplicación:**

+	Análisis de Frecuencia: Utilizar un Dot Matrix Chart para mostrar la frecuencia de ocurrencias de varios eventos, donde cada punto representa una ocurrencia individual.
+	Distribución de Productos: En un contexto de negocios, usar un Dot Matrix Chart para representar la distribución de ventas de productos en diferentes regiones.
+	Encuestas y Respuestas: Visualizar respuestas de encuestas, donde cada punto puede representar un porcentaje de respuestas para cada pregunta dividido por categorías de respuestas.
+	Comparación de Categorías: Comparar el tamaño de diferentes categorías, como la cantidad de empleados en diferentes departamentos de una empresa.


*	**Ventajas y Limitaciones:**

*	**Ventajas:**

+	Claridad Visual: Ofrece una representación clara y directa que puede ser más intuitiva que otros tipos de gráficos para mostrar cantidades discretas.
+	Comparación Fácil: Facilita la comparación visual entre categorías o grupos.

*	**Limitaciones:**

+	Escalabilidad: Puede volverse visualmente complicado y menos efectivo cuando se trata con grandes volúmenes de datos, ya que la cantidad de puntos puede ser abrumadora.
+	Menos Detalles: No es ideal para mostrar tendencias o patrones complejos dentro de los datos.


*	**Tipo de Datos Representables con Cartogramas**

Un Dot Matrix Chart es ideal para representar datos cuantitativos, donde cada punto en la matriz puede representar una unidad o un incremento de la variable cuantitativa. Este tipo de gráfico muestra efectivamente la frecuencia o la cantidad de ocurrencias, haciendo que sea adecuado para datos que son contables y discretos.

+ Datos Cualitativos:

Aunque el Dot Matrix Chart se utiliza principalmente para datos cuantitativos, también puede ser empleado para representar datos cualitativos de forma que se cuantifiquen o clasifiquen, como en el caso de categorías que pueden ser contadas (por ejemplo, número de individuos que prefieren cierto tipo de producto).


*	**Estructura de los Datos para Cartogramas**

Para que un Dot Matrix Chart funcione efectivamente, los datos deben estar estructurados de manera que permitan la representación en forma de matriz. Idealmente, deberíamos tener:

+	Una variable categórica: Esta variable define las filas del gráfico. Cada categoría se representa en una fila diferente.
+	Una variable cuantitativa: Esta variable proporciona el número de puntos que se deben dibujar. Cada unidad de esta variable se representa como un punto en la matriz.


*	**Limitaciones en Cuanto a Datos**

Cantidad de Datos:

+	Mínima: No hay un mínimo estricto, pero un Dot Matrix Chart tiene más sentido cuando hay suficientes datos para visualizar patrones o comparaciones significativas.
+	Máxima: Aunque no hay un máximo técnico, la eficacia del gráfico disminuye con un número muy grande de puntos. Esto se debe a que una cantidad excesiva de puntos puede hacer que el gráfico sea difícil de interpretar y visualmente caótico.

*	**Visualización realizada**

+	Conjunto de datos utilizado: Se utiliza el conjunto de datos "Activaciones_niveles_Plan_Nacional_Temperaturas_Estivales_2022.csv", obtenible desde  https://www.sanidad.gob.es/ciudadanos/saludAmbLaboral/planAltasTemp/2022/home.htm .  El conjunto de datos descargado está disponible en este mismo repositorio en el fichero "Agua_Embalsada_Comunidades_Autonomas_2024.csv" dentro de esta misma carpeta de este repositorio.
+	Resultado de la visualización: Se encuentra disponible en el ichero cartograma.png y se reproduce aquí:

  ![image](https://github.com/jmmonterog/pec02_visualizacion_datos/assets/103445965/7d4dda1f-7215-46cf-8a9d-847dcc744595)

