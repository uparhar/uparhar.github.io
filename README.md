# Uplove Parhar — Electrical Engineering & Robotics Portfolio

Welcome to my professional portfolio! This site showcases my work in embedded systems, PCB design, robotics, and IoT development.

## 🌐 Live Portfolio
**Visit:** [uparhar.github.io](https://uparhar.github.io)

---

## 📋 About

I'm an engineering student at **UBC Okanagan** (BASc, integrated dual-degree program) with a **GPA of 3.65/4.0**. As **electrical subteam lead** on **Okanagan Marine Robotics**, I'm developing an autonomous underwater vehicle for RoboSub 2025.

My expertise spans:
- **Embedded Systems:** STM32 (HAL/LL, FreeRTOS), ESP32, ARM architecture
- **PCB Design:** Altium Designer, KiCAD, custom board bring-up, hand soldering
- **Power Electronics:** LiPo management, DC-DC conversion, motor control, protection circuits
- **Robotics & Control:** ROS2, PID systems, IMU sensor fusion, AUV architecture
- **Machine Learning:** PyTorch, YOLO11, computer vision pipelines
- **Full-Stack IoT:** Flask, ThingSpeak, embedded telemetry systems

---

## 🚀 Featured Projects

### 1. **Ogopogo — Autonomous Underwater Vehicle** (RoboSub 2025)
- **Role:** Electrical subteam lead, full system architecture
- **Highlights:**
  - Designed custom STM32F765VGT6 main MCU board in Altium Designer (55% cost reduction)
  - Built reusable FTDI USB-to-JTAG/SWD debug interface (60% faster setup)
  - Diagnosed and resolved complex hardware faults through systematic debugging
  - Implemented FreeRTOS firmware with ROS2 integration
- **Tech:** STM32, Altium Designer, FreeRTOS, ROS2, Power Electronics

### 2. **Ocean Acidification Monitoring Buoy**
- **Recognition:** City of Kelowna environmental initiative
- **Highlights:**
  - Full IoT platform: ESP32 sensing + ThingSpeak telemetry
  - ML model trained with PyTorch to predict acidification trends
  - Flask dashboard with real-time sensor data and AI-powered insights
  - 3D-printed enclosure with custom sensor mounts
- **Tech:** ESP32, PyTorch, Flask, ThingSpeak, SolidWorks

### 3. **Personal Mini Submarine**
- Origin project for robotics journey
- **Highlights:**
  - Full closed-loop PID control with IMU feedback
  - Raspberry Pi + Blue Robotics T200 thruster integration
  - Custom kill switch PCB
  - ESC arming sequence debugging
- **Tech:** Raspberry Pi, PID Control, PWM Motor Control, Custom PCB

### 4. **Custom STM32 Main Controller Board**
- Ground-up PCB design in Altium Designer
- Optimized regulator and protection circuitry selection
- Full board bring-up with oscilloscope debugging
- Resolved SWD trace faults through creative problem-solving

### 5. **Computer Vision Pipeline (YOLO11)**
- OKMR ODST object detection system
- Zero-shot auto-labeling with Grounding DINO
- PyTorch training pipeline

### 6. **Power Distribution & LiPo Management**
- Custom isolation board with optocoupler PWM handling
- Fault isolation and PCB repair expertise
- Multi-domain voltage conversion

### 7. **Reusable FTDI Debug Interface**
- Universal SWD/JTAG connectivity tool
- 60% reduction in debugging setup time
- PlatformIO integration

---

## 🔧 Technical Skills

### Embedded & MCU
- STM32 (HAL/LL drivers, FreeRTOS, bare-metal)
- ESP32, Arduino, PlatformIO
- Real-time kernel design, task scheduling

### PCB & Hardware
- **Altium Designer** (schematic, multi-layer layout)
- **KiCAD** design and routing
- Hand soldering (SMD/THT), component selection
- Hardware debugging (SWD/JTAG, oscilloscope, multimeter)

### Power Electronics
- LiPo battery management systems
- DC-DC buck/boost converter design
- Motor control (PWM, ESC arming)
- Protection circuitry (fuses, TVS diodes, thermal management)

### Robotics & Control Systems
- **ROS2** / DDS middleware
- PID control loops
- IMU sensor fusion (gyro, accel integration)
- Autonomous vehicle architecture
- Thruster/motor vectoring

### Machine Learning & Computer Vision
- **PyTorch**, YOLO11, Grounding DINO
- Graph Neural Networks (GNNs), XGBoost
- Object detection training pipelines
- Zero-shot learning approaches

### Software & IoT
- **C/C++**, Python, Java
- **Flask** full-stack web applications
- **ThingSpeak** IoT telemetry
- Embedded protocols: CAN, I2C, SPI, UART, USB
- **Git** version control and collaboration

### Design & CAD
- **SolidWorks** 3D modeling
- 3D printing and prototyping
- Sensor mount design
- Mechanical tolerance analysis

---

## 📚 Education

- **UBC Okanagan** | Bachelor of Applied Science (Electrical Engineering)
  - Integrated dual-degree program (Sept 2025–present)
  - GPA: 3.65/4.0
  - Relevant Coursework: CAD, Engineering Instrumentation, Electromagnetics, Dynamics, Sustainable Design

---

## 💼 Work Experience

**Physiotherapy Assistant — Macleod Physiotherapy** (Sept 2023 – Feb 2025)
- Operated therapeutic equipment (ultrasound, TENS) supporting patient care
- Led and trained volunteer PTAs, improving consistency during peak hours

---

## 🛠️ Portfolio Structure

```
uparhar.github.io/
├── index.html              # Main portfolio page
├── css/
│   └── style.css           # Professional styling & animations
├── js/
│   └── main.js             # Interactive features & smooth scrolling
└── README.md               # This file
```

---

## 🎨 Features

✨ **Modern, Responsive Design** — Works beautifully on desktop, tablet, and mobile  
🎯 **Project Showcase** — Detailed cards for each major project  
📊 **Skills Section** — Organized by technical domain  
⚡ **Smooth Animations** — Professional transitions and scroll reveals  
🔗 **Easy Contact** — Direct links to email, GitHub, LinkedIn

---

## 🚀 Customization Guide

### Edit Your Bio
- Update the hero section in `index.html`
- Modify the "About" section with your background

### Update Projects
Add new project cards by copying this template:

```html
<div class="project-card">
    <div class="project-image" style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);">
        <i class="fas fa-microchip"></i>
    </div>
    <h3>Project Title</h3>
    <p class="project-subtitle">Subtitle or role</p>
    <p>Project description with technical details and accomplishments.</p>
    <div class="project-tags">
        <span class="tag">Technology 1</span>
        <span class="tag">Technology 2</span>
    </div>
    <a href="#" class="project-link">View Details →</a>
</div>
```

### Modify Colors
Edit CSS variables in `css/style.css`:

```css
:root {
    --primary-color: #00d4ff;      /* Cyan accent */
    --secondary-color: #0a1428;    /* Dark blue */
    --accent-color: #ff6b6b;       /* Red highlight */
}
```

### Update Skills
Modify the skills grid in the **Skills** section to match your expertise.

### Add Contact Info
Update links in the **Contact** section:
- Email address
- GitHub profile
- LinkedIn profile
- Phone number

---

## 📝 Best Practices for EE/Robotics Portfolios

1. **Include Technical Details** — Specify hardware (chip names, board versions)
2. **Document Architecture** — Explain system design, signal flow, control loops
3. **Show Problem-Solving** — Highlight debugging approach, trade-offs, lessons learned
4. **Link GitHub Repos** — Direct visitors to full source code and documentation
5. **Add Schematics/Diagrams** — Include circuit diagrams, PCB layouts, block diagrams
6. **Showcase Results** — Performance metrics, test results, competition placements
7. **Update Regularly** — Keep portfolio fresh with new projects and achievements

---

## 🌟 Quick Tips

- **Professional Photos** — Include clear images of prototypes and test setups
- **Performance Metrics** — Document power consumption, response times, accuracy
- **Test Data** — Show oscilloscope captures, sensor readings, control response plots
- **CAD Models** — Link to 3D renderings or STEP files
- **Video Demos** — Embedded videos of systems in action (especially for robotics)

---

## 📄 License

This portfolio template is open source. Feel free to adapt it for your own projects!

---

## 🤝 Let's Connect

- **Email:** uploveparhar@gmail.com
- **GitHub:** [github.com/uparhar](https://github.com/uparhar)
- **LinkedIn:** [linkedin.com/in/uplove-p](https://linkedin.com/in/uplove-p)
- **Location:** Kelowna, BC

---

**⚡ Building the future, one circuit at a time.**
