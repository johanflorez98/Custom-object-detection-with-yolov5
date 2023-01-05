# Detector de partes de computadores de escritorio

Se presenta un detector de partes de un computador de escritorio haciendo uso del modelo YoloV5, el cual tiene la capacidad de detectar entre 4 clases, correspondientes a: "CPU", "Monitor", "Mouse" y "Teclado".

Se creó un [dataset](https://drive.google.com/drive/folders/1_qojEljAS2p7xvLYGjeYkKy-V745dskx?usp=sharing) personalizado con imágenes de computadores de escritorio, conformado por 69 imágenes en total, 40 imágenes para entrenamiento, 19 para validación y 10 para prueba. Cada una de las respectivas imágenes está conformada por al menos 1 de las clases mencionadas.
Para el etiquetado de las imágenes se utilizó el programa Web "Make Sense", ya que es muy amigable graficamente para dicho trabajo. Una vez realizado el mencionado proceso se exportaron las etiquetas en formato de YoloV5.

El cuaderno se encuentra [disponible aquí](https://colab.research.google.com/drive/1kX0iE1duFAJ62ve2sqogtb0JZuh-0IcP?usp=sharing), dado su tamaño.
