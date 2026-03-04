# Gaussian Splat Evaluation & Simulation Environment

An exploration into capturing real-world environments and assets via modern 3D reconstruction tecniques: **Gaussian Splatting + NeRF** and converting them into high-fidelity 3D meshes

## Live Demo
[View the Interactive 3D Viewer](https://michaelnguyenz229.github.io/gaussian-splatting-eval/)
*Includes OctoTest, 2019 Prius XLE, and Tesla Optimus captures.*

## Tech Stack
* **Capture:** Luma AI (Neural Radiance Fields / Gaussian Splatting)
* **Rendering:** Three.js / WebGL / lil-gui
* **Format:** GLB (Binary glTF) - Optimized for web performance and simulation compatibility.

##  Scans & Assets Gallery

### Tesla Optimus (Gen 2) Evaluation
This scan focuses on capturing a complex humanoid form. The process involved defining a precise 3D bounding box to isolate the agent from the environment.

**Pre-Scan Bounding Process:**
| Left View | Right View |
| :---: | :---: |
| ![Pre-Scan Left](images/Pre-Scan-Left.jpg) | ![Pre-Scan Right](images/Pre-Scan-Right.jpg) |
| *Defining the left center point.* | *Defining the 180° right boundary.* |

---

### Asset Library
| Capture Name |
| :--- |
| **Tesla Optimus** |
| **2019 Prius XLE** |
| **OctoTest** |
