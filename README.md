# Anatomy Layer Stacker – Blender Add-on

Anatomy Layer Stacker is a Blender add-on for stacking 3D anatomical models based on numeric layer order. It arranges models along the Z-axis with adjustable spacing, enabling clear visualization of sequential dissections. Ideal for photogrammetry, education, and surgical simulation.

## Description

Anatomy Layer Stacker is an open-source Blender add-on developed to streamline the spatial organization and visualization of serial anatomical datasets derived from photogrammetry, 3D scanning, or segmentation workflows. It automates the arrangement of multiple 3D mesh models—each representing a successive anatomical layer—by identifying numerically named mesh objects (e.g., "1", "2", "3") and stacking them vertically with consistent, user-defined spacing.

Designed for medical educators, anatomists, and surgical researchers, the add-on enables clear, layered visualization of complex anatomical structures, supporting both educational and virtual reality applications.

## Features

- Automatic stacking of 3D layers based on numeric naming  
- Adjustable Z-axis spacing via a simple UI slider  
- Sidebar panel with visibility toggles for each layer  
- Works natively within Blender (2.80+)  
- Fully offline, no external dependencies  

## Installation

1. Download `anatomy_layer_stacker.py`
2. Open Blender → `Edit > Preferences > Add-ons > Install...`
3. Select the `.py` file and enable the add-on
4. In the 3D Viewport, press `N` to open the sidebar
5. Go to the `Layer Visibility` tab and use the interface to stack and toggle layers

## License

This project is licensed under the GNU General Public License v3.0.  
See the `LICENSE` file for full terms. You may use, modify, and redistribute this software under the conditions of the GPL.

## Contact

Developed by the [3D Atlas of Neurological Surgery](https://3datlasofneurologicalsurgery.org)  
Contact: 3datlas@pm.me
