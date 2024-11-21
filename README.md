# Mango Dress Detection App

Este proyecto es una aplicación móvil desarrollada con **Flutter** que utiliza un modelo de IA para clasificar imágenes de vestidos de Mango. La aplicación permite a los usuarios cargar imágenes desde la galería o tomar fotos directamente con la cámara para identificar si una prenda es un "Mango Dress". El modelo utilizado fue entrenado con **Teachable Machine** y luego exportado a **TensorFlow Lite** para su integración en la aplicación.

## Funcionalidades

- **Carga de imágenes desde la cámara o la galería**: Los usuarios pueden tomar una foto con la cámara del dispositivo o seleccionar una imagen desde la galería.
- **Clasificación de imágenes**: El modelo clasifica la imagen seleccionada en categorías como "Mango Dress" o "No Mango Dress".
- **Precisión**: Muestra la etiqueta predicha junto con un porcentaje de precisión basado en la confianza del modelo.
- **Interfaz sencilla**: Una interfaz amigable que permite realizar predicciones fácilmente.

## Tecnologías Utilizadas

- **Flutter**: Framework utilizado para el desarrollo de la aplicación móvil.
- **TensorFlow Lite**: Para cargar y ejecutar el modelo de IA entrenado en el dispositivo móvil.
- **Teachable Machine**: Herramienta utilizada para entrenar el modelo de clasificación de imágenes.

## Instalación

1. Clona este repositorio en tu máquina local:
   ```bash
   git clone https://github.com/tu_usuario/mango-dress-detection.git
