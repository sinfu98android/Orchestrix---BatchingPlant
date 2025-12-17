# Industrial Batching Plant Automation

**Project: Orchestrix Batching Plant**<br>
*[🔗  powered by Orchestrix Framework](https://github.com/sinfu98android/Orchestrix_main_framework)*

 
<br><br>
Orchestrix Batching Plant is a real-world industrial automation system powered by the Orchestrix Framework, designed to control multiple batching lines with high-speed, low-latency, middleware-free orchestration. It integrates PLCs, load cells, and a web-based HMI to provide real-time batching, monitoring, and analytics. Deployed in production for over 2 years, it has reduced staffing requirements, lowered maintenance costs by 30%+, and enabled predictive maintenance and operational insights. All system architecture, framework, PLC integration, and on-site commissioning were designed and implemented by the author.<br>

## 🛠 Development Notes
- Before Orchestrix, implementing a full batching plant system typically required **~2 weeks**.  <br>
- Using the Orchestrix framework, the same system can be implemented in **~1 week**, by reusing orchestration logic, workflow management, and integration code.  <br>
- Framework-enabled development reduces repeated boilerplate, allowing focus on project-specific behavior.<br>


#### 🎥**Watch a video of the commissioning and on-site trial** of the Batching Plant system
![  Batching Plant system video](https://github.com/sinfu98android/Orchestrix_BatchingPlant/blob/79f43c33b88d44096f15782fb4bdf8cbc0b957aa/Youtube%20Cover%20%5BJPG%5D)(https://youtu.be/asrHC0f4MmY?si=lkpU2SrsDjZ1knN6) <br><br>

## 📦 Shipping & Deployment

- Successfully shipped and deployed in a real industrial production environment<br>
- In continuous operation for **2+ years** with high reliability<br>
- Fully commissioned on-site, including PLC integration, calibration, and operator validation<br>
- Supports remote updates, monitoring, and troubleshooting without disrupting <br>


### 🏗 System Architecture

Frontend (Web UI) <br>
  ↓ <br>
Backend (PHP + C/C++ Runtime) <br>
   ↓ <br>
Memcache (Queue + Cache Layer) <br>
   ↓ <br>
MySQL Database <br>
   ↓ <br>
PLC / Load Cell Devices <br>

**Network & Protocol Support** <br>
•	TCP / RS485 <br>
•	Local network or cloud-based control <br>
•	No OPC server required <br>

### ⚙️ Tech Stack <br>
•	Frontend: JavaScript web UI <br>
•	Backend: PHP <br>
•	Low-Level Drivers: Custom C/C++<br>
•	Caching/Queue: Memcache <br>
•	Database: MySQL <br>
•	Deployment: FTP (WinSCP – legacy industrial environments) <br>


### 🚀 Batching Plant Features 
**Core Features** <br>
•	ERP → Automatic batching job creation <br>
•	Real-time ingredient weighing <br>
•	Automatic sequence control (mixing, dosing, loading) <br>
•	Load cell amplifier integration <br>
•	Remote I/O & PLC command execution <br>
•	Real-time runtime logging <br>
•	Event monitoring + alarms <br>
•	Full traceability (batch history) <br>

**Operational Features** <br>
•	Multi-plant centralized web control <br>
•	1 operator can run multiple batching lines <br>
•	Remote troubleshooting & maintenance <br>
•	Brand-agnostic hardware support <br>
•	Very lightweight (no middleware bridge needed) <br>


### ⚡ Performance & Impact <br> 
•	2+ years continuous operation in real industrial environment <br>
•	Reduced downtime via predictive maintenance <br>
•	OEE insights for cycle time, machine utilization, quality <br>
•	Faster troubleshooting with centralized logs <br>
•	Reduced staffing, previous 1 operator 1 batching plant → 1 operator can handle multi batching plant <br>
•	Seamless remote access lowers onsite technician visits <br>
• Brand-agnostic design reduces machine and maintenance costs by ~30%+ compared to original vendor parts  

### 📊 Data Intelligence & Analytics <br>
**Orchestrix generates:** <br>
•	Material accuracy variance <br>
•	Cycle time distribution <br>
•	Batch quality metrics <br>
•	Equipment error patterns <br>
•	Predictive failure alerts<br>
•	Production volume summaries <br>
•	Capable of weighing operations without job order <br>
•	Minimizes material corruption and theft <br> 
•	Provides deep analysis and historical quality records for batching plant performance <br>


### 🧩 PLC Edge Integration <br>
**Orchestrix communicates directly with:** <br>
•	Mitsubishi PLCs <br>
•	Omron PLCs <br>
•	Schneider PLCs (Modbus) <br>
•	Modbus TCP devices <br>
•	Load cell amplifiers <br>
**This allows:** <br>
•	Fast message response <br>
•	Custom low-level C/C++ driver handling <br>
•	No OPC server required <br>
•	High performance in constrained environments <br>

### 👨‍💻 Author Contribution <br>
This system and all components described in this document—including the architecture, PLC protocol implementation, runtime modules, backend services, data intelligence layer, and on-site commissioning—were fully designed and developed by the author. <br><br>
 
### Technical Batching Plant pdf
[📎  download technical pdf](https://github.com/sinfu98android/Orchestrix_BatchingPlant/blob/eede6d837fe12a0d6a4999ec92bdf4642d41918e/Batching%20plant%20Technical%20PDF.pdf)   <br>
*Note : Github Sometimes cannot preview PDF file directly, please download to view.*
<br><br>
![System Architecture & Impact](https://github.com/sinfu98android/Orchestrix_BatchingPlant/blob/66e8c4249e480d7ae174f78da01db4e5ae3e1bdf/BatchingPlant_Orchestrix_Architecture_Impact.png.jpg)

<br><br>
### 🏭 Field Deployment

The batching plant automation system is powered by the **Orchestrix Framework**, providing deterministic, middleware-free control and HMI.  

This **panel** represents the heart of the system, installed in the field and used in production. It demonstrates:

- Real industrial deployment  
- Integration of HMI, PLC logic, and Orchestrix orchestration  
- Reliable, long-term operation in a factory environment

![Panel Box](https://github.com/sinfu98android/Orchestrix_BatchingPlant/blob/e3a5f0dc5a76fb12e12defcc5a47e2ef107af28d/Images/Box%20Panel-1)

![Panel Box](https://github.com/sinfu98android/Orchestrix_BatchingPlant/blob/e3a5f0dc5a76fb12e12defcc5a47e2ef107af28d/Images/Box%20Panel-2)
### Skills
C/C++ | Automation | Linux | Embedded Communication | Embedded Firmware | HMI | R&D | Web & Runtime Architecture |Software development | Programming | motion control | RTOS

### This Batching Plant system is built on top of the Orchestrix framework <br>
[🔗  Orchestrix Framework link](https://github.com/sinfu98android/Orchestrix_main_framework) 
Check it out!

### Contact 
[Linkedin - Yudi Hariyanto](https://www.linkedin.com/in/yudi-hariyanto-2732462a3?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) <br>
Feel free to contact for questions, collaborations, or technical discussion
