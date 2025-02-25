# IA_Detect-o-de-imagens-e-texto
Código Python (Notebook Colab) para detectar imagens e texto usando webcam do computador.

Esse código pode ser rodado tanto em sua maquina local ou online no Google Colab. O importante é que ambas as formas de rodar a rede, GPU será necessário.

Requerimentos:
Bibliotecas e Frameworks.

numpy
# Install espeak primeiro, para que o pyttsx3 possa acha-lo.
!apt-get install -y espeak
# Instalar pacotes, modulos, dependencias e frameworks.
!pip install ultralytics opencv-python-headless pillow easyocr pyttsx3
!pip install gradio

Bibliotecas a serem importadas para que a rede rode no colab.
from IPython.display import display, Javascript
from google.colab.output import eval_js
import cv2
import numpy as np
import base64
