# Acne_Detector


## ¿Qué es el acné?
El acné es una condición visible en la piel que puede variar en cantidad, tamaño y distribución. En muchos casos, el seguimiento de la evolución del acné se realiza de forma visual, comparando fotografías tomadas en distintos momentos. Sin embargo, este proceso puede ser subjetivo, ya que depende de la observación manual de la persona que analiza las imágenes.

El problema que busca resolver este proyecto es apoyar el análisis visual de imágenes faciales mediante un modelo de visión artificial capaz de detectar zonas donde aparece acné. El sistema no reemplaza la valoración médica profesional, pero puede funcionar como una herramienta de apoyo para identificar regiones afectadas, generar evidencia visual y facilitar el seguimiento de cambios en la piel a lo largo del tiempo.

## Modelo 

En una aplicación real, este modelo podría implementarse en una clínica dermatológica, consultorio médico, farmacia dermatológica o incluso en una aplicación móvil de monitoreo de la piel. El usuario las zonas especificas de piel a una cámara o cargaría una imagen y el sistema procesaría la imagen para detectar automáticamente las zonas con posible presencia de acné.

## Ejecución del código 

Para poder ejecutar el código es necesario tener una cuenta en google colab.

Los pasos a seguir son: 

1. Abrir el archivo del notebook: Acne_det_.ipynb
2. Abrirlo en Google Colab.

Recomendación: Activa la GPU para mejorar el rendimiento del entrenamiento y evitar retardos del CPU, debes de ir a Entorno de ejecución → Cambiar tipo de entorno de ejecución → GPU

3. Ejecutar todas las celdas del notebook: Entorno de ejecución → Ejecutar todo
4. Al ejecutar podras ver que se realiza lo siguiente: 
   - Instalación de librerías necesarias.
   - Descarga del dataset.
   - Preparación de los datos.
   - Entrenamiento del modelo YOLO.
   - Generación del modelo entrenado.
   - Pruebas de detección.
   - Visualización de resultados con bounding boxes.

Es importante que para ver distintos resultados se modifique el numero mostrado en la ultima linea la cual tiene por default el numero dos:

res[2].show()


## Notas 

Los documentos utilizados son generados en el mismo código, por lo tanto no es necesario hacer descargas extenas, solo se debe de tener en cuenta que al perder la conexión estos archivos no apareceran. 

<img src="evidencias/resultado_1.jpg" width="500">
<img src="evidencias/resultado_2.jpg" width="500">
