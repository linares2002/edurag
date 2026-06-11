## 1. Descripción General

**AVATAR** (_Academic Virtual Assistant with Text Augmentation and Retrieval_) es una aplicación web educativa desarrollada para la Universidad de Jaén como solución a un proyecto de innovación docente de la convocatoria **PIMED 2025**. El sistema combina cuatro tecnologías:

| Tecnología | Función | Implementación |
|---|---|---|
| **RAG** (Retrieval-Augmented Generation) | Consulta de documentos académicos con respuestas contextualizadas | ChromaDB + SentenceTransformers + LLM |
| **YOLO v8** | Reconocimiento visual de objetos en tiempo real | ultralytics YOLOv8n |
| **Realidad Aumentada** | Superposición de contenido 3D sobre marcadores físicos | A-Frame 1.2.0 + AR.js 3.3.3 |
| **TTS/STT** | Accesibilidad mediante voz (entrada y salida) | Web Speech API (navegador) |

### Contexto y Motivación

El estudiantado universitario demanda métodos de aprendizaje adaptados a sus patrones de consumo de información: inmediatez, alto contenido visual y acceso ubicuo desde dispositivos móviles. Los métodos tradicionales (búsquedas bibliográficas, LLMs genéricos como ChatGPT) no proporcionan respuestas de calidad a dudas muy específicas relativas a una asignatura concreta.

**AVATAR** resuelve este problema permitiendo que el estudiante:
- Apunte con la cámara de su dispositivo a objetos físicos y reciba información académica contextualizada.
- Escanee marcadores AR en materiales docentes para visualizar contenido 3D superpuesto.
- Formule preguntas en lenguaje natural (texto o voz) y obtenga respuestas generadas por IA basadas en el corpus documental específico de la asignatura.

### Titulaciones y Asignaturas

La implantación inicial se realiza en:
- **Grado en Ingeniería de Tecnologías de Telecomunicación**
- **Máster en Ingeniería de Telecomunicación**

Asignaturas: Tecnologías Ópticas, Comunicaciones Ópticas, Infraestructuras de Telecomunicación, Redes basadas en IP.
