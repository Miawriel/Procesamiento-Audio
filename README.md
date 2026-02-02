## Procesamiento de Audio con Diversas Librerías de Python 🎧🐍
Este proyecto fue desarrollado para la materia de Ciencia de Datos para Sensores Inteligentes. El objetivo principal es explorar y comparar las capacidades de 5 librerías líderes en Python para la carga, manipulación, filtrado y transcripción de señales de audio.

🚀 Resumen del Proyecto
El notebook documenta un flujo de trabajo experimental donde se somete un archivo de audio (Cancion de gato) a diferentes transformaciones para entender conceptos fundamentales como la frecuencia de muestreo (sampling rate), la normalización y la transcripción automática (ASR).

🛠️ Librerías Utilizadas
El análisis se divide en 5 enfoques técnicos:

Librosa: Utilizada para la carga profesional y visualización de la forma de onda.

Soundfile: Empleada para la escritura y exportación de archivos procesados.

SciPy: Aplicación de filtros digitales (pasa-bajas) y análisis matemático de la señal.

Pydub: Manipulación de volumen y efectos rápidos de audio.

Transformers (Hugging Face): Implementación del modelo Whisper para transcripción de audio a texto.

📊 Puntos Clave del Análisis
Filtros Digitales: Se implementó un filtro pasa-bajas con SciPy para observar cómo se eliminan las frecuencias agudas de la señal original.

El reto de la IA: Se documentó cómo el modelo Whisper intenta forzar sonidos fuera del dominio del habla (un maullido) hacia patrones del lenguaje humano, transcribiendo "yum" en lugar de un sonido onomatopéyico de gato.

Muestreo: Verificación de cómo el sampling rate afecta la representación de la señal y la compatibilidad entre librerías.

📋 Requisitos
Para replicar este experimento, necesitas instalar:

Bash
pip install librosa soundfile scipy pydub transformers torch
