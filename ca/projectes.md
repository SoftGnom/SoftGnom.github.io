---
layout: default
lang: ca
title: Projectes
---

## 🛠️ Repositoris & Evolució Tècnica

El catàleg públic de **SoftGnom** reflecteix una evolució orgànica: des de l'experimentació algorísmica i de baix nivell fins a la construcció d'un ecosistema modular d'IA i automatització en local.

---

### 🚀 1. Nucli de l'Ecosistema (Desenvolupament Actiu)
Projectes fonamentals que defineixen la infraestructura i el flux de treball principal del laboratori.

| Projecte | Descripció i Enfocament | Tecnologies | Estat / Rol |
| :--- | :--- | :---: | :--- |
| **[LocAI](https://github.com/SoftGnom/LocAI)** | Eina base en fase de modularització: separa la orquestració d'IA local, l'automatització de l'entorn de desenvolupament (DevOps + Agents LLM) i la futura capa d'integració de serveis. | `Shell` `Python` `Podman` `Compose`| *Core & DevOps* |

---

### 🧩 2. Eines Específiques & Proves de Concepte (PoC)
Solucions desenvolupades prèviament a la definició de l'ecosistema global, orientades a la privacitat i l'execució *offline*. Actualment funcionen com a peces autònomes pendents d'integració.

| Projecte | Descripció i Enfocament | Tecnologies | Estat / Rol |
| :--- | :--- | :---: | :--- |
| **[CopIURL](https://github.com/SoftGnom/CopIURL)** | Eina modular per automatitzar la captura, neteja, estructuració i anàlisi de contingut web de manera completament local i sense dependències externes. | `Python` | *PoC / Offline Data* |
| **[TextIAudio](https://github.com/SoftGnom/TextIAudio)** | Sistema encapsulat en contenidors aïllats per a la síntesi de veu (**TTS amb Piper**) i transcripció (**STT amb VOSK**) en entorns locals. | `Python` `Podman` `Compose` | *PoC / Multimodal* |

---

### 📦 3. Components Reutilitzables & Casos d'Ús
Desenvolupaments orientats a resoldre necessitats funcionals concretes amb capacitat d'acoblar-se a arquitectures més àmplies.

| Projecte | Descripció i Enfocament | Tecnologies | Estat / Rol |
| :--- | :--- | :---: | :--- |
| **[DynoForm](https://github.com/SoftGnom/DynoForm)** | Motor de renderitzat dinàmic capaç de generar formularis reactius i adaptables a partir d'esquemes JSON estructurats des d'un backend. | `Dart` `Flutter` `JSON` `Python` `Podman` `Compose` | *UI / Dynamic Engine* |

---

### 🔬 4. Laboratori, Dades & Fonaments de Programari
Repositoris d'exploració tècnica, entrenament de models i codi escrit de forma manual (previ a l'ús d'assistents generatius), centrats en el rigor algorísmic i el control del maquinari.

| Projecte | Descripció i Enfocament | Tecnologies | Estat / Rol |
| :--- | :--- | :---: | :--- |
| **[ML-LoL](https://github.com/SoftGnom/ML-LoL)** | Experimentació d'aprenentatge computacional sobre un conjunt de dades massiu (Riot API), avaluant models de classificació i acceleració per GPU. | `Python` `Jupyter` `CUDA` | *Data & ML Lab* |
| **[MiscelaneaPassada](https://github.com/SoftGnom/MiscelaneaPassada)** | Recull de peces de programari, estructures de dades, algorismes d'optimització i codi de baix nivell desenvolupat manualment. | `C++` `C` `Java` `Python` `Assembly` `Raspberry Pi` | *Low-level & Algorithms* |
