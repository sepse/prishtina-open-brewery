# Prishtina Open Brewery 🍻🔧
## Overview

**Open Source Brewery** is a research and development initiative exploring how open source technologies can optimize and reimagine the craft of beer brewing. Brewing is a complex and delicate process — one that requires careful control over temperature, timing, fermentation dynamics, and ingredient ratios. This project uses open source hardware and software as a testing ground to improve brewing precision and to foster innovation through community-driven experimentation.

Our goal is to empower brewers, makers, and researchers by providing open access to tools, prototypes, data, and methodologies that enhance brewing outcomes through smart, tech-enabled systems.

## Why Open Source? 🌍

Open source enables a collaborative environment where innovation is accelerated, transparency is built-in, and experimentation is accessible to all. In the brewing context, this means:

- 🔧 Developing custom monitoring and control systems with microcontrollers and sensors.
- 📡 Gathering and sharing real-time brewing and fermentation data.
- 🧠 Leveraging Machine Learning and LLMs to assist in recipe development.
- 📚 Publishing all findings, code, and brewing recipes under open licenses for community use and iteration.

## Core Technologies ⚙️

### 🖥️ Microcontrollers & Sensors
We utilize a range of open hardware platforms to build modular systems for real-time monitoring and control:
- **Microcontrollers**: ESP8266, ESP32, and Arduino boards.
- **Sensors**: 
  - Temperature and humidity sensors (for mash, fermentation, and storage)
  - CO₂ sensors (for fermentation tracking)
  - Flow sensors (for draft line monitoring and dispensing metrics)

### 🍺 Prototypes

#### 🔄 Beer-O-Meter
A custom device that:
- Measures flow in real-time using a flow sensor.
- Displays live output on 8x8 RGB LED Neomatrix panels.
- Controls draft access via RFID authentication.
- Helps breweries quantify and manage dispensing more accurately.

#### 🌡️ Fermentation Maintenance
- Temperature and CO₂ sensors embedded in fermentation chambers.
- Wireless data logging using ESP-based devices.
- Planned expansion to active heating/cooling control for automated fermentation curve management.

### 🧠 Machine Learning & Large Language Models
We explore the use of AI in brewing through:
- **Recipe Generation**: Using LLMs trained or prompted with datasets of brewing recipes and sensory profiles to suggest novel or optimized brews.
- **Data-Driven Brewing**: Applying ML models to historical brewing logs to predict outcomes or identify optimal process variables.
- **Natural Language Interfaces**: Enabling conversational interfaces where users can ask questions like *"Suggest a hoppy IPA recipe based on what’s in my fridge."*

### 🖥️ Microprocessor Integration
- **Raspberry Pi** devices serve as local servers for sensor aggregation, display dashboards, and logging.
- Python scripts and web-based dashboards provide real-time visualization and analysis of brewing parameters.

## Community Impact 🤝

This project is not only a toolset — it's a platform for **citizen science** and **open innovation** in brewing. By sharing knowledge, tools, and results, we invite brewers, engineers, data scientists, and hobbyists to:

- Collaborate on hardware and software development.
- Run their own experiments and share results.
- Contribute new sensor integrations, dashboards, or ML models.
- Participate in data collection for AI training.

## Open Resources 📂

- ✅ All source code (firmware, backend, ML scripts)
- ✅ Hardware schematics and BOMs
- ✅ Brewing logs and datasets (for ML experimentation)
- ✅ Open recipe database (community-submitted + AI-generated)
- ✅ Step-by-step build instructions

## Project Status 🛠️

| Component                | Status          |
|--------------------------|-----------------|
| Nano-brewery setup       | ✅ Complete     |
| Beer-O-Meter             | ✅ Operational  |
| Fermentation monitoring  | ⚙️ In testing  |
| ML recipe generation     | 🧪 Prototyping |
| Public documentation     | 📚 In progress |

---

## Get Involved 👥

This is a living, evolving project. You can:
- Fork the repo and contribute new features or fixes
- Share your brewing logs for AI experimentation
- Propose improvements to hardware designs
- Help test sensor integrations or control loops
- Add your own brewing recipes to the public collection

---

**Let’s brew smarter, together.** 🍻  
Explore the code, build your own system, and join a community where technology and tradition come together to make better beer.

🔗 [See more at github.com/sepse](https://github.com/sepse)
