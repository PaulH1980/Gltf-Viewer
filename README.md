# Gltf-Viewer

ImGui-based glTF viewer / editor built on **SDL** and **legacy OpenGL**.

> This project originally started as a PBRT-v3 rendering experiment, but evolved into a light glTF viewer/editor powered by SDL, ImGui, and OpenGL.
> The focus is fast iteration, simplicity, and debuggability.

---

## Preview

<p align="center">
  <img src="media/helmet.jpg" alt="Helmet screenshot" width="1280">
</p>

<p align="center">
  <img src="media/metal_balls.jpg" alt="Metal balls screenshot" width="1280">
</p>

<p align="center">
  <img src="media/sponza.jpg" alt="Sponza screenshot" width="1280">
</p>

> Images are stored full-resolution via Git LFS and displayed scaled-down for readability.

---

## Features (WIP)

- Load **glTF 2.0** files (`.gltf` / `.glb`)
- ImGui UI for:
  - Scene hierarchy exploration
  - Node / mesh inspection
  - Render options and debug modes
  - Camera controls
- SDL for windowing and input
- Legacy OpenGL backend for simple prototyping
- Fully self-contained Visual Studio 2022 solution (`Enigma.sln`)
- No external dependency managers required

---

## Project Layout

