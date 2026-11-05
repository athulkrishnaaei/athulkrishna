<div align="center">

<img src="assets/hero.svg" alt="Athulkrishna VP — Robotics, Autonomous Systems & Physical AI" width="100%" />

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=19&duration=3000&pause=900&color=38BDF8&center=true&vCenter=true&width=850&lines=Robotics+%26+Autonomous+Systems+Engineer;ROS+2+%7C+LiDAR+%7C+3D+Motion+Planning;Physical+AI+%7C+VLM%2FVLA+Robot+Safety;From+Perception+to+Safe+Robot+Action" alt="Typing animation with robotics specializations" /></a>

**Robotics · Physical AI · Autonomous Navigation · UAVs · Perception · Robot Safety**

[![GitHub](https://img.shields.io/badge/GitHub-athulkrishnaaei-111827?style=for-the-badge&logo=github&logoColor=white)](https://github.com/athulkrishnaaei)
[![Email](https://img.shields.io/badge/Email-Contact_Me-0ea5e9?style=for-the-badge&logo=gmail&logoColor=white)](mailto:athulkrishnavpkdlr47@gmail.com)
[![Location](https://img.shields.io/badge/Based_in-Germany-0f766e?style=for-the-badge&logo=googlemaps&logoColor=white)](#about-me)

</div>

## 👋 About Me

I'm **Athulkrishna VP**, a robotics engineer and **M.Eng. Mechatronics and Cyberphysical Systems** student at **Deggendorf Institute of Technology** in Germany. My work connects robot perception, autonomous planning, and foundation-model reasoning with practical safety mechanisms for real-world robotic systems.

- 🤖 **Physical AI & safety:** researching knowledge- and constitution-guided safety monitoring for robot motion and Vision-Language-Action (VLA) systems at **Schaeffler**.
- 🚁 **Autonomous UAVs:** developed LiDAR-based plane detection, 3D mapping, path planning, and simulated precision landing at **Universität der Bundeswehr München**.
- 🧭 **Navigation:** build ROS-based mobile robots and 3D planners using **A\***, **RRT/RRT\***, point clouds, and occupancy maps.
- 🦾 **Hands-on robotics:** experience with humanoid robots, robotic arms, embedded controllers, and vision-driven interaction.
- 🔎 **Interested in:** full-time robotics, robot perception, autonomous systems, and Physical AI engineering opportunities.

## 🛠️ Technical Toolbox

**Robotics, planning & simulation**

![ROS](https://img.shields.io/badge/ROS%201%20%2F%202-22314E?style=flat-square&logo=ros&logoColor=white)
![PX4](https://img.shields.io/badge/PX4-1C1C1C?style=flat-square)
![LiDAR](https://img.shields.io/badge/LiDAR-0f766e?style=flat-square)
![SLAM](https://img.shields.io/badge/SLAM-0f766e?style=flat-square)
![A*](https://img.shields.io/badge/A*-0f766e?style=flat-square)
![RRT*](https://img.shields.io/badge/RRT%20%2F%20RRT*-0f766e?style=flat-square)
![Gazebo](https://img.shields.io/badge/Gazebo-f59e0b?style=flat-square)
![AirSim](https://img.shields.io/badge/AirSim-f59e0b?style=flat-square)
![Unreal Engine](https://img.shields.io/badge/Unreal%20Engine-111827?style=flat-square&logo=unrealengine&logoColor=white)
![RViz](https://img.shields.io/badge/RViz-f59e0b?style=flat-square)

**AI, perception & safety**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Open3D](https://img.shields.io/badge/Open3D-6366f1?style=flat-square)
![SigLIP](https://img.shields.io/badge/SigLIP-6366f1?style=flat-square)
![VLM / VLA](https://img.shields.io/badge/VLM%20%2F%20VLA-6366f1?style=flat-square)
![3D Point Clouds](https://img.shields.io/badge/3D%20Point%20Clouds-6366f1?style=flat-square)
![OctoMap](https://img.shields.io/badge/OctoMap-6366f1?style=flat-square)

**Development & hardware**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Arduino](https://img.shields.io/badge/Arduino-00878F?style=flat-square&logo=arduino&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![NVIDIA Jetson](https://img.shields.io/badge/NVIDIA%20Jetson-76B900?style=flat-square&logo=nvidia&logoColor=white)

## 🚀 Featured Projects

### 01 · Constitutional Safety Brain — Robot Safety Monitoring

**Python · SigLIP · PyTorch · VLMs · Semantic Retrieval · Constitutional AI**

Designed a safety-monitoring pipeline that matches robot camera frames against **63 constitutional safety rules**, using visual–text embeddings for fast first-pass screening. Built rule-level hazard scoring and an evaluation interface for comparing detection and reasoning behavior.

- Benchmarked an approximately **137 ms** SigLIP screening path against a **34.9 s** Qwen-VL reasoning path in the documented experiment (about **255×** faster in that comparison).
- Exploring graph-guided safety checks, selective higher-level reasoning, and explainable interventions for robot control.

🎥 [Watch the demonstration](https://youtube.com/watch?v=MK_gFOnhCw8)

### 02 · Safety-Aware Vision-Language-Action Controller

**Python · RoboBrain2.5 · V-JEPA · VLMs · Risk Visualization**

Built an experimental **three-stage safety-gated pipeline** for screening robot commands and candidate trajectories. Combined constitution-based command checks with model-assisted trajectory assessment and visual risk overlays. Created an evaluation UI for investigating safety decisions and debugging scenarios.

🎥 [Watch the demonstration](https://youtu.be/Ehb461TiQHI)

### 03 · Autonomous Drone Landing on Cargo Boxes

**ROS · LiDAR · Python · RRT · Unreal Engine · RViz**

Developed a simulated autonomous landing workflow that uses LiDAR point clouds to identify cargo boxes, estimate landing targets, and plan obstacle-aware routes to their centers. Integrated a custom RRT-based planning library with visualization and flight simulation.

🎥 [Watch the demonstration](https://youtu.be/JImVHIX0O0U)

### 04 · Landing Assist Module (LAM)

**ROS 2 · AirSim · Unreal Engine · Open3D · OctoMap · RANSAC / PROSAC**

Explored safe UAV landing-zone detection from 3D point clouds, including planar-surface detection, occupancy mapping, and simulation-driven evaluation.

📂 [Source code — Landing Assist Module](https://github.com/athulkrishnaaei/Landing-Assist-Module-LAM)

### 05 · ROS-Based Autonomous Mobile Robot

**ROS · RPLIDAR · Jetson Nano · Arduino Nano · Flask**

Built a LiDAR-equipped mobile robot with environment mapping, distributed motor control, and a browser interface for goal selection, remote operation, and live system monitoring.

🎥 [Watch the demonstration](https://youtube.com/shorts/nsJ0YgHIQi0)

### 06 · Humanoid Robot with Hand Tracking

**Computer Vision · Gesture Interaction · Robotics**

Contributed to a humanoid platform that follows hand movement in real time and supports gesture-responsive interaction, question answering, and line following.

🎥 [Watch the demonstration](https://youtu.be/STopG6v4R4s)

<details>
<summary><b>More projects</b></summary>

- **Edge AI Apple Classification & Pneumatic Sorting** — YOLOv5, Raspberry Pi, Arduino, MQTT, and pneumatic actuation; ongoing tracking and timing improvements.
- **IoT Smart Extension Board** — Internet-connected control of three devices, voice assistants, mobile controls, and Telegram integration. [Demo](https://youtu.be/RJqJeY4B5Eo)
- **Electric Cycle** — lithium-ion / BLDC-motor project with a reported 25 km range and 40 km/h top speed. [Demo](https://youtu.be/SsaXQv5LV0E)
- **Hand Gesture Controlled Robotic Arm** — OpenCV gesture tracking mapped to servo motion. [Demo](https://youtu.be/gQuPhFFletc)

</details>

## 💼 Experience

| Organization | Role | Period |
|---|---|---|
| **Schaeffler Technologies AG & Co. KG** | Master thesis student ,Safety Brain for Humanoid Robots: Knowledge-Graph-Guided Safety Monitoring For Motion Control  | AUG 2026 – Present |
| **Schaeffler Technologies AG & Co. KG** | Behavioral Safety Research Intern, Innovation Factory | Sep 2025 – Mar 2026 |
| **Universität der Bundeswehr München** | Student Research Assistant — UAV perception & planning | Jun 2024 – May 2025 |
| **Robomiracle** | Robotics Trainer & Research Specialist | Feb 2023 – Aug 2023 |

At Robomiracle, I helped teach hands-on robotics, programming, 3D printing, and drone technology to **2,000+ students**.

## 🎓 Education

| Degree | University | Period |
|---|---|---|
| **M.Eng. Mechatronics and Cyberphysical Systems** | Deggendorf Institute of Technology, Germany | Mar 2025 – Present |
| **B.Tech. Mechanical Engineering** | PRIST University, India | Mar 2018 – Aug 2022 |

## 📬 Let's Connect

I'm interested in collaborations on **safe embodied intelligence, robot perception, autonomous navigation, planning, and UAV systems**.

📧 **Email:** [athulkrishnavpkdlr47@gmail.com](mailto:athulkrishnavpkdlr47@gmail.com)  
🐙 **GitHub:** [github.com/athulkrishnaaei](https://github.com/athulkrishnaaei)  
📍 **Based in Germany**

---

<div align="center">
<sub>Engineering autonomy with perception, planning, and safety in the loop.</sub>
</div>
