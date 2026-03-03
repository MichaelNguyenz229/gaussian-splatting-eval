# Gaussian Splat Evaluation & Simulation Environment

An exploration into capturing real-world environments via **Gaussian Splatting** and converting them into high-fidelity 3D meshes for use in robotics simulation pipelines.

##  Live Demo
[View the Interactive 3D Environment](https://michaelnguyenz229.github.io/gaussian-splatting-eval/)

## Tech Stack
* **Capture:** Luma AI (Neural Radiance Fields / Gaussian Splatting)
* **Rendering:** Three.js / WebGL
* **Format:** GLB (Binary glTF) - Optimized for web performance and simulation compatibility.



## Scans & Assets Gallery
*A collection of real-world captures processed for simulation.*

| Capture Name | Preview | Description |
| :--- | :--- | :--- |
| **OctoTest** | ![OctoTest Preview](gifs/octotest.gif) | Initial test scan to evaluate texture baking and mesh density. |
| **Future Scan 02** | ![Coming Soon](https://via.placeholder.com/150) | In-progress capture focusing on complex geometry. |

## Roadmap
- [x] Custom Three.js web renderer deployment.
- [ ] **Library Expansion:** Scan and process a diverse set of real-world objects to build a robust training environment.
- [ ] **Physics Integration:** Exporting meshes to Isaac Sim/MuJoCo to generate URDF/XML files for robotic interaction.