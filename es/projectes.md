---
layout: default
lang: es
title: Proyectos
---

## 🛠️ Repositorios & Evolución Técnica

El catálogo público de **SoftGnom** refleja una evolución orgánica: desde la experimentación algorítmica y de bajo nivel hasta la construcción de un ecosistema modular de IA y automatización en local.

---

### 🚀 1. Núcleo del Ecosistema (Desarrollo Activo)
Proyectos fundamentales que definen la infraestructura y el principal flujo de trabajo del laboratorio.

| Proyecto | Descripción y Enfoque | Tecnologías | Estado / Rol |
| :--- | :--- | :---: | :--- |
| **[LocAI](https://github.com/SoftGnom/LocAI)** | Herramienta base en fase de modularización: separa la orquestación de IA local, la automatización del entorno de desarrollo (DevOps + Agents LLM) y la futura capa de integración de servicios. | `Shell` `Python` `Podman` `Compose`| *Core & DevOps* |

---

### 🧩 2. Herramientas Específicas & Pruebas de Concepto (PoC)
Soluciones desarrolladas previamente a la definición del ecosistema global, orientadas a la privacidad y ejecución *offline*. Actualmente funcionan como piezas autónomas pendientes de integración.

| Proyecto | Descripción y Enfoque | Tecnologías | Estado / Rol |
| :--- | :--- | :---: | :--- |
| **[CopIURL](https://github.com/SoftGnom/CopIURL)** | Herramienta modular para automatizar la captura, limpieza, estructuración y análisis de contenido web de forma completamente local y sin dependencias externas. | `Python` | *PoC / Offline Data* |
| **[TextIAudio](https://github.com/SoftGnom/TextIAudio)** | Sistema encapsulado en contenedores aislados para la síntesis de voz (**TTS con Piper**) y transcripción (**STT con VOSK**) en entornos locales. | `Python` `Podman` `Compose` | *PoC / Multimodal* |

---

### 📦 3. Componentes Reutilizables & Casos de Uso
Desarrollos orientados a resolver necesidades funcionales concretas con capacidad de ensamblarse a arquitecturas más amplias.

| Proyecto | Descripción y Enfoque | Tecnologías | Estado / Rol |
| :--- | :--- | :---: | :--- |
| **[DynoForm](https://github.com/SoftGnom/DynoForm)** | Motor de renderizado dinámico capaz de generar formularios reactivos y adaptables a partir de esquemas JSON estructurados desde un backend. | `Dart` `Flutter` `JSON` `Python` `Podman` `Compose` | *UI / Dynamic Engine* |

---

### 🔬 4. Laboratorio, Datos & Fundamentos de Software
Repositorios de exploración técnica, entrenamiento de modelos y código escrito de forma manual (previo al uso de asistentes generativos), centrados en el rigor algorítmico y el control del hardware.

| Proyecto | Descripción y Enfoque | Tecnologías | Estado / Rol |
| :--- | :--- | :---: | :--- |
| **[ML-LoL](https://github.com/SoftGnom/ML-LoL)** | Experimentación de aprendizaje computacional sobre un conjunto de datos masivo (Riot API), evaluando modelos de clasificación y aceleración por GPU. | `Python` `Jupyter` `CUDA` | *Data & ML Lab* |
| **[MiscelaneaPassada](https://github.com/SoftGnom/MiscelaneaPassada)** | Recopilación de piezas de software, estructuras de datos, algoritmos de optimización y código de bajo nivel desarrollado manualmente. | `C++` `C` `Java` `Python` `Assembly` `Raspberry Pi` | *Low-level & Algorithms* |
