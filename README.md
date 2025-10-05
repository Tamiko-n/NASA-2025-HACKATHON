# 🌌 Cosmic Mayhem

**Interactive 3D Asteroid Impact Visualization Platform**  
Built for the **NASA Space Apps Challenge 2025**

---

## 🔹 Project Title
**Cosmic Mayhem**

---

## 🔹 Problem Statement

Near-Earth asteroids like *Impactor-2025* pose significant risks to our planet.  
Current systems primarily **detect** these asteroids but fail to help the public or decision-makers **visualize and understand** their potential impact.

While NASA and USGS publish detailed datasets on asteroid trajectories, geological layers, elevation, and human exposure, these data sources remain **fragmented and difficult to interpret**.

**Cosmic Mayhem** bridges this gap through a **3D, data-driven web visualization platform** that combines NASA and USGS data to simulate and visualize asteroid behavior, potential impact zones, and recommended mitigation strategies — making complex space data **accessible, interactive, and educational**.

---

## 🔹 Project Description

**Cosmic Mayhem** allows users to explore a 3D model of Earth surrounded by dynamic, orbiting asteroids using **real NASA asteroid datasets**.  
Each asteroid can be clicked to reveal its physical and orbital characteristics, such as:

- Diameter  
- Magnitude  
- Orbit class  
- Eccentricity  
- Inclination  
- Hazardous status  

Users can adjust simulation speed, observe asteroid motion, and scroll to access additional data about **future threats** and **planetary safety guidelines**.

---

## 🔹 How It Works

### 🧠 Core Logic & Flow
1. **Data Input:**  
   Static asteroid data (real NASA NEO dataset) is loaded into JavaScript objects.

2. **3D Environment Creation:**  
   - Earth and its atmosphere are rendered using **Three.js** with NASA textures.  
   - Lighting and star fields simulate a realistic space environment.

3. **Asteroid Simulation:**  
   - Each asteroid’s orbit, rotation, and trajectory are modeled around Earth.  
   - Clicking on any asteroid reveals detailed NASA-based metrics in a dynamic info panel.

4. **User Interaction:**  
   - Speed controls allow users to toggle between *Slow*, *Normal*, and *Fast* orbital speeds.  
   - Camera rotation and zoom are managed with custom `SimpleOrbitControls`.  
   - The interface includes real-time threat alerts and safety guidelines below the 3D view.

---

## 🔹 Technical Architecture

**Frontend Stack:**
- **HTML5, CSS3, JavaScript (ES6)**
- **Three.js** for 3D visualization

**Data Sources:**
- NASA Near-Earth Object (NEO) dataset  
- USGS Earthquake & Geological Data  
- ESA Space Situational Awareness  
- JPL Small-Body Database

**APIs & References:**
- NASA NEO API  
- USGS Earthquake Map (embedded link)  
- Planetary Defense Coordination Office resources

---

## 🔹 Features

✅ **3D Interactive Earth Model** — with realistic textures, lighting, and clouds  
✅ **Clickable Asteroids** — view real parameters for each near-Earth object  
✅ **Speed Control System** — simulate asteroid orbit velocity  
✅ **Threat Visualization Panel** — future threats, statistics, and global impact alerts  
✅ **Precautionary Section** — safety guide for public awareness  
✅ **Educational Design** — for students, enthusiasts, and decision-makers  

---

## 🔹 Benefits

- Transforms **raw NASA/USGS data** into an **interactive 3D experience**  
- Helps users **visualize planetary threats** in real time  
- Increases **public awareness and preparedness**  
- Supports **scientific outreach and education**

---

## 🔹 Intended Impact

The project democratizes access to **space hazard intelligence**, empowering the public, educators, and policymakers with visual, actionable insights into potential asteroid threats and Earth’s defense readiness.

It turns technical astrophysical data into a **tool for awareness, education, and proactive risk mitigation**.

---

## 🔹 Tools, Technologies & Platforms

| Category | Tools / Frameworks |
|-----------|--------------------|
| **Languages** | HTML, CSS, JavaScript |
| **Libraries** | Three.js (r128) |
| **Data APIs** | NASA NEO API, USGS Earthquake API |
| **Visualization** | 3D orbit simulation using Three.js |
| **Hosting** | Vercel |

---

## 🔹 Creativity & Innovation

- Combines **space and Earth science datasets** for a unified visual platform  
- Uses **real-time 3D rendering** rather than static charts  
- Introduces **educational storytelling** through interactive exploration  
- Bridges **data science and public awareness** with an immersive interface  

---

## 🔹 Design & Ethical Considerations

- Ensures **scientific accuracy** via trusted data sources (NASA, USGS, ESA)  
- Designed for **accessibility** and educational clarity  
- Optimized for **browser performance** even on lower-end devices  
- Promotes **awareness over fear** — focusing on preparedness and learning  

---

## 🔹 Future Improvements

🚀 **AI-driven Predictive Impact Simulation** — calculate realistic collision zones and energy outputs  
🌍 **Live Data Integration** — fetch live NASA NEO feeds for ongoing asteroid tracking  
🛰️ **Disaster Alert System** — integrate with global alert APIs for real-time updates  
📊 **Data Dashboard** — show population, geography, and environmental exposure metrics  

---

## 🔹 Team Members

| Name | Role |
|------|------|
| **Sadia Naeem** | Project Lead |
| **Mustufa Asad** | Data Scientist & Researcher |
| **Anusha Fatima** | Frontend Developer & 3D Developer |
| **Muskan Shafique** | UI/UX Designer |
| **Syeda Hasfa Tariq** | Astronomy Consultant |
| **Tamia Naeem** | Safety Research Specialist |

---

### 🌠 Live Demo / Preview
*(Add your hosted link once deployed on GitHub Pages or Netlify)*  
👉 **[View Cosmic Mayhem Online](https://your-live-demo-link.com)**
