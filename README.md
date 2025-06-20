# rasterizing-roblox

# Roblox Raster Drawing

**Note:** Roblox does not natively support true image rasterization. However, the introduction of [`EditableImage`](https://create.roblox.com/docs/reference/engine/classes/EditableImage) — has opened possibilities for pixel-based rendering and manipulation within the engine.

##  Project Overview

This is a Photoshop, Procreate style raster based program in Roblox, completely for free, for everyone. This project leverages the [`EditableImage`] using Ethanthegrand's CanvasDraw API to facilitate communication. 

## Key Features

- ✏️ **Custom Brushes**:  Smudge, blend, lighten/darken, glow, and shape brushes
- 🎨 **Advanced Color Manipulation**: True alpha blending, hue preservation, and live color picking across layers
- 🧱 **Layered Canvas System**: Full multi-layer support with (per-layer blending options[WIP])
- 🔄 **Undo/Redo System**: Chunked command history for efficient memory usage
- 🔍 **Zoom & Pan**: Smooth viewport control for high-resolution pixel editing 
- 📐 **Snapping and Stroke Logic**: Pixel-accurate snapping and intelligent stroke management
- 🔒 **Completely Free**: No monetized features — all tools and brushes are fully accessible to the user. 

UI and 2D experiences on Roblox often lag behind engines like Unreal or Unity, due to how Roblox allocates its engine resources. This project serves as a demonstration that expressive 2D drawing tools can exist on Roblox without sacrificing performance or artistic flexibility.
