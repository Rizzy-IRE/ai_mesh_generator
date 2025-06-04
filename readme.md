# AI Mesh Generator 🧠➜🧱

Generate clean, printable 3D models from 2D concept art using TripoSR and Blender.  
This project is designed for NVIDIA AI Workbench.

## 🧪 Workflow
1. Drop 2D image into `data/inputs/`
2. Run notebook to generate mesh via TripoSR
3. Preview & convert to STL for 3D printing

## 📦 Requirements
- RTX-class GPU
- NVIDIA AI Workbench (pulls `nvcr.io` containers)
- Blender (for cleanup, optional)

## 📁 Folder Layout
- `notebooks/`: AI scripts
- `data/`: input/output images & meshes
- `models/`: model checkpoints
