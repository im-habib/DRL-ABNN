# Neurasynk: Adaptive Brain Network Neurofeedback

**Neurasynk** is a cutting-edge research project focused on modulating functional brain connectivity using **Deep Reinforcement Learning (DRL)**. By shifting the paradigm from localized power-band training to global network-level interactions, Neurasynk provides a personalized, dynamic, and high-precision neurofeedback experience.

---

## 🚀 Project Overview

Traditional neurofeedback often targets isolated brain regions. **Neurasynk** treats the brain as a complex, dynamic graph. By utilizing a closed-loop system, it identifies real-time synchronization patterns and uses a DRL agent to "nudge" the brain toward more efficient network states.

* **Status:** Ongoing (Started 2025)
* **Type:** Neural Engineering / Artificial Intelligence
* **Target:** Functional Connectivity (EEG-based)

---

## 🛠 System Workflow

The system operates in a high-speed, closed-loop pipeline to ensure timing-dependent plasticity:

1. **Acquisition:** Real-time EEG streaming via **Lab Streaming Layer (LSL)**.
2. **Preprocessing:** Artifact rejection (EOG/EMG) using GPU-accelerated **ICA**.
3. **Feature Extraction:** Generating  connectivity matrices using **Phase Locking Value (PLV)**.
4. **DRL Decision:** A **Proximal Policy Optimization (PPO)** agent evaluates the brain state.
5. **Feedback Delivery:** Real-time stimulus modulation (Visual/Auditory) via **Unity** or **PsychoPy**.

---

## 🧠 DRL Framework

The project treats neurofeedback as a **Markov Decision Process (MDP)**:

* **State Space ():** High-dimensional vectors representing graph metrics (Global Efficiency, Clustering Coefficients, and Node Degrees).
* **Action Space ():** Continuous control of feedback parameters (e.g., stimulus opacity, audio frequency, or task difficulty).
* **Reward Function ():** 


*Where  represents target connectivity and  is a penalty for signal noise or physiological artifacts.*

---

## 📊 Expected Outcomes

### **Technical Metrics**

* Achieve a total system latency of **<150ms**.
* High stability and convergence of the DRL agent within single sessions.

### **Neural Impact**

* Significant increase in the **Small-World Index** of functional networks.
* Strengthened connectivity within the **Dorsolateral Prefrontal Cortex (dlPFC)** for cognitive control.

### **Cognitive Impact**

* Measurable improvement in **Working Memory (N-back)** and **Inhibitory Control (Stroop)**.
* Demonstrable "Transfer Effects" where neural optimization persists without active feedback.

---

## 💻 Technical Stack

| Category | Tools |
| --- | --- |
| **Neuroscience** | MNE-Python, LSL, AntNeuro/Enobio EEG |
| **Machine Learning** | PyTorch, Gymnasium, Scikit-learn |
| **Signal Processing** | CuPy (GPU Acceleration), Riemannian Geometry |
| **Interface/VR** | Unity 3D, PsychoPy |
| **Data Standard** | BIDS (Brain Imaging Data Structure) |
