# Proyecto de Procesamiento de Imágenes

## Descripción
Este proyecto implementa diferentes técnicas de procesamiento de imágenes utilizando Python y OpenCV. Incluye transformaciones como la negativa de una imagen y la umbralización, entre otras.

## Tecnologías Utilizadas
- Python
- OpenCV
- NumPy
- Jupyter Notebook

## Requisitos
Antes de ejecutar el proyecto, asegúrate de tener instaladas las siguientes dependencias:

```bash
pip install opencv-python numpy jupyter
```

## Uso
1. Clona el repositorio:

   ```bash
   git clone https://github.com/tuusuario/procesamiento-imagenes.git
   ```

2. Accede al directorio del proyecto:

   ```bash
   cd procesamiento-imagenes
   ```

3. Abre Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Ejecuta el archivo `proyecto.ipynb` para ver las transformaciones aplicadas a las imágenes.

## Funcionalidades
- Carga de imágenes en diferentes formatos.
- Aplicación de transformaciones como:
  - Negativo de una imagen.
  - Umbralización.
- Visualización de resultados en Jupyter Notebook.

## Ejemplo de Uso
### Aplicar Negativo a una Imagen
```python
import cv2
import numpy as np
import matplotlib.pyplot as plt

# Cargar imagen
display = cv2.imread('imagen.jpg', cv2.IMREAD_GRAYSCALE)

# Aplicar transformación negativa
negativo = 255 - display

# Mostrar resultado
plt.subplot(1, 2, 1)
plt.title('Imagen Original')
plt.imshow(display, cmap='gray')
plt.subplot(1, 2, 2)
plt.title('Imagen Negativa')
plt.imshow(negativo, cmap='gray')
plt.show()
```

## Contribuciones
Si deseas contribuir a este proyecto, por favor abre un issue o envía un pull request.

## Autor
Abraham Martinez Hernandez

