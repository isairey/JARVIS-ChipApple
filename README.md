<div align="center">

<img width="220" src="https://cdn-icons-png.flaticon.com/512/4712/4712109.png" />

# 🤖 Jarvis MLX

### Asistente de Inteligencia Artificial Offline para Apple Silicon 🚀

<p align="center">
  <b>Jarvis MLX</b> es una solución todo en uno inspirada en asistentes inteligentes que integra reconocimiento de voz, modelos de lenguaje y síntesis de voz ejecutándose localmente en equipos Apple Silicon mediante MLX.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Jarvis-MLX-blueviolet?style=for-the-badge">
  <img src="https://img.shields.io/badge/Apple-MLX-black?style=for-the-badge&logo=apple&logoColor=white">
  <img src="https://img.shields.io/badge/Python-AI-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Offline-AI-success?style=for-the-badge">
</p>

<p align="center">
  <a href="#-acerca-del-proyecto">Acerca</a> •
  <a href="#-características">Características</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-instalación">Instalación</a> •
  <a href="#-arquitectura">Arquitectura</a>
</p>

</div>

---

# 🌌 Acerca del proyecto

**Jarvis MLX** es un asistente inteligente diseñado para funcionar completamente de forma local en computadoras Mac con procesadores Apple Silicon.

El proyecto combina múltiples tecnologías modernas de Inteligencia Artificial:

* 🎤 Reconocimiento de voz
* 🧠 Modelos de lenguaje avanzados
* 🔊 Síntesis de voz natural
* ⚡ Ejecución optimizada mediante MLX
* 🔒 Funcionamiento completamente offline
* 🍎 Optimización para Apple Silicon

---

# ✨ Características

## 🎤 Speech To Text

* Conversión de voz a texto
* Reconocimiento automático
* Compatible con múltiples idiomas
* Basado en Whisper

---

## 🧠 Large Language Models

* Conversaciones inteligentes
* Soporte para modelos personalizados
* Compatible con Phi-3
* Compatible con Llama 3
* Compatible con Mistral

---

## 🔊 Text To Speech

* Conversión de texto a voz
* Respuestas habladas
* Baja latencia
* Voces personalizables

---

## 🔒 IA Offline

* Sin conexión a internet
* Privacidad total
* Procesamiento local
* Datos seguros

---

# 👨‍💻 Arquitectura

## 🎤 Whisper STT

Sistema de reconocimiento de voz basado en Whisper.

### Funcionalidades

* Captura de audio
* Transcripción automática
* Alta precisión
* Procesamiento local

---

## 🧠 LLM Engine

Motor de lenguaje natural.

### Funcionalidades

* Comprensión de lenguaje
* Generación de respuestas
* Integración con modelos locales
* Personalización mediante Fine-Tuning

---

## 🔊 MeloTTS

Sistema de síntesis de voz.

### Funcionalidades

* Conversión texto a voz
* Generación rápida
* Compatible con entrenamiento personalizado
* Voces configurables

---

# 🛠️ Tecnologías utilizadas

## 🤖 Inteligencia Artificial

<p>
  <img src="https://skillicons.dev/icons?i=python" />
</p>

* MLX
* Whisper
* Phi-3
* Llama 3
* Mistral
* MeloTTS

---

## 🍎 Ecosistema Apple

<p>
  <img src="https://skillicons.dev/icons?i=apple" />
</p>

* Apple Silicon
* MLX Framework
* macOS
* ARM64

---

## 🧰 Herramientas

<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode,python" />
</p>

* Git
* GitHub
* VS Code
* Python

---

# 📂 Estructura del proyecto

```bash
Jarvis-MLX/
│
├── melo/
├── whisper/
├── models/
├── audio/
├── outputs/
├── requirements.txt
├── main.py
├── config.py
└── README.md
```

---

# ⚡ Instalación

## 📋 Requisitos

* macOS
* Apple Silicon (M1, M2, M3 o superior)
* Python 3.10+
* Conda
* MLX

---

# 🚀 Configuración

## 1️⃣ Verificar arquitectura ARM

```bash
python -c "import platform; print(platform.processor())"
```

Debe devolver:

```bash
arm
```

---

## 2️⃣ Crear entorno Conda

```bash
CONDA_SUBDIR=osx-arm64 conda create -n native numpy -c conda-forge
```

---

## 3️⃣ Activar entorno

```bash
conda activate native
```

---

## 4️⃣ Instalar dependencias

```bash
pip install -r requirements.txt
```

---

# 🎤 Speech To Text

## Whisper

Jarvis utiliza Whisper para reconocimiento de voz.

### Características

* Transcripción rápida
* Modelos ligeros
* Alta precisión
* Compatible con múltiples idiomas

---

# 🧠 Large Language Models

## Modelos recomendados

* Phi-3
* Llama 3
* Mistral
* Modelos Fine-Tuned

### Rendimiento

* Hasta 60 tokens por segundo
* Optimizado para M1 Max
* Ejecución local

---

# 🔊 Text To Speech

## MeloTTS

Sistema utilizado para sintetizar voz.

### Características

* Generación rápida
* Baja latencia
* Entrenamiento personalizado
* Compatible con datasets propios

### Nota

La configuración inicial utiliza una voz femenina. Para cambiarla es necesario entrenar un modelo personalizado de MeloTTS.

---

# 📊 Funcionalidades principales

## 🤖 Asistente Inteligente

* Conversaciones naturales
* Procesamiento local
* Respuestas en tiempo real
* Integración de voz

---

## 🔒 Privacidad

* Sin servicios externos
* Sin envío de datos
* Procesamiento offline
* Seguridad mejorada

---

## ⚡ Rendimiento

* Optimizado para Apple Silicon
* Uso eficiente de GPU Neural Engine
* Baja latencia
* Alta velocidad de respuesta

---

# 🎯 Casos de uso

* 🤖 Asistentes personales
* 🎙️ Automatización por voz
* 🧠 Investigación en IA
* 🔒 Aplicaciones privadas
* 💼 Productividad personal
* 🏠 Sistemas inteligentes locales

---

# 🚧 Roadmap

## 🔮 Próximas mejoras

* Soporte para nuevos LLMs
* Mejoras en TTS
* Integración multimodal
* Agentes autónomos
* Automatización avanzada
* Soporte para visión artificial

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas ❤️

## Cómo contribuir

1. Fork del proyecto

```bash
git checkout -b feature/nueva-funcionalidad
```

2. Commit

```bash
git commit -m "✨ Nueva funcionalidad"
```

3. Push

```bash
git push origin feature/nueva-funcionalidad
```

4. Pull Request 🚀

---

# 👨‍💻 Desarrollador

<div align="center">

## Huw Prosser

Desarrollador enfocado en Inteligencia Artificial local, asistentes inteligentes y tecnologías optimizadas para Apple Silicon.

</div>

---

# 🌟 Apoya el proyecto

⭐ Dale una estrella
🍴 Haz fork
📢 Comparte el proyecto

---

# 📜 Licencia

Proyecto open source orientado al desarrollo de asistentes inteligentes locales utilizando tecnologías modernas de Inteligencia Artificial.

---

<div align="center">

### 🤖 Jarvis MLX — tu asistente inteligente offline impulsado por Apple Silicon 🚀

</div>

