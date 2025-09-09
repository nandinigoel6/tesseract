# tesseract
Resistant Modelling Intelligence Layer for Rhino/Grasshopper

## Overview
Tesseract is a lightweight Rhino/Grasshopper plugin that:
- Listens to modelling events (add, move, scale).
- Samples changed geometry into a target skeleton.
- Evaluates reuse %, CO2e proxy, decay exposure.
- Suggests candidate parts/joints from an inventory.
- Displays a live HUD overlay + companion Eto panel.

## Roadmap (Fall 2025 Semester)
- [x] Week 2: Repo scaffold + proposal
- [ ] Week 3: Event hooks (add/move/scale)
- [ ] Week 4: Inventory ingest
- [ ] Week 6: HUD overlay scaffold
- [ ] Week 9: First demo
- [ ] Week 13: Final presentation + dashboard

## Getting Started
- Rhino 8 (MIT license)
- Grasshopper
- ghPython
- RhinoCommon SDK
- Karamba3D

Clone this repo and run 'tests/hello_world.py' to see event logging in action.
