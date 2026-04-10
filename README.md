# Rube Goldberg : Indonesian Café (Unity)

A physics-driven Rube Goldberg Machine built in Unity, using chained interactions to unfold a personal narrative set in an Indonesian café.

## Project Details

| | |
|---|---|
| **Category** | Rube Goldberg Machine, Physics Simulation, 3D Modeling, Lighting & Sound Design, Narrative Experience |
| **Year** | 2025 |
| **Tools** | Unity, Premiere Pro, C# |

## About

This project designs and builds a physics-driven Rube Goldberg Machine in Unity, using chained interactions to unfold a personal narrative. It integrates 3D models, materials, sound, motion, camera framing, and lighting to create a cohesive, story-led experience.

The Indonesian café is built as a tribute to longing for home and to coffee as a shared tradition in Indonesia. Cafés are a growing part of everyday life—across youth culture, working communities, and even street coffee trucks—serving as places where people gather and relationships form. This project becomes a dreamlike "world of wonder," shaped by how I imagine Indonesia in my mind: familiar, vibrant, and warmly communal.

## Build Focus

- Physics-driven chain reactions (cause → effect → narrative progression)
- 3D scene composition (models, props, spatial storytelling)
- Lighting + camera framing to guide attention through each step
- Sound + motion cues to reinforce impact and pacing
- Materials + environmental mood to evoke a nostalgic café atmosphere

The machine is designed as a sequence of interactions that feels playful and intentional, where each trigger carries the viewer forward through the space like a story.

## Demo Video

[Watch the Unity Demo](https://www.youtube.com/watch?v=jb7P1sDZG8U)

## Running the Project

This project is built as a Unity WebGL application. To run it locally:

1. Serve the content using a local web server (WebGL builds cannot be opened directly from filesystem)
2. Open `index.html` through the web server

Example with Python:
```bash
python -m http.server 8000
```

Then visit `http://localhost:8000` in your browser.

## Project Structure

```
indonesianCafe_CoreLab/
├── Build/                    # Unity WebGL build output
├── TemplateData/            # WebGL templates and assets
├── index.html              # WebGL launcher
├── dependencies.txt        # Project dependencies
└── GUID.txt               # Unity project GUID
```