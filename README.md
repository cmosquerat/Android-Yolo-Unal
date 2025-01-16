


# Universidad Nacional de Colombia - Sede Manizales
## GCPDS

### Modelos de Detección y Segmentación en Entornos Móviles Android

Este repositorio contiene implementaciones y modelos optimizados para detección y segmentación de objetos utilizando **TFLite** en dispositivos Android. 

---

## ¿Qué es TFLite?

TensorFlow Lite (TFLite) es un framework ligero diseñado para ejecutar modelos de aprendizaje automático en dispositivos móviles y embebidos con recursos limitados. Es ideal para implementar modelos eficientes con baja latencia en aplicaciones Android.

---

## Estructura del Repositorio

```
.
├── LICENSE
├── NOTICE
├── README.md
├── TransformToTFLITE/
│   ├── transformar.ipynb
├── tree.py
├── YOLOv10-Object-Detector-Android-Tflite/
│   ├── app/
│   │   ├── build.gradle.kts
│   │   ├── proguard-rules.pro
│   │   └── src/
│   │       ├── androidTest/
│   │       ├── main/
│   │       └── test/
│   ├── build.gradle.kts
│   ├── gradle/
│   │   ├── libs.versions.toml
│   │   └── wrapper/
│   │       ├── gradle-wrapper.jar
│   │       └── gradle-wrapper.properties
├── YOLOv8-Image-Classification-Android-Tflite/
│   ├── app/
│   │   ├── build.gradle.kts
│   │   ├── proguard-rules.pro
│   │   └── src/
│   │       ├── androidTest/
│   │       ├── main/
│   │       └── test/
├── YOLOv8-Instance-Segmentation-Android-Tflite/
│   ├── app/
│   │   ├── build.gradle.kts
│   │   ├── proguard-rules.pro
│   │   └── src/
│   │       ├── androidTest/
│   │       ├── main/
│   │       └── test/
├── YOLOv9-Object-Detector-Android-Tflite/
│   ├── app/
│   │   ├── build.gradle.kts
│   │   ├── proguard-rules.pro
│   │   └── src/
│   │       ├── androidTest/
│   │       ├── main/
│   │       └── test/
└── YOLOv8-Object-Detector-Android-Tflite/
    ├── app/
    │   ├── build.gradle.kts
    │   ├── proguard-rules.pro
    │   └── src/
    │       ├── androidTest/
    │       ├── main/
    │       └── test/
```

---

## ¿Cómo Ejecutar los Modelos?

### Requisitos Previos

1. **Instalar Android Studio:**
   - Descarga [Android Studio](https://developer.android.com/studio) e instálalo en tu sistema.
2. **Clonar el Repositorio:**
   ```bash
   git clone https://github.com/tu-repositorio.git
   ```
3. **Abrir el Proyecto:**
   - Abre Android Studio y selecciona `File > Open` para cargar el directorio del modelo deseado (por ejemplo, `YOLOv8-Object-Detector-Android-Tflite/`).

---

### Instrucciones para Conversión a TFLite

El directorio `TransformToTFLITE` contiene un notebook (`transformar.ipynb`) con las instrucciones detalladas para convertir modelos preentrenados a formato TFLite. Sigue estos pasos para realizar la conversión:

1. **Abrir el Notebook**:
   Ejecuta el archivo `transformar.ipynb` usando Jupyter Notebook o Google Colab.

2. **Sigue los Pasos en el Notebook**:
   El notebook incluye:
   - Preparación de modelos.
   - Optimización para dispositivos móviles.
   - Exportación a formato TFLite.

---
