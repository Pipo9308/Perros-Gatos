# Perros y Gatos - Clasificación de Imágenes con TensorFlow.js

Este proyecto utiliza TensorFlow.js para clasificar imágenes en tiempo real a través de la cámara web. La aplicación identifica si la imagen mostrada es de un **Perro** o un **Gato**.

## Tecnologías utilizadas

- HTML
- CSS (Bootstrap 5)
- JavaScript
- TensorFlow.js
- Python (para el servidor local)
- Ngrok (para exponer el servidor a dispositivos móviles)

## Requisitos

- Navegador web moderno que soporte TensorFlow.js y la API de la cámara web.
- Python 3.x instalado en tu máquina.
- Conexión a internet para cargar los recursos de TensorFlow.js y Bootstrap.
- Ngrok para exponer el servidor local a internet.

## Instalación

### 1. Clonar el repositorio

Clona este repositorio en tu máquina local:

```bash
git clone https://github.com/tu_usuario/perros-y-gatos.git

```
2. Iniciar un servidor local con Python
Este proyecto utiliza un servidor básico de Python para servir el archivo index.html.

Si tienes Python 3.x instalado, puedes iniciar el servidor con el siguiente comando dentro de la carpeta del proyecto:

bash
Copiar
Editar
```bash
python -m http.server 8000
```
Este comando iniciará un servidor en http://localhost:8000.

3. Exponer el servidor con Ngrok (Opcional, para dispositivos móviles)
Para probar la aplicación en un dispositivo móvil, necesitas exponer el servidor local a través de Ngrok. Sigue estos pasos:

Descarga e instala Ngrok.

Una vez instalado, abre una terminal y navega a la carpeta donde está instalado Ngrok.

Ejecuta el siguiente comando para exponer el servidor local a internet:

```bash
ngrok http 8000
```

