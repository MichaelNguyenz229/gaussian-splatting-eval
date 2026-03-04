# Gaussian Splat Evaluation & Simulation Environment

An exploration into capturing real-world environments and assets via **Gaussian Splatting** and converting them into high-fidelity 3D meshes for robotics simulation pipelines.

## Live Demo
[View the Interactive 3D Viewer](https://michaelnguyenz229.github.io/gaussian-splatting-eval/)
*Includes OctoTest, 2019 Prius XLE, and Tesla Optimus captures.*

## 🛠 Tech Stack
* **Capture:** Luma AI (Neural Radiance Fields / Gaussian Splatting)
* **Rendering:** Three.js / WebGL / lil-gui
* **Format:** GLB (Binary glTF) - Optimized for web performance and simulation compatibility.

##  Robotics & Simulation Context
The goal of this project is to evaluate the feasibility of using mobile-captured 3D data as a rapid prototyping tool for:
1. **Scene Generation:** Creating digital twins of real-world environments.
2. **Object Isolation:** Evaluating Luma AI's ability to "crop" and segment specific assets (like a Prius or Optimus) from the background.
3. **Collision Mapping:** Testing how mesh density affects robotic agent interaction in simulators like Isaac Sim or MuJoCo.

##  Scans & Assets Gallery

### Tesla Optimus (Gen 2) Evaluation
This scan focuses on capturing a complex humanoid form. The process involved defining a precise 3D bounding box to isolate the agent from the environment.

**Pre-Scan Bounding Process:**
| Left View | Right View |
| :---: | :---: |
| ![Pre-Scan Left](images/Pre-Scan-Left.jpg) | ![Pre-Scan Right](images/Pre-Scan-Right.jpg) |
| *Defining the front center point.* | *Defining the 180° rear boundary.* |

---

### Asset Library
| Capture Name | Description | Status |
| :--- | :--- | :--- |
| **Tesla Optimus** | Humanoid agent scan for kinematic study. |  Mesh Generated |
| **2019 Prius XLE** | Large-scale object capture to test texture baking on reflective surfaces. | Mesh Generated |
| **OctoTest** | Baseline test for poly-count and browser performance. |  Complete |

##  Roadmap
- [x] Multi-model Three.js web viewer with interactive UI.
- [ ] **Library Expansion:** Build a robust library of "Simulation-Ready" assets.
- [ ] **Physics Integration:** Generate URDF/XML files from these meshes for robotic interaction testing.