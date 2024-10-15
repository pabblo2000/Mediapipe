
# FaceMesh con Mediapipe

Este directorio contiene ejemplos de cómo utilizar **Mediapipe** para la malla facial (FaceMesh) utilizando dos modelos de deep learning: **Face Landmark** y **Face Detection**.

## Modelos utilizados

1. **Face Detection**: Este modelo se utiliza para detectar la presencia de un rostro en la imagen o en el video, generando un bounding box inicial.
2. **Face Landmark**: Una vez detectado el rostro, este modelo se utiliza para predecir 468 puntos de referencia en la cara, generando una malla facial densa.

Estos dos modelos trabajan en conjunto para realizar la detección precisa de la cara y mapear los puntos clave en tiempo real, lo que permite aplicaciones avanzadas como el seguimiento facial y la animación.

## Requisitos

Asegúrate de tener instalada la librería de Mediapipe y OpenCV para la ejecución de los ejemplos.

Instala ambas librerías usando pip:

```bash
pip install mediapipe opencv-python
```

## Uso

Los scripts incluidos en este directorio permiten realizar la detección de la malla facial utilizando Mediapipe. Puedes ejecutarlos utilizando un archivo de imagen o utilizando la cámara web para detectar la malla facial en tiempo real.

### Ejecución con imagen:

```bash
python facemesh_image.py --input imagen.jpg
```

### Ejecución en tiempo real con la cámara:

```bash
python facemesh_video.py
```

## Descripción de los scripts

- **facemesh_image.py**: Realiza la detección de la malla facial en una imagen estática.
- **facemesh_video.py**: Realiza la detección de la malla facial en tiempo real utilizando la cámara del dispositivo.

## Referencias

- [Documentación de Mediapipe](https://mediapipe.dev/)
- [Repositorio de GitHub de Mediapipe](https://github.com/google/mediapipe)

