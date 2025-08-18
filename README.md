# IntuiCAM

[![Build Status](https://img.shields.io/github/actions/workflow/status/your-org/IntuiCAM/ci.yml?branch=main)](https://github.com/your-org/IntuiCAM/actions)  
[![License: MIT](https://img.shields.io/badge/License-MIT-blue)](LICENSE)

**IntuiCAM** is an open-source CAM project in **active development**. The goal is to deliver an intuitive, cross-platform solution for CNC turning. A modular **C++ core library** drives the toolpath algorithms while a Qt-based GUI guides you from STEP import to G-code export. Python bindings allow integration and automation.
> **Project Status:** Pre-release / development in progress. Expect missing features and rapid changes.


![image](https://github.com/user-attachments/assets/34024db4-e501-45cc-af62-eb78560b7549)

---
## Project Goals
- Provide a modern, free CAM solution focused on CNC turning
- Offer an intuitive workflow from CAD import to optimized G-code
- Remain extensible via plugins and Python scripting
- Explore future automation with AI-assisted features
- Build toolpath simulation with tool and machine agnostic collision detection
- Develop high performance tool agnostic C++ toolpath generation core
  

## Key Features

- **Modular C++ Core**
  Development of a high-performance library implementing lathe toolpath algorithms.
- **Python Bindings**
  Access core CAM functionality from Python for scripting or integration in other tools (pybind11).
- **Cross-Platform GUI (Qt)**
  Qt will allow desktop interface for Windows, macOS and Linux that guides you from model import to G-code output.
- **STEP Import & B-Rep Accuracy**
  Uses OpenCASCADE to load precise CAD geometry to preserve precision.
- **G-Code Generation & Post-Processing**
  Generating ISO-compliant programs with a flexible post-processing layer for custom machine dialects.
- **Extensible & Plugin-Friendly**
  Clean separation of core and GUI allows new operations or backends to be added with minimal changes.
---

### Current Status

✅ **Responsive GUI** - Embedded OpenGL 3D Viewer in dynamic Qt6 GUI  
✅ **Tool Mangagment** - Tool management dialog window to add and edit turning tools and their geometry
✅ **Material Mangagment** - Material management dialog window to add and edit turning materials and their properties
✅ **Automatic Workpiece Alignment** - Uploading a workpiece automatically alignes it to the chuck.
✅ **Automatic Raw Material Calculation** - Raw material automatically gets generated and displayed based on part geometry and user parameters.
✅ **Lathe/3D Viewing Mode** - Lathe mode locks the viewer to the xz plane.   

### Long Term Goals

- Automate as many CAM-steps as possible (Like 3D-Printing slicers)
- Add functionality streamlining CAM for CNC-mills
- Integrate milling and turning operations to allow for mill-turning 
- Add Cloud connectivity features to easily upload g-code to machine
