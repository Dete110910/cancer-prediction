# Predicción de lunares cancerígenos

Este proyecto se basa en un detector de lunares cacerígenos. Aquí podrás subir una imagen de un lunar que se vea claramente y el modelo, entrenado en Python con la librería de Tensorflow, tratará de predecir si lo que se ve allí puede ser potencialmente cancerígeno o no.

## Probar en vivo

## Cómo utilizarlo

### Descargar el repositorio
Descarga el repositorio 

### Inicia un servidor en la carpeta
Este proyecto utiliza un modelo de Tensorflow.js, el cual para cargarse requiere que el acceso sea por medio de http/https.
Para eso puedes usar cualquier servidor, pero aquí hay una forma de hacerlo:
- Descarga Python en tu computadora
- Abre una línea de comandos o terminal
- Navega hasta la carpeta donde descargaste el repositorio
- Ejecuta el comando `python -m http.server 8000`
- Abre un explorador y ve a http://localhost:8000
### Uso
Suba una imagen de un lunar en la piel que se vea claramente.

## Problemas
El modelo no se comporta correctamente con imágenes que no tienen una correcta resolución o que no corresponden a fotos de lunares en la piel de una persona.