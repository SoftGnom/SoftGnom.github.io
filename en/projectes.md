---
layout: default
lang: en
title: Projects
---

## 🛠️ Repositories & Technical Evolution

The **SoftGnom** public catalog reflects an organic evolution: from low-level, algorithmic experimentation to the construction of a modular ecosystem for local AI and automation.

---

### 🚀 1. Ecosystem Core (Active Development)
Foundational projects that define the laboratory's infrastructure and primary workflow.

| Project | Description & Approach | Technologies | Status / Role |
| :--- | :--- | :---: | :--- |
| **[LocAI](https://github.com/SoftGnom/LocAI)** | A core tool currently undergoing modularization; it separates local AI orchestration, development environment automation (DevOps + LLM agents), and a future service integration layer. | `Shell` `Python` `Podman` `Compose`| *Core & DevOps* |

---

### 🧩 2. Specialized Tools & Proofs of Concept (PoC)
Solutions developed prior to the definition of the overall ecosystem, focused on privacy and *offline* execution. These currently function as standalone components awaiting integration.

| Project | Description & Approach | Technologies | Status / Role |
| :--- | :--- | :---: | :--- |
| **[CopIURL](https://github.com/SoftGnom/CopIURL)** | A modular tool for automating the capture, cleaning, structuring, and analysis of web content—running entirely locally with no external dependencies. | `Python` | *PoC / Offline Data* |
| **[TextIAudio](https://github.com/SoftGnom/TextIAudio)** | A system encapsulated in isolated containers for speech synthesis (**TTS using Piper**) and transcription (**STT using VOSK**) in local environments. | `Python` `Podman` `Compose` | *PoC / Multimodal* |

---

### 📦 3. Reusable Components & Use Cases
Developments aimed at addressing specific functional requirements, designed to be integrated into larger, broader architectures.

| Project | Description and Approach | Technologies | Status / Role |
| :--- | :--- | :---: | :--- |
| **[DynoForm](https://github.com/SoftGnom/DynoForm)** | A dynamic rendering engine capable of generating reactive, adaptable forms based on JSON schemas structured via a backend. | `Dart` `Flutter` `JSON` `Python` `Podman` `Compose` | *UI / Dynamic Engine* |

---

### 🔬 4. Laboratory, Data & Software Foundations
Repositories for technical exploration, model training, and code written manually (prior to the use of generative assistants), with a focus on algorithmic rigor and hardware control.

| Project | Description and Approach | Technologies | Status / Role |
| :--- | :--- | :---: | :--- |
| **[ML-LoL](https://github.com/SoftGnom/ML-LoL)** | Machine learning experimentation on a massive dataset (Riot API), evaluating classification models and GPU acceleration. | `Python` `Jupyter` `CUDA` | *Data & ML Lab* |
| **[MiscelaneaPassada](https://github.com/SoftGnom/MiscelaneaPassada)** | A collection of software components, data structures, optimization algorithms, and manually developed low-level code. | `C++` `C` `Java` `Python` `Assembly` `Raspberry Pi` | *Low-level & Algorithms* |
