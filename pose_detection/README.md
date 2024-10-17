
# Mediapipe Pose Detection

Este directorio contiene ejemplos de cómo utilizar **Mediapipe** para la detección de poses en tiempo real o en imágenes estáticas.

## Modelos utilizados

Mediapipe Pose es un modelo avanzado que permite la detección y seguimiento del cuerpo humano utilizando puntos de referencia (landmarks) en tiempo real. Este modelo predice **33 puntos de referencia** en el cuerpo, que corresponden a diferentes articulaciones y partes del cuerpo como los hombros, codos, rodillas, etc.

## Requisitos

Asegúrate de tener instalada la librería de Mediapipe y OpenCV para la ejecución de los ejemplos.

Instala ambas librerías usando pip:

```bash
pip install mediapipe opencv-python
```

## Uso

Los scripts incluidos en este directorio permiten realizar la detección de poses utilizando Mediapipe. Puedes ejecutarlos utilizando un archivo de imagen o utilizando la cámara web para detectar poses en tiempo real.

### Ejecución con imagen:

```bash
python pose_image.py --input imagen.jpg
```

### Ejecución en tiempo real con la cámara:

```bash
python pose_video.py
```

## Descripción de los scripts

- **pose_image.py**: Realiza la detección de poses en una imagen estática.
- **pose_video.py**: Realiza la detección de poses en tiempo real utilizando la cámara del dispositivo.

## Referencias

- [Documentación de Mediapipe](https://mediapipe.dev/)
- [Repositorio de GitHub de Mediapipe](https://github.com/google/mediapipe)
