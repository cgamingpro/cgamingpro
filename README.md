# CG

<div align="center">

**Unity · AR/VR · Machine Learning · Backend Systems** [![GitHub followers](https://img.shields.io/github/followers/cgamingpro?label=follow&style=social)](https://github.com/cgamingpro)

</div>

---

A practical builder of interactive 3D systems, scalable backend architectures, and compact ML demos. I ship playable prototypes, optimize for performance, and prefer simple, explorable systems over abstract concepts.

---

## ⭐ Featured projects

### 🔹 [ITR_hub](https://github.com/cgamingpro/ITR_hub)  
**Tech:** Python · FastAPI · Redis · PostgreSQL · Selenium  
Distributed Robotic Process Automation (RPA) engine. Automates bulk data scraping operations using headless Selenium, utilizing an asynchronous background job queue (RQ) to process records concurrently without blocking the main web server. Features real-time compilation and NLP-to-SQL analytics via Google Gemini.

### 🔹 [VR_Gallery](https://github.com/cgamingpro/VR_Gallery)  
**Tech:** Unity · C# · Blender · ShaderLab/HLSL  
Mobile-first VR gallery for Google Cardboard. Blender-modeled assets and custom shaders, optimized to run smoothly on mid-range Android devices.

### 🔹 [DoomDt — Doom-style FPS Template](https://github.com/cgamingpro/DoomDt)  
**Tech:** Unity · C# · Blender  
Reusable FPS template focused on rapid prototyping: modular weapon & movement systems, enemy spawning, and quick-iteration workflows.

### 🔹 [Procedural Map Generator](https://github.com/cgamingpro/ProceduralDungeonGenrator)  
**Tech:** Unity · C# · Blender  
Noise-driven procedural maps for roguelike / sandbox-style levels (suitable for Minecraft-like worlds). Generates unique, replayable maps and reduces manual design time.

### 🔹 [Ascii_Gator](https://github.com/cgamingpro/Ascii_Gator)  
**Tech:** Python · OpenCV · NumPy  
Utility that converts images into ASCII art by mapping pixel brightness values to character sets. Designed as a lightweight experiment in image processing and terminal-based visualization.

### 🔹 [HandyTowers](https://github.com/cgamingpro/HandyTowers)  
**Tech:** Unity · C#  
Interactive project focused on gameplay experimentation and hands-on prototype development.

---

## 🧰 Tech & Tools

**Languages:** C · C++ · Java · Python · C# · SQL  
**Game / 3D:** Unity (expert) · Blender · TouchDesigner  
**Backend & Web:** FastAPI · PostgreSQL · Redis · Selenium  
**ML & Data:** NumPy · Pandas · Matplotlib · OpenCV · scikit-learn  
**Tools:** Git · Linux · Docker · VMware · MySQL · VS Code · Adobe CC

---

## ⚙️ Quick demos & how to run

> Backend Services (ITR_hub)
- Provision local or cloud instances of **Redis** and **PostgreSQL**.
- Boot the API servers: `uvicorn main:app --port 8000 --reload`
- Spin up background workers: `rq worker high default low --with-scheduler`

> Unity projects  
- Open the project folder in **Unity Hub** → use Unity 2020–2022 (whichever matches the project).  
- Open the sample scene and press Play. Mobile builds: switch platform to Android, build APK and test on device (use Google Cardboard for VR Gallery).

> ML notebooks  
- `pip install -r requirements.txt`  
- `jupyter notebook` or deploy with Streamlit / Gradio for an interactive demo:  
```bash
pip install streamlit
streamlit run app.py
