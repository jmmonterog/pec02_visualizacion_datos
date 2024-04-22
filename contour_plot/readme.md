## Gráfico de contorno (dot plot)

*	**Origen:**

El concepto de líneas de contorno fue desarrollado en el siglo XVIII por Hachure y más tarde fue utilizado por Charles Hutton en trabajos científicos y matemáticos, sentando las bases para lo que se convertiría en el gráfico de contorno.

*	**Descripción/Funcionamiento:**

Los gráficos de contorno se utilizan típicamente para representar datos cuantitativos, donde los ejes X e Y pueden representar el espacio o rangos de una variable independiente, y las líneas de contorno representan una tercera variable cuantitativa.

*	**Ejemploso de Aplicación:**

+	Meteorología: Para representar datos del clima donde se muestran líneas de igual temperatura o precipitación.
+	Geografía y Cartografía: Para demostrar la altitud en los mapas.
+	Ingeniería y Física: Para visualizar la distribución del estrés en un objeto.
+	Economía: Para mostrar diferentes niveles de distribución de datos económicos geográficamente o en un espacio de mercancías.
+	Imagen Médica: Para representar diferentes densidades en escaneos como las resonancias magnéticas.

*	**Limitaciones:**

Las principales limitaciones de los gráficos de contorno dependen de la naturaleza de los datos:

+ Los datos deben ser numéricos y continuos sobre el área.
+ La interpolación entre puntos de datos puede llevar a inexactitudes si los datos no son lo suficientemente densos.
+ Puede ser difícil de interpretar en áreas donde hay un cambio rápido en el gradiente o hay picos y valles, ya que las líneas de contorno pueden volverse demasiado densas.

*	**Tipo de Datos Representables con Gráficos de Contorno**

Un gráfico de contorno, o "contour plot", se utiliza para representar datos tridimensionales en dos dimensiones. Este tipo de gráfico es especialmente útil para explorar cómo dos variables independientes afectan a una variable dependiente.

+ Datos Cuantitativos: Los contour plots representan comúnmente datos cuantitativos. Las variables en los ejes X e Y suelen ser cuantitativas y representan dimensiones espaciales o rangos de variables independientes. La variable Z, representada por las líneas de contorno, también es cuantitativa y generalmente representa la intensidad o magnitud de una tercera variable.
+ Datos Cualitativos: No son comúnmente representados con gráficos de contorno, ya que las líneas de contorno implican un gradiente y continuidad que no se aplica bien a las variables cualitativas.


*	**Estructura de los Datos para Gráficos de Contorno**

+	Rejilla de Datos: Los datos generalmente deben estar en formato de grilla, donde tienes un valor Z para cada combinación de X e Y en un rango específico. Esto se conoce como datos "estructurados en grilla".
+	Puntos de Datos Interpolados: Si los datos no están en una grilla regular, pueden necesitar ser interpolados para crear una superficie continua que se pueda representar con líneas de contorno.


*	**Limitaciones en Cuanto a Datos**

+	Continuidad: Los gráficos de contorno asumen que entre los puntos de datos hay una transición suave y continua. Si los datos son discretos o hay saltos bruscos en los valores, el gráfico de contorno podría ser engañoso.
+	Densidad de Datos: Necesitas suficientes datos para cubrir el área de interés. Si los datos son demasiado escasos, la interpolación puede ser inexacta. Por otro lado, si los datos son demasiado densos, el gráfico puede volverse confuso con demasiadas líneas de contorno.
´+	Interpolación: La precisión de un gráfico de contorno depende de la calidad de la interpolación entre los puntos de datos. Malas interpolaciones pueden llevar a interpretaciones erróneas de los datos.


*	**Visualización realizada**

+	Conjunto de datos utilizado: Se utiliza el conjunto de datos "Activaciones_niveles_Plan_Nacional_Temperaturas_Estivales_2022.csv", obtenible desde página de OpenData de ECWMF https://www.ecmwf.int/en/forecasts/datasets/open-data .El conjunto de datos descargado y el Jupiter Notebook para realizar la visualizacion están disponiblse en este mismo repositorio en los ficheros "presion_viento_850hPa.jpnb" "presion_viento_850hPa.ipynb" respectivamente dentro de esta misma carpeta de este repositorio.
+	Resultado de la visualización: Se encuentra disponible en el ichero Agua_Embalsada_Comunidades_Autonomas_2024.png y se reproduce aquí:

![image](https://github.com/jmmonterog/pec02_visualizacion_datos/assets/103445965/fcb01ae4-e102-41e1-9c66-f2a5a311aec4)