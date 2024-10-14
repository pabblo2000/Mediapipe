
# Hand Detection con Mediapipe

Este directorio contiene ejemplos de cómo utilizar **Mediapipe** para la detección de manos en tiempo real o en imágenes estáticas.

## Requisitos

Asegúrate de tener instalada la librería de Mediapipe y OpenCV para la ejecución de los ejemplos.

Instala ambas librerías usando pip:

```bash
pip install mediapipe opencv-python
```

## Uso

Los scripts incluidos en este directorio permiten realizar la detección de manos utilizando Mediapipe. Puedes ejecutarlos utilizando un archivo de imagen o utilizando la cámara web para detectar las manos en tiempo real.

### Ejecución con imagen:

```bash
python hand_detection_image.py --input imagen.jpg
```

### Ejecución en tiempo real con la cámara:

```bash
python hand_detection_video.py
```

## Descripción de los scripts

- **hand_detection_image.py**: Realiza la detección de manos en una imagen estática.
- **hand_detection_video.py**: Realiza la detección de manos en tiempo real utilizando la cámara del dispositivo.

## Referencias

- [Documentación de Mediapipe](https://mediapipe.dev/)
- [Repositorio de GitHub de Mediapipe](https://github.com/google/mediapipe)

