## Gráfico de contorno (dot plot)

*	**Origen:**

El concepto de líneas de contorno fue desarrollado en el  __siglo XVIII__ por  __Hachure y más tarde fue utilizado por Charles Hutton__ en trabajos científicos y matemáticos, sentando las bases para lo que se convertiría en el gráfico de contorno.

*	**Descripción/Funcionamiento:**

Los gráficos de contorno se utilizan típicamente __para representar datos cuantitativos, donde los ejes X e Y pueden representar el espacio o rangos de una variable independiente, y las líneas de contorno representan una tercera variable cuantitativa__.

*	**Ejemploso de Aplicación:**

+	Meteorología: Para representar datos del clima donde se muestran líneas de igual temperatura o precipitación.
+	Geografía y Cartografía: Para demostrar la altitud en los mapas.
+	Ingeniería y Física: Para visualizar la distribución del estrés en un objeto.
+	Economía: Para mostrar diferentes niveles de distribución de datos económicos geográficamente o en un espacio de mercancías.
+	Imagen Médica: Para representar diferentes densidades en escaneos como las resonancias magnéticas.

*	**Limitaciones:**

Las principales limitaciones de los gráficos de contorno dependen de la naturaleza de los datos:

+ __Los datos deben ser numéricos y continuos sobre el área__.
+ La interpolación entre puntos de datos puede llevar a inexactitudes si los datos no son lo suficientemente densos.
+ Puede ser __difícil de interpretar en áreas donde hay un cambio rápido en el gradiente__ o hay picos y valles, ya que las líneas de contorno pueden volverse demasiado densas.

*	**Tipo de Datos Representables con Gráficos de Contorno**

Un gráfico de contorno, o "contour plot", se utiliza __para representar datos tridimensionales en dos dimensiones__. Este tipo de gráfico es especialmente útil para explorar cómo dos variables independientes afectan a una variable dependiente.

+ Datos Cuantitativos: __Los contour plots representan comúnmente datos cuantitativos__. Las variables en los ejes X e Y suelen ser cuantitativas y representan dimensiones espaciales o rangos de variables independientes. La variable Z, representada por las líneas de contorno, también es cuantitativa y generalmente representa la intensidad o magnitud de una tercera variable.
+ Datos Cualitativos: __No son comúnmente representados con gráficos de contorno__, ya que las líneas de contorno implican un gradiente y continuidad que no se aplica bien a las variables cualitativas.


*	**Estructura de los Datos para Gráficos de Contorno**

+	Rejilla de Datos: Los datos generalmente deben estar en formato de grilla, donde tienes un valor Z para cada combinación de X e Y en un rango específico. Esto se conoce como datos "estructurados en grilla".
+	Puntos de Datos Interpolados: Si los datos no están en una grilla regular, pueden necesitar ser interpolados para crear una superficie continua que se pueda representar con líneas de contorno.


*	**Limitaciones en Cuanto a Datos**

+	Continuidad: Los gráficos de contorno asumen que entre los puntos de datos hay una transición suave y continua. Si los datos son discretos o hay saltos bruscos en los valores, el gráfico de contorno podría ser engañoso.
+	Densidad de Datos: Necesitas suficientes datos para cubrir el área de interés. Si los datos son demasiado escasos, la interpolación puede ser inexacta. Por otro lado, si los datos son demasiado densos, el gráfico puede volverse confuso con demasiadas líneas de contorno.
´+	Interpolación: La precisión de un gráfico de contorno depende de la calidad de la interpolación entre los puntos de datos. Malas interpolaciones pueden llevar a interpretaciones erróneas de los datos.


*	**Visualización realizada**

+	Conjunto de datos utilizado: Se utiliza el __conjunto de datos de predicciones meteorológicas paras las 12:00 horas del días 2024/04/22__, obtenible desde página de OpenData de ECWMF https://www.ecmwf.int/en/forecasts/datasets/open-data .El script Jupiter Notebook para descargar los datos y realizar la visualizacion está disponible en este mismo repositorio en el fichero "presion_viento_850hPa.ipynb" en esta misma carpeta.
+	Resultado de la visualización: Se encuentra disponible en el fichero "presion_viento_850hPa.png" y se reproduce aquí:

![image](https://github.com/jmmonterog/pec02_visualizacion_datos/assets/103445965/6924b772-4c7c-4b3c-b258-50ef52283673)

