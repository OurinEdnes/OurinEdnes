<!-- ===================== HEADER ===================== -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=220&section=header&text=OCEADRA_SYS%20%F0%9F%A6%88&fontSize=56&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Computer%20Vision%20%C2%B7%20IoT%20%C2%B7%20UAV%20%C2%B7%20Software%20Engineering&descSize=18&descAlignY=58" alt="header" />

<a href="https://ourinednes.github.io/">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1200&color=4FC3F7&center=true&vCenter=true&width=700&lines=Informatics+Student+%7C+Tech+Lead+%40+Djayanta+UAV;Computer+Vision+%26+Hardware+Integration;C%2B%2B+%7C+Java+%7C+Python+%7C+YOLO+%7C+OpenCV;Small+shark%2C+big+curiosity" alt="Typing SVG" />
</a>

<br/><br/>

[![Portfolio](https://img.shields.io/badge/🌊_Portfolio-ourinednes.github.io-0e75b6?style=for-the-badge)](https://ourinednes.github.io/)
[![Instagram](https://img.shields.io/badge/Instagram-@_decadanza-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/_decadanza/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/banu-najieh-al-fadhil-5249b8325/)

![Profile Views](https://komarev.com/ghpvc/?username=OurinEdnes&label=Profile%20Views&color=0e75b6&style=flat-square)
![Followers](https://img.shields.io/github/followers/OurinEdnes?style=flat-square&logo=github&color=203a43)

</div>

---

## 👋 About Me

```cpp
#include <shark.h>

struct Oceadra {
    string role       = "Informatics Student @ Universitas Ahmad Dahlan";
    string exchange   = "AIMS Exchange Scholar @ UMPSA, Malaysia 🇲🇾 (Fall 2026)";
    string location   = "Yogyakarta, ID 🇮🇩 x Pekan, MY";
    string specialty[3] = {"Computer Vision", "Hardware Integration (IoT/UAV)", "Software Engineering"};
    string philosophy = "Good tech isn't just code that runs, but code that makes sense.";
    bool   breaksThingsToLearn = true; // responsibly, of course 😌
};
```

I design **real-time intelligent systems** and connect them to real hardware. I like learning from the ground up (C++, data structures, how systems behave behind the scenes), asking *"why?"*, and thinking outside the box when the box feels too small.

- 🚁 **Tech Lead @ Djayanta UAV Team:** network config & stable real-time UAV ↔ ground-station communication
- 🔥 **Samsung Innovation Campus:** building an IoT early-warning system for forest fires (ESP32 + multi-sensor + MQTT)
- 🤖 **R&D Team Member @ UMPBOT**
- 💼 **6-month internship** in Data & CS
- 🔭 **Building:** HCI hand-landmark system and a water-disaster victim detection prototype
- 🎤 **Public speaking:** awarded *The Best Student* in the HMIF Public Speaking Training (2024)
- 🌏 **International Delegate**, iFUTURE 2026 Young Future Leaders Summit @ WTC Kuala Lumpur
- 📝 **Research:** paper on a digital-image-processing based water-disaster victim detection system, submitted to JuTISI (Oct 2026)
- 🦈 **Fun fact:** huge soft spot for shark-themed anime characters

---

## 🔥 Spotlight: Forest Fire Early Warning System

> **Samsung Innovation Campus (IoT)** · Team of 4 · Prototype simulated in Wokwi

Forest and peatland fires (*karhutla*) keep recurring in Indonesia. Peat fires can smolder underground for months, and satellite imagery or manual patrols often detect them too late. Existing IoT prototypes usually rely on a single short-range flame sensor, which causes inaccurate alarms. This project focuses on **detecting the trigger conditions and the earliest signs of burning, before the fire grows.**

| | |
|---|---|
| 🧠 **Controller** | ESP32 with ADC calibration and multivariate rule-based risk logic |
| 🌡️ **Sensors** | DHT22 (air temperature & humidity) · capacitive soil moisture · MQ-2 (gas/smoke) |
| 🚦 **Risk levels** | `Normal` → `Warning` → `Danger` |
| 🔔 **Local alert** | LED + buzzer on site |
| ☁️ **Remote monitoring** | MQTT (HiveMQ Cloud, TLS) → Python dashboard |
| 🧪 **Prototype** | Wokwi simulation, low-cost components |

<img src="https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white" />
<img src="https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white" />
<img src="https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54" />
<img src="https://img.shields.io/badge/PlatformIO-F5822A?style=flat-square&logo=platformio&logoColor=white" />
<img src="https://img.shields.io/badge/Wokwi-simulation-1F6FEB?style=flat-square" />

---

## 💼 Experience

| Role | Where | Period |
|---|---|---|
| **Tech Lead**: UAV network & communication | Djayanta UAV Team | 2025 |
| **R&D Team Member** | UMPBOT | Present |
| **Intern**: Data & CS | <!-- TODO: nama perusahaan --> | 6 months |

---

## 🚀 Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🚁 <a href="https://github.com/OurinEdnes/A.R.C.S">A.R.C.S</a></h3>
      <b>Aerial Rescue & Color Search System</b><br/>
      Java prototype for search-and-rescue: HSV color detection and real-time object tracking on simulated camera input.<br/><br/>
      <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
      <img src="https://img.shields.io/badge/HSV-Tracking-0e75b6?style=flat-square" />
    </td>
    <td width="50%" valign="top">
      <h3>✋ HCI Hand-Landmark System</h3>
      <b>Gesture-based human-computer interaction</b><br/>
      MediaPipe hand-landmark detection for cursor control and a virtual keyboard.<br/><br/>
      <img src="https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square" />
      <img src="https://img.shields.io/badge/Computer%20Vision-203a43?style=flat-square" />
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>⌨️ TypeShark</h3>
      <b>Distraction-free typing tutor</b><br/>
      Desktop app built with Electron with real-time WPM and accuracy tracking.<br/><br/>
      <img src="https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white" />
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
    </td>
    <td width="50%" valign="top">
      <h3>🦈 <a href="https://github.com/OurinEdnes/finance-shark-bot">Finance Shark AI</a></h3>
      <b>AI assistant bot</b><br/>
      Monitors, analyzes, and sends automated notifications about management data.<br/><br/>
      <img src="https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54" />
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>📦 <a href="https://github.com/OurinEdnes/-Warehouse-management-application">Warehouse Manager</a></h3>
      <b>Hybrid data structure implementation</b><br/>
      Inventory, tracking, and order processing using Array, Stack, Queue, Linked List, and Tree.<br/><br/>
      <img src="https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54" />
    </td>
    <td width="50%" valign="top">
      <h3>🪐 3D Solar System</h3>
      <b>Computer graphics simulation</b><br/>
      3D simulation of the solar system and galaxy motion with C++ and OpenGL.<br/><br/>
      <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
      <img src="https://img.shields.io/badge/OpenGL-5586A4?style=flat-square&logo=opengl&logoColor=white" />
    </td>
  </tr>
</table>

<div align="center">

**[🌊 See all projects, screenshots & combat records on my portfolio →](https://ourinednes.github.io/)**

</div>

---

## 🛠️ Arsenal

**Programming & AI**<br/>
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python_(Flask)-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=for-the-badge)
![YOLO](https://img.shields.io/badge/YOLOv8_/_v11-111F68?style=for-the-badge)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white)

**Hardware & Comms**<br/>
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi_5-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![LoRa](https://img.shields.io/badge/LoRa-1F2937?style=for-the-badge)
![ExpressLRS](https://img.shields.io/badge/ExpressLRS-C62828?style=for-the-badge)
![GStreamer](https://img.shields.io/badge/GStreamer-2C5364?style=for-the-badge)
![MQTT](https://img.shields.io/badge/MQTT_/_HiveMQ-660066?style=for-the-badge&logo=mqtt&logoColor=white)
![PlatformIO](https://img.shields.io/badge/PlatformIO-F5822A?style=for-the-badge&logo=platformio&logoColor=white)
![Wokwi](https://img.shields.io/badge/Wokwi-1F6FEB?style=for-the-badge)

**Database**<br/>
![MySQL](https://img.shields.io/badge/MariaDB_/_SQL-003545?style=for-the-badge&logo=mariadb&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4ea94b?style=for-the-badge&logo=mongodb&logoColor=white)

**Design, Networking & Management**<br/>
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![DaVinci Resolve](https://img.shields.io/badge/DaVinci_Resolve-233A53?style=for-the-badge&logo=davinciresolve&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale-242424?style=for-the-badge&logo=tailscale&logoColor=white)
![Cisco](https://img.shields.io/badge/Cisco_Packet_Tracer-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)
![UML](https://img.shields.io/badge/Astah_UML-4A90D9?style=for-the-badge)
![Blender](https://img.shields.io/badge/Blender-F5792A?style=for-the-badge&logo=blender&logoColor=white)

---

## 🎓 Education & Achievements

| | |
|---|---|
| 🇲🇾 **UMPSA**: AIMS Exchange Scholar | Bachelor of Computer Science (Software Engineering) · Fall 2026 |
| 🇮🇩 **Universitas Ahmad Dahlan** | Informatics |
| 🏆 **The Best Student** | HMIF Public Speaking Training · 2024 |
| 🌏 **International Delegate** | iFUTURE 2026 Young Future Leaders Summit, WTC Kuala Lumpur |
| 📝 **Researcher / Author** | Submitted to JuTISI · Oct 2026 |

### 📜 Certifications & Training

| Certificate | Issuer | Date |
|---|---|---|
| **Gemini Certified Student (University)** | Google for Education | Oct 2026 (valid to 2029) |
| **Public Speaking Training**: *Dare To Speak To Get Attention* | B1GFAIR "RISE", Yogyakarta | Jan 2025 |
| **International Youth Goals**: Singapore, Malaysia & Thailand, Batch #2 (online selection program) | B1GFAIR x Olpedia Education Center | Apr 2025 |
| **National Seminar: Personal Branding** | B1GFAIR "RISE" x BEM FMIPA UNY | Jan 2025 |
| **National Seminar: Content Creator** | B1GFAIR "RISE" | Jan 2025 |
| **National Seminar: Mahasiswa Prestasi** | B1GFAIR "RISE" | Jan 2025 |

---

## 📊 GitHub Stats

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=OurinEdnes&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&bg_color=0d1117" />
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=OurinEdnes&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117" />

<img src="https://streak-stats.demolab.com?user=OurinEdnes&theme=tokyonight&hide_border=true&background=0d1117" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=OurinEdnes&theme=tokyo-night&hide_border=true&bg_color=0d1117&area=true" />

<br/><br/>

*"Swim through the code, don't just float on it."* 🦈

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=120&section=footer" alt="footer" />

</div>
