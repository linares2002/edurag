## 1. General Description
**AVATAR** (_Academic Virtual Assistant with Text Augmentation and Retrieval_) is an educational web application developed for the University of Jaén as a solution to a teaching innovation project under the **PIMED 2025** call. The system combines four technologies:

| Technology | Function | Implementation |
|---|---|---|
| **RAG** (Retrieval-Augmented Generation) | Academic document querying with contextualised responses | ChromaDB + SentenceTransformers + LLM |
| **YOLO v8** | Real-time visual object recognition | ultralytics YOLOv8n |
| **Augmented Reality** | Overlay of 3D content onto physical markers | A-Frame 1.2.0 + AR.js 3.3.3 |
| **TTS/STT** | Voice accessibility (input and output) | Web Speech API (browser) |

### Context and Motivation
University students demand learning methods adapted to their information consumption patterns: immediacy, high visual content, and ubiquitous access from mobile devices. Traditional methods (bibliographic searches, generic LLMs such as ChatGPT) do not provide quality answers to highly specific questions relating to a particular subject.

**AVATAR** solves this problem by enabling students to:
- Point their device camera at physical objects and receive contextualised academic information.
- Scan AR markers in teaching materials to visualise overlaid 3D content.
- Ask questions in natural language (text or voice) and obtain AI-generated responses based on the subject's specific documentary corpus.

### Degrees and Subjects
The initial rollout takes place in:
- **Bachelor's Degree in Telecommunication Technologies Engineering**
- **Master's Degree in Telecommunication Engineering**

Subjects: Optical Technologies, Optical Communications, Telecommunication Infrastructures, IP-based Networks.
