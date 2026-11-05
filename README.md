# TinyML Workshop

**Exploring Tiny Machine Learning (TinyML) — From Model Development to Embedded Deployment**

## Overview

This repository contains the resources, code, datasets, models and documentation for a hands-on TinyML workshop.

TinyML focuses on running machine learning models on resource-constrained embedded devices and microcontrollers. It brings together machine learning, embedded systems and hardware-level implementation to enable intelligent processing directly on edge devices.

The repository is organized to support the workflow from data collection and model development to model conversion and deployment on embedded hardware.

## What is TinyML?

TinyML is the implementation of machine learning algorithms on low-power, memory-constrained devices such as microcontrollers and embedded development boards.

Unlike conventional machine learning systems that rely on cloud servers, TinyML enables:
- On-device inference.
- Reduced communication latency.
- Lower power consumption.
- Reduced dependence on internet connectivity.
- Edge-based intelligent applications.

## Repository Contents

| Directory / File | Description |
|---|---|
| `Data_Logger/` | Resources related to collecting and logging sensor data |
| `Datasets/` | Datasets used for model development and experimentation |
| `Documentation/` | Workshop notes, instructions and technical references |
| `Models/` | Machine learning model resources |
| `ONNX/` | ONNX model-related resources |
| `Python/` | Python scripts and model development utilities |
| `STM32/` | STM32-related embedded implementation resources |
| `Utilities/` | Supporting scripts and tools |
| `.vscode/` | VS Code workspace configuration |
| `simple_model.onnx` | ONNX model file |
| `simple_model.onnx.data` | Associated ONNX model data |

## Technologies and Tools

- **Python** – Data processing and model development
- **Machine Learning** – Model training and inference
- **ONNX** – Model representation and interoperability
- **STM32** – Embedded deployment platform
- **Embedded Systems** – Microcontroller-based implementation
- **Visual Studio Code** – Development environment

## Typical TinyML Workflow

```text
       Sensor Data Collection
                 |
                 v
          Data Preprocessing
                 |
                 v
          Model Development
                 |
                 v
           Model Training
                 |
                 v
          Model Conversion
                 |
                 v
        Embedded Deployment
                 |
                 v
         On-Device Inference
```

## Learning Objectives

Through this workshop, participants can explore:

1. Fundamentals of TinyML and Edge AI.
2. Sensor data collection and dataset preparation.
3. Basic machine learning model development.
4. Model formats and ONNX interoperability.
5. Deployment concepts for resource-constrained hardware.
6. STM32-based embedded machine learning.
7. The interaction between software, hardware and machine learning.

## Getting Started

### Prerequisites

- Basic Python programming knowledge.
- Familiarity with embedded systems and microcontrollers.
- Basic understanding of machine learning concepts.
- Visual Studio Code or another compatible development environment.

### Clone the Repository

```bash
git clone https://github.com/may13-o/TinyML-Workshop.git
cd TinyML-Workshop
```

Explore the directories to find the relevant scripts, datasets, models and hardware-specific resources.

Refer to the `Documentation/` directory for additional instructions.

## Applications of TinyML

TinyML can be applied in several real-world domains:

- Smart sensor systems.
- Predictive maintenance.
- Industrial monitoring.
- Wearable devices.
- Smart agriculture.
- Environmental monitoring.
- Voice and gesture recognition.
- Low-power IoT devices.

## Repository Structure

```text
TinyML-Workshop/
│
├── Data_Logger/
├── Datasets/
├── Documentation/
├── Models/
├── ONNX/
├── Python/
├── STM32/
├── Utilities/
│
├── .vscode/
├── .gitignore
├── simple_model.onnx
├── simple_model.onnx.data
└── README.md
```

## Author

**Mayur Kharvi**

Electronics and Communication Engineering  
Advanced Communication Technology  
NMAM Institute of Technology

GitHub: [@may13-o](https://github.com/may13-o)

---

*Learning and experimenting with TinyML, Edge AI and embedded machine learning.*
