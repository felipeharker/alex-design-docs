# Alex Design Docs

Alex Design Docs serves as the home and primary location for documents related to standards created and distributed by Alexandria. This repository contains standardized model files, configuration settings, and templates for designing and visualizing in Rhino 8 and Grasshopper.

## Contents

### `working-template_v1.2.1.3dm`
This document contains the accepted practices for digital drafting and modeling in Rhinoceros 8.

**Features:**
* **Standardized Organization:** Includes predefined layers and sublayers, saved views, and standardized naming conventions and labels.
* **Pre-made Assets:** Contains materials, lights, and pre-made text formatting/styles for callouts and dimensioning.
* **Living Examples:** The model file provides living examples of how to draft (2D), annotate, dimension, and organize 2-dimensional drawings. It also features multiple examples of 3D modeled signage located at saved positions for rendering and visualizing.

This document serves as the functional hub for all design practice standards and works in conjunction with:
* **Render Settings:** Acts as a master document for designing and visualizing with V-Ray.
* **Grasshopper Template:** Works alongside `working-template_v1.2.1.gh` for paired definitions.

### `working-template_v1.2.1.gh`
This document serves as a baseline standard for Grasshopper definition files. Grasshopper is the native parametric/computational design plugin for Rhino.

**Standards Included:**
* Grouping, color coding, and labeling conventions.
* Best practices for data types and data tree workflows.
* User input standards (for numbers, data trees, geometries, etc.).

*(Note: This standard is currently under development with the goal of being as comprehensive as its Rhino counterpart.)*

### `configs/render-settings`
This sub-directory contains the default day and night render settings files (V-Ray object filetype). This allows users to easily swap render settings within V-Ray inside the same Rhino model file to create renders representing different times of day.

### `resource-lib_v1.0.0.3dm`
A living graphic resource and reference library (currently in early development).

---
*These documents aim to follow Agile Documentation Practices—keeping documentation simple, effective, and closely aligned with the working files.*