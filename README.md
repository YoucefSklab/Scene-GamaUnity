# Scene-GamaUnity

Scene-GamaUnity is a **generic tool for participatory modeling and simulation** that enhances the GAMA platform by enabling real-time stakeholder interaction. It allows users to **create remote control interfaces** to interact dynamically with agent-based simulations, making it particularly useful for **serious games and decision-making support systems**.

## Overview

In recent years, agent-based simulation models have been widely used to study complex systems across various domains. However, **most existing simulation tools lack support for real-time stakeholder interaction**, making them unsuitable for participatory modeling and simulation scenarios.

**Scene-GamaUnity bridges this gap by providing a remote control interface for the GAMA platform**, enabling stakeholders to modify model parameters and observe the impact of their decisions in real time.

## Key Features

- **Remote Control Interfaces**: Create and configure remote control panels with generic UI elements (buttons, checkboxes, dialogs, selection boxes, text inputs, etc.).
- **Cross-Platform Compatibility**: The Unity client can run on multiple devices, including Android, without requiring GAMA installation.
- **Seamless GAMA Integration**: Implements a new agent skill (`unity`) to communicate with the GAMA platform.
- **Real-Time Interaction**: Enables stakeholders to modify parameters and receive immediate feedback during simulation.
- **MQTT Communication Protocol**: Ensures efficient data exchange between Unity and GAMA.

## System Architecture

Scene-GamaUnity consists of two main components:

1. **GAMA Plugin**: Introduces a new agent skill (`unity`) in GAMA to enable remote interactions.
2. **Unity Client**: A generic Unity scene that serves as the **user interface** for remote control, allowing stakeholders to interact with GAMA simulations from various devices.

## Installation

### Prerequisites

- [GAMA Platform](https://gama-platform.org/) installed.
- [Unity](https://unity.com/) installed to run the Unity client.
- An MQTT broker (e.g., [Eclipse Mosquitto](https://mosquitto.org/)) for communication.

### Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/YoucefSklab/Scene-GamaUnity.git
   
