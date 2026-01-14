<img width="4000" height="1414" alt="5" src="https://github.com/user-attachments/assets/c2c8a50c-f973-4038-959b-bc3b7aec5543" />

# Tibetan Spirit: Digital Legacy System
### *Translating Biological Rhythms into Generative Art*

---

## Concept: The Frequency of Faith

This interactive installation perceives **"Faith"** as a unique spiritual frequency inherent to every individual. 

The system captures the viewer’s **breathing patterns** and **walking pace** through LiDAR sensing, real-time translating these delicate life signals into a **"Soul Flower"** blooming on a digital canvas. The morphology, color, and complexity of each flower are uniquely sculpted by the participant's biometric data. 

As participants move on, their flowers don't disappear; they migrate to the edges of the screen, gathering into a **"Symbiotic Garden"**—a collective digital legacy woven from the breath of many.

---

## Technical Architecture

The core of this project is a **Digital Legacy System** written in Python, designed to handle real-time signal processing and generative visualization.

### 1. Biometric Signal Processing
* **Smoothing Algorithm**: Uses a low-pass filter (Alpha-smoothing) to clean raw sensor data, ensuring the "flower" reacts fluidly rather than erratically.
* **Latent Mapping**: Maps breath depth and step speed into normalized latent parameters to drive generative attributes.

### 2. Generative Logic
* **Morphology**: The number of petal layers is driven by the `breath_latent` variable (1 to 7 layers).
* **Color Theory**: A linear interpolation (`lerp`) function transitions colors between "Calm" (Blue) and "Vivid" (Pink) based on walking intensity.
* **Contour**: Logic gates determine if the flower's edges are "Smooth" (low intensity) or "Sharp" (high intensity).

### 3. Archive & Legacy System
* **Mandala Database**: A structured logging system that archives every "Soul Flower" with its coordinates and timestamps, managing a maximum of 240 concurrent entries to maintain a balanced collective ecosystem.

---

## Tech Stack
* **Language**: Python 3.9
* **Interface**: Tkinter (Real-time GUI Rendering)
* **Concepts**: Human-Computer Interaction (HCI), Biometric Art, Generative Design, Signal Filtering.
