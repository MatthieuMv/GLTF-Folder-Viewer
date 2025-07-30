# GLB/GLTF Folder Viewer

A lightweight, mobile-friendly web app that lets you browse and preview 3D models in `.glb` and `.gltf` formats directly from your device:

* **Folder Picker**: Select an entire directory of assets with a single file input.
* **Responsive Thumbnails**: Automatically-generated, inlined WebGL snapshots displayed in a fluid CSS grid.
* **Interactive Modal**: Click a thumbnail to open a Three.js–powered 3D viewer with OrbitControls for rotating, zooming, and panning.
* **ES Module–Based**: Modern importmap setup for Three.js v150+, GLTFLoader, and OrbitControls—no deprecated globals or build steps.
* **File:// Compatible**: Inlines external buffers and textures as Data URIs so it runs seamlessly over `file://` or any static server.

Perfect for quickly inspecting and sharing collections of GLB/GLTF assets without any server-side dependencies.

This project is made by AI.
