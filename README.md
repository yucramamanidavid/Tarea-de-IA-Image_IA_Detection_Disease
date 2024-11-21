# Mango Dress Detection App

## Descripción del Proyecto

Este proyecto es una **aplicación móvil** desarrollada utilizando **Flutter** que permite a los usuarios identificar si una prenda de vestir corresponde a un "Mango Dress". La aplicación utiliza un **modelo de clasificación de imágenes** entrenado en **Teachable Machine** y exportado a **TensorFlow Lite** para su ejecución eficiente en dispositivos móviles.

### Características principales:

- **Clasificación de imagen**: La aplicación permite tomar una foto o seleccionar una imagen desde la galería y clasificarla en dos categorías: "Mango Dress" o "No Mango Dress".
- **Modelo de IA**: El modelo entrenado utiliza técnicas de **Deep Learning** para identificar prendas de vestir específicas basadas en imágenes de entrenamiento proporcionadas.
- **Interfaz de usuario amigable**: La aplicación tiene una interfaz sencilla y clara para el usuario, permitiéndole interactuar de forma fácil y rápida.
- **Precisión del modelo**: Después de cada clasificación, la aplicación muestra la categoría de la prenda con un porcentaje que refleja la certeza del modelo.

## Tecnologías Utilizadas

### 1. **Flutter**:
   Flutter es un framework de desarrollo móvil de Google, utilizado para crear aplicaciones nativas de alto rendimiento para **Android** e **iOS**. Este proyecto fue desarrollado en Flutter utilizando **Dart** como lenguaje de programación.

### 2. **Teachable Machine**:
   Teachable Machine es una herramienta de Google que permite crear modelos de aprendizaje automático de manera sencilla sin necesidad de experiencia previa en machine learning. Se usó para entrenar el modelo de clasificación de imágenes.

### 3. **TensorFlow Lite**:
   TensorFlow Lite es una versión optimizada de TensorFlow diseñada para ejecutar modelos de machine learning en dispositivos móviles de manera eficiente. El modelo entrenado en Teachable Machine se exportó a un formato **TensorFlow Lite (.tflite)** para integrarlo en la aplicación móvil.

### 4. **Dart**:
   Dart es el lenguaje de programación utilizado en Flutter para implementar la lógica de la aplicación, interactuar con el modelo y gestionar la interfaz de usuario.

## Instalación

### 1. Clonar el repositorio

Primero, clona el repositorio del proyecto en tu máquina local con el siguiente comando:

```bash
git clone https://github.com/tu_usuario/mango-dress-detection.git
