Cardiotocology - Cardiotocología

### Descripcion de los datos
La cardiotocografía es una técnica médica utilizada para monitorear la salud fetal durante el embarazo y el parto. Consiste en la medición simultánea de la frecuencia cardíaca fetal y las contracciones uterinas de la madre. Esto se realiza mediante un dispositivo llamado cardiotocógrafo, que registra gráficamente ambas señales.

El objetivo principal de la cardiotocografía es evaluar la vitalidad del feto y detectar posibles signos de sufrimiento fetal durante el trabajo de parto. La frecuencia cardíaca fetal y los patrones de contracción uterina proporcionan información importante sobre la oxigenación y el bienestar del bebé en el útero materno.

Este monitoreo es especialmente crucial durante el parto, ya que ayuda a los profesionales médicos a tomar decisiones informadas sobre la necesidad de intervenciones para garantizar la seguridad tanto de la madre como del bebé.

### Detalle de el .csv
 Los CTGs también fueron clasificados por tres obstetras expertos y se asignó una etiqueta de clasificación de consenso a cada uno de ellos. La clasificación fue tanto con respecto a un patrón morfológico (A, B, C...) como a un estado fetal (N, S, P). Por lo tanto, el conjunto de datos se puede utilizar tanto para experimentos de 10 clases como de 3 clases.

### ESTADO FETAL
 N: Normal. Esto podría indicar que el estado fetal se considera normal durante el monitoreo, lo que significa que la frecuencia cardíaca fetal y las contracciones uterinas están dentro de los rangos esperados y no se observan signos de sufrimiento fetal.

S: Sospechoso o Sufriente. Esta etiqueta podría indicar que se observan ciertos signos o patrones en el monitoreo que sugieren que el feto podría estar experimentando algún grado de estrés o sufrimiento, lo que puede requerir una atención médica adicional.

P: Patológico. Esto podría indicar que se observan anormalidades graves o preocupantes en el monitoreo que sugieren un riesgo significativo para la salud fetal, lo que puede requerir intervención médica inmediata.

### DICCIONARIO DE DATOS
FileName: El nombre del archivo o registro donde se registraron los datos. Esta columna podría contener cadenas de texto que identifican de manera única cada registro.

Date: La fecha en la que se realizó el registro o la medición. Esta columna generalmente contendrá fechas en un formato específico, lo que permite realizar análisis de series temporales.

SegFile: Es posible que represente un archivo o segmento específico dentro de un registro más grande. Esta columna podría proporcionar información adicional sobre la segmentación de los datos, como la duración o la ubicación dentro del registro.

b, e: Estos podrían representar marcas de tiempo inicial y final dentro del registro. Proporcionan información sobre la duración o el intervalo de tiempo cubierto por cada registro o segmento.

LBE, LB, AC, FM, UC: Estas columnas contienen mediciones relacionadas con la cardiotocografía fetal, como la frecuencia cardíaca fetal basal, la línea de base de la frecuencia cardíaca fetal, aceleraciones de la frecuencia cardíaca fetal, movimientos fetales y contracciones uterinas, respectivamente.

ASTV, MSTV, ALTV, MLTV: Estas columnas representan características de la variabilidad de la frecuencia cardíaca fetal, como la amplitud y la duración de las variaciones a corto y largo plazo.

DL, DS, DP, DR, Width: Parámetros relacionados con las contracciones uterinas, como la duración, la separación, la pendiente, la amplitud y el ancho.

Min, Max, Mode, Mean, Median, Variance: Estas columnas contienen estadísticas descriptivas de las mediciones de frecuencia cardíaca fetal y contracciones uterinas, como el valor mínimo, máximo, la moda, la media, la mediana y la varianza.

Nmax, Nzeros: Estas columnas representan el número máximo de aceleraciones por minuto y el número de ceros durante la señal de frecuencia cardíaca fetal, respectivamente.

Mode: Esta columna podría representar la moda de la frecuencia cardíaca fetal.

Tendency: Esta columna podría representar una posible tendencia en los datos de frecuencia cardíaca fetal.

A, B, C, D, E, AD, DE, LD, FS, SUSP: Estas columnas contienen etiquetas o códigos relacionados con la clasificación de los datos por expertos obstetras.

CLASS: Una etiqueta de clasificación general.

NSP: Otra etiqueta de clasificación, posiblemente relacionada con el estado fetal (Normal, Sospechoso, Patológico), como se discutió anteriormente.