
<div align="center">

# Hi, I'm Ngô Hoàng Dương 👋


**AI researcher · Computer vision, multi-object tracking & AI agents**


</div>

---

### 🧠 About

- I'm an AI researcher interested in **AI agents** and in **computer vision** systems that have to run on real video.
- My recent work covers **multi-object tracking and ReID** (single and multi-camera), **vision-language pipelines** (agentic object detection, image/video captioning), and agent-driven data pipelines.
- On the side I build TypeScript web apps, such as a personal productivity companion.

---

### 🛠️ Tech I work with

**AI / CV**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Hugging Face Transformers](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-F97316?style=flat-square&logo=gradio&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white)
![Rasa](https://img.shields.io/badge/Rasa-5A17EE?style=flat-square&logo=rasa&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

**Backend / Web / Tooling**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

### 🚀 Featured projects

#### 🎯 Computer Vision · Multi-Object Tracking & ReID

| Project | What it is | Stack |
|---|---|---|
| [**six-eye**](https://github.com/HoangDuong-Devs/six-eye) | Multi-camera tracking with a **global ID module**: merges per-camera tracks into cross-camera identities, with homography computation for a shared map. Includes a written analysis comparing merge and conflict-resolution strategies. | Python · PyTorch · OpenCV · Qdrant |
| [**boxmot_multicamera**](https://github.com/HoangDuong-Devs/boxmot_multicamera) | A standalone, minimal tracking package: YOLOv7 detection, BoT-SORT with pending-ID management, ID-switch detection, long-term ReID in Qdrant, and a **multi-camera demo** that assigns global IDs and draws tracks on a shared map. | Python · PyTorch · YOLOv7 · OSNet · Qdrant |
| [**boxmot**](https://github.com/HoangDuong-Devs/boxmot) | A **Tracking + ReID system** built on [BoxMOT](https://github.com/mikel-brostrom/boxmot). It combines BoT-SORT/DeepOCSORT with short- and long-term ReID (OSNet, ArcFace, Qdrant), plus **Pending ID** and **Assign ID Manager** logic for handling ID swaps. | Python · PyTorch · YOLOv7 · Docker |
| [**Supervision-System**](https://github.com/HoangDuong-Devs/Supervision-System) | A supervision workspace based on BoxMOT, with face detection/recognition and ReID experiments around YOLOv7 tracking. | Python · PyTorch · Jupyter · Docker |
| [**Face_Alignment**](https://github.com/HoangDuong-Devs/Face_Alignment) | A FastAPI web service that takes an uploaded video and aligns and crops faces with dlib's 68-point landmarks, then renders a processed video. | Python · FastAPI · OpenCV · dlib |

#### 🤖 AI Agents · Vision-Language · Data Pipelines

| Project | What it is | Stack |
|---|---|---|
| [**Agentic_Object_Detection**](https://github.com/HoangDuong-Devs/Agentic_Object_Detection) | A 5-step **agentic object detection** pipeline. VLMs (GPT-4o, o1) act as reasoners and reviewers with chain-of-thought around an open-vocabulary detector (Grounding DINO), and refine concepts before re-detecting. | Python · OpenAI API · Grounding DINO · Gradio |
| [**Video-Captioning**](https://github.com/HoangDuong-Devs/Video-Captioning) | A trimmed **BLIP caption toolkit** for training and inference: a single-image CLI, a web app, and a video captioner that captions frames and overlays the text on the video. | Python · PyTorch · Transformers |
| [**labeling-tool**](https://github.com/HoangDuong-Devs/labeling-tool) | An end-to-end, agent-driven pipeline for data collection, model training, and automated dataset generation *(early stage)*. | — |
| [**ChatbotRasa**](https://github.com/HoangDuong-Devs/ChatbotRasa) | A chatbot built with Rasa NLU and Core: intents, entities, custom actions and dialogue management. | Python · Rasa |

#### 🌐 Apps

| Project | What it is | Stack |
|---|---|---|
| [**project-ellie**](https://github.com/HoangDuong-Devs/project-ellie) | **ProjectEllie**, a personal productivity app for finances, schedules and tasks. It also has journal, goals, focus and mind-map views, an assistant, and a 3D VRM companion. | TypeScript · React · TanStack Start · Supabase · Three.js |

<!-- Optional, small: forks I'm exploring -->
<sub>🔭 Exploring: [agentmemory](https://github.com/HoangDuong-Devs/agentmemory) · [OpenViking](https://github.com/HoangDuong-Devs/OpenViking), on memory and context for AI agents.</sub>

---

### 📊 GitHub stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=HoangDuong-Devs&show_icons=true&count_private=false&hide_border=true&theme=tokyonight" alt="GitHub stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=HoangDuong-Devs&layout=compact&hide_border=true&theme=tokyonight" alt="Top languages" />

</div>

---

### 📫 Contact

[![GitHub](https://img.shields.io/badge/GitHub-HoangDuong--Devs-181717?style=flat-square&logo=github)](https://github.com/HoangDuong-Devs)

<!-- TODO: add contact links once approved (e.g. LinkedIn / X / blog). No email for now. -->
