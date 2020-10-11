# Detectar-errores-en-imagenes
Comparar dos imágenes, tomando una de ellas como referencia, para detectar alguna variación entre ambas. 

![Ejemplo](https://github.com/cabustillo13/Detectar-errores-en-piezas/blob/master/Resultados/resultadosFisuras0_1.png)

Con este programa se busca calcular el índice de similitud estructural (SSIM) entre una imagen patrón o de referencia vrs una imagen a analizar.

Una de las aplicaciones planteadas es la detección de fisuras en algún elemento de máquina (ej: debido a fatiga, desgaste, etc). Se obtuvieron buenos resultados.
Sí realmente lo aplicaramos a una pieza 3D, deberíamos realizar este proceso desde distintas vistas (lo cual puede llevar a no determinar algún cambio estructural en puntos ciegos), para eso directamente se podría ser un escaneado de la imagen 3D respecto a su archivo CAD, .STL con el cuál fue fabricado. 
*Por ejemplo, ésto se utiliza para realizar mantenimiento predictivo en las grandes brocas de perforación en la minería.*

Otra aplicación es evaluar si la etiqueta de una botella fue colocada dentro del lugar que corresponde. En los resultados se puede observar que aún con rotaciones 
muy pequeñas de la etiqueta (5 grados de inclinación), este método logra detectar la variación.
*Por ejemplo, ésto se utiliza en empaquetadoras de cerveza comercial para corroborar que su etiqueta se encuentre dentros los parámetros establecidos.*

Imágenes obtenidas de Pixabay. La licencia ampara: gratis para usos comerciales y no es necesario reconocimiento.
