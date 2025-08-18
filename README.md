# IntuiCAM

IntuiCAM is an open-source computer-aided manufacturing system focused on CNC turning. It combines a high-performance C++ core library with a Qt-based desktop interface and Python bindings for automation.

![image](https://github.com/user-attachments/assets/34024db4-e501-45cc-af62-eb78560b7549)

## Features

### Implemented
- **Qt6 interface with OpenCASCADE 3D viewer** supporting both free 3D navigation and a lathe XZ mode for turning operations.
- **Tool management dialog** to create, edit and persist turning tools and assemblies.
- **Material management** with presets and editable physical and machining properties.
- **Automatic workpiece alignment** that orients the imported model to the chuck centerline and initializes the work coordinate system.
- **Automatic raw material sizing** that generates a cylindrical blank based on detected part dimensions.
- **G-code generation library** producing program headers, tool changes and movement commands.
- **Python bindings** exposing geometry, toolpath, post-processing and simulation APIs for scripting or integration.

### In Progress
- STEP file import and precise B-Rep geometry (current loader uses a simple placeholder implementation).
- Toolpath simulation and collision detection.
- Expanded toolpath operations and automated toolpath pipeline.
- Additional platform integration, milling support and cloud connectivity features.

## Project Status

Pre-release / development in progress. Expect rapid changes and incomplete features.

