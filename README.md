# Perros y Gatos - Clasificación de Imágenes con TensorFlow.js

Este proyecto utiliza TensorFlow.js para clasificar imágenes en tiempo real a través de la cámara web. La aplicación identifica si la imagen mostrada es de un **Perro** o un **Gato**.

## Tecnologías utilizadas

- HTML
- CSS (Bootstrap 5)
- JavaScript
- TensorFlow.js

## Requisitos

- Navegador web moderno que soporte TensorFlow.js y la API de la cámara web.
- Conexión a internet para cargar los recursos de TensorFlow.js y Bootstrap.

## Instalación

1. Clona este repositorio en tu máquina local:

   ```bash
   git clone https://github.com/tu_usuario/perros-y-gatos.git
Abre el archivo index.html en tu navegador.

Uso
Al abrir la página, la cámara web se iniciará automáticamente y mostrará la imagen capturada.

La aplicación procesará la imagen y mostrará si es un Perro o un Gato.

Puedes cambiar entre las cámaras (delantera o trasera) haciendo clic en el botón Cambiar cámara.

Estructura del Proyecto
index.html: Archivo principal con la interfaz y lógica de la aplicación.

model.json: El modelo de TensorFlow.js que se carga para hacer las predicciones (asegúrate de tener este archivo en la misma carpeta que index.html).
