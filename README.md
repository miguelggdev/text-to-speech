# Text-to-Speech (TTS)

## 📢 Kokoro - Open-Weight TTS Model

[Kokoro](https://huggingface.co/hexgrad/Kokoro-82M) es un modelo de conversión de texto a voz (TTS) de código abierto con **82 millones de parámetros**. Este repositorio proporciona herramientas y scripts para utilizar Kokoro de manera eficiente en distintos proyectos de síntesis de voz.

## 🚀 Características
- 🔊 **Modelo ligero**: 82M de parámetros para una síntesis eficiente.
- 🏆 **Código abierto**: Disponible en Hugging Face.
- 🎙️ **Calidad de voz natural**.

## 📥 Instalación
Asegúrate de tener **Python 3.8+** y ejecuta:
```bash
pip install -r requirements.txt
```

## 🚀 Uso

Puedes probar tu código, generar el audio y descargarlo usando **Google Colab**.

Ejemplo de uso con Python:
```python
from kokoro import TTS

model = TTS.load("hexgrad/Kokoro-82M")
model.synthesize("Hola, bienvenido a Text-to-Speech con Kokoro!")
```

## 📌 Enlaces útiles
- 📄 Modelo en Hugging Face: [Kokoro-82M](https://huggingface.co/hexgrad/Kokoro-82M)
- 📖 Documentación oficial: *próximamente*

## 🤝 Contribuciones
¡Las contribuciones son bienvenidas! Si deseas mejorar este proyecto, por favor abre un **issue** o envía un **pull request**.

## 📝 Licencia
Este proyecto se encuentra bajo la licencia **MIT**.

---
✉️ *Desarrollado con ❤️ por [tu nombre o usuario]*



