# 🚗 Uttil - Asistente de Renta de Autos con IA Generativa

Uttil es una plataforma inteligente de carsharing que conecta a usuarios y propietarios de vehículos de forma eficiente, flexible y personalizada. Este repositorio contiene el código fuente de nuestro asistente conversacional basado en recuperación aumentada por generación (RAG) y modelos de lenguaje locales, diseñado para ayudar a los usuarios a consultar catálogos de automóviles para alquiler.

## 👨‍💻 Equipo

[**Juan Fernando Rojas**](https://www.linkedin.com/in/juan-fernando-rojas-a00955258?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app)
Estudiante de economía Universidad de Los Andes

[**Cristian Oviedo**](https://www.linkedin.com/in/cristian-oviedo-78362524b/)
Estudiante de economía Universidad de Los Andes

[**Mariana Solano**](https://www.linkedin.com/in/mariana-solano-pineda/)
Estudiante de economía y administración de empresas Universidad de Los Andes

[**Helen Margfoy**](https://www.linkedin.com/in/helenmargfoy/)
Estudiante de Economía y Gobierno y asuntos Públicos Universidad de Los Andes

[**Andrés Ballén**](www.linkedin.com/in/andrés-ballén)
Estudiante de economía Universidad de Los Andes

## 🌍 Problema que abordamos

El mercado de renta de vehículos enfrenta ineficiencias como:

- Overbooking por mala gestión de flota.
- Altos precios para los consumidores.
- Bajo o nulo seguimiento de la clientela.

Uttil propone un enfoque centrado en la comunidad para transformar la movilidad urbana con inteligencia artificial.

## 🧠 Modelo de IA

Usamos el modelo **phi4 de Microsoft**, ejecutado localmente a través del servidor **Ollama**. Este modelo es capaz de generar respuestas precisas y contextualizadas a partir de documentos cargados por el usuario.

El sistema utiliza el framework **LangChain** para implementar una arquitectura **RAG (Retrieval-Augmented Generation)**.

## ⚙️ Funcionalidades principales

- 📁 Carga de catálogos en formatos `.pdf`, `.docx`, `.csv`, `.txt`, `.json`.
- 🧩 Procesamiento automático y vectorización de contenido.
- 🤖 Chatbot con respuestas inteligentes basadas en los documentos.
- 🔄 Opción de usar generación directa vía API de Ollama para respuestas más rápidas.
- 🌐 Interfaz web amigable con **Gradio**.

## 🧪 Tecnologías utilizadas

- 🐍 Python
- 🧱 LangChain
- 🧠 Ollama (modelo `phi4`)
- 🔍 FAISS para recuperación vectorial
- 🎛️ Gradio para interfaz de usuario
- 📄 Unstructured, docx2txt, PyPDF, CSVLoader para carga de archivos
- 🧬 sentence-transformers (modelo `intfloat/multilingual-e5-small` para embeddings)

## 📈 Impacto potencial

- Mercado global de renta de vehículos: $88 mil millones (2024)
- Región LATAM: participación del 36.4%
- Proyección de ingresos: $1M USD anuales en los primeros 3 años

## 📄 Licencia

Este proyecto está bajo la Licencia MIT.

