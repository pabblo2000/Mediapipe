
# Face Detection con Mediapipe

Este directorio contiene ejemplos de cómo utilizar **Mediapipe** para la detección de rostros en tiempo real o en imágenes estáticas.

## Requisitos

Asegúrate de tener instalada la librería de Mediapipe y OpenCV para la ejecución de los ejemplos.

Instala ambas librerías usando pip:

```bash
pip install mediapipe opencv-python
```

## Uso

Los scripts incluidos en este directorio permiten realizar la detección de rostros utilizando Mediapipe. Puedes ejecutarlos utilizando un archivo de imagen o utilizando la cámara web para detectar rostros en tiempo real.

### Ejecución con imagen:

```bash
python face_detection_image.py --input imagen.jpg
```

### Ejecución en tiempo real con la cámara:

```bash
python face_detection_video.py
```

## Descripción de los scripts

- **face_detection_image.py**: Realiza la detección de rostros en una imagen estática.
- **face_detection_video.py**: Realiza la detección de rostros en tiempo real utilizando la cámara del dispositivo.

## Referencias

- [Documentación de Mediapipe](https://mediapipe.dev/)
- [Repositorio de GitHub de Mediapipe](https://github.com/google/mediapipe)

