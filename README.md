# 🚀 PythonIA_Convulent - API de Detección de Objetos con COCO

![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat&logo=fastapi)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv)
![COCO](https://img.shields.io/badge/Dataset-COCO-FF4F40?style=flat)

> *"Detección de objetos en tiempo real con modelo pre-entrenado SSD MobileNet V2"*

## 🌟 **Características Clave**
- 🖼️ Detección de objetos usando el dataset **COCO**
- ⚡ API REST con **FastAPI** para integración sencilla
- 🚦 Soporte para CORS (ideal para frontends)
- 📦 Modelo pre-entrenado **SSD MobileNet V2** listo para producción

## 🛠️ **Stack Tecnológico Exacto**
```mermaid
graph LR
    A[FastAPI] --> B(Endpoint /predict)
    C[TensorFlow] --> D(SSD MobileNet V2)
    E[OpenCV] --> F(Procesamiento de imágenes)
    B --> D
    D --> F
```
