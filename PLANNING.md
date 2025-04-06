# REDACTARIO - Planning Document

## Overview
**Redactario** is a 32-bit style JRPG that follows a hip hop DJ hero on a quest through a sprawling NYC-style metropolis. The protagonist hunts for vinyl records, pizza, chicks, and herbal delights while evading obstacles like the NYPD, skateboard punks, and dope dealers (with the latter featuring as memorable boss battles).

## High-Level Vision
- **Theme & Setting:**  
  A unique blend of hip hop culture and classic JRPG storytelling set against the backdrop of urban New York City. Locations include bustling streets, parks, record stores, bodegas, and a central apartment homebase.
- **Gameplay:**  
  Traditional turn-based combat, branching dialogue systems, and world exploration, all wrapped in a visually authentic 32-bit pixel art style.

## Architecture & Technical Overview
- **Game Engine:**  
  [Godot Engine 4.4](https://godotengine.org/)  
  Utilizes Godot’s node-based scene system for modular design and reusable components.
  
- **Core Systems:**
  - **Combat:** Turn-based system with action queuing, stat management, and dynamic damage calculation.
  - **Dialogue:** Branching conversations with interactive dialogue trees.
  - **Exploration:** World maps built with TileMap nodes for smooth navigation and interaction zones.
  
- **Programming Language:**  
  [GDScript](https://docs.godotengine.org/en/stable/getting_started/scripting/gdscript/index.html) — Python-like syntax optimized for Godot.

## Tech Stack & Tools
- **Game Development:**  
  - **Engine:** Godot 4.4  
  - **Scripting:** GDScript  
  - **Pixel Art:** TinyPixelArt (integrated workflow with Godot)
  - **Animation:** Godot’s Animation Editor for sprite sheet-based animations.
  
- **Version Control:**  
  Git (with GitHub/GitLab) and Git LFS for handling large assets.

## Constraints & Considerations
- **Visual Style:**  
  Maintain an authentic 32-bit JRPG aesthetic.
- **Resource Management:**  
  Ensure efficient use of system resources given the pixel art assets and complex node interactions.
- **Deployment:**  
  Cross-platform support (desktop, mobile, web) with minimal configuration changes.

## AI Prompt Reference
At the beginning of any new conversation, please reference this file:
> “Use the structure and decisions outlined in PLANNING.md.”

---

*End of PLANNING.md*
