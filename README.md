# CAD Exports

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
![Designed in](https://img.shields.io/badge/designed%20in-Onshape-blue.svg)

STEP and STL exports of every structural component we've designed across our missions. Our live parametric designs live in Onshape, but we export key versions here so anyone — regardless of what CAD software they use — can open, study, and build on our work.

We're a student rocketry association from Anand, Gujarat, building towards 100 km — one mission at a time.

---

## What's in here

```
cad-exports/
├── missions/
│   ├── M001-HomiSII
│   │   ├── nose-cone/
│   │   │   ├── nose-cone-v3.step     # Final version as flown
│   │   │   ├── nose-cone-v3.stl
│   │   │   └── specs.md              # Dimensions, material, manufacturing notes
│   │   ├── body-tube/
│   │   ├── fins/
│   │   ├── ejection-system/
│   │   └── M001-full-assembly.step   # Complete rocket assembly export
│   └── M002/
└── resources/
    └── standard-components/          # Reusable parts that carry across missions
```

---

## File Formats

| Format | Use |
|--------|-----|
| `.step` | Import into any professional CAD tool — Fusion 360, SolidWorks, FreeCAD, etc. |
| `.stl` | 3D printing or mesh viewing |
| `specs.md` | Dimensions, tolerances, material, and manufacturing method — readable without opening any software |

> **Live parametric designs** are in our Onshape workspace. If you want access for editing or to see the full design history, open an issue and we can share a read-only link.

---

## What's in each `specs.md`

Every component folder contains a `specs.md` documenting:

- Final outer dimensions and tolerances
- Material used and why
- Manufacturing method (3D printed / machined / purchased standard)
- Version history and what changed between versions
- Known limitations, or things we'd redesign next mission

If a part looks different from what's in the simulation files, check the mission archive — we document all changes made between design and final build.

---

## Using These Files

**Fusion 360 / SolidWorks / FreeCAD:** Import the `.step` file via File → Import.  
**FreeCAD (free & open source):** Fully supported — `.step` opens natively.  
**3D printing:** Use the `.stl`. Check `specs.md` for recommended wall thickness and infill where noted.  
**Reference only:** `specs.md` gives you all dimensions without needing to open any CAD software.

---

## A Note on Versions

Files are versioned in the filename (e.g. `nose-cone-v3.step`). The highest version number is what flew. Earlier versions are kept in the folder so you can see the design evolution. The commit history tells you what changed and when.

---

## Contributing

If you've manufactured one of our components and found a fit issue, a stress concentration, or a straightforward improvement — we want to know. Open an issue with photos or measurements and we'll consider it for the next mission revision.

[💬 Discussions](../../discussions)

---

## License

This work is licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

You are free to use, adapt, and build upon these designs for any purpose — including commercially — as long as you give appropriate credit to [Association Name]. See the [LICENSE](LICENSE) file for full terms.

---

## About Us

We're a student rocketry association from Anand, Gujarat. This repository is part of our commitment to open-source rocketry education. Everything we learn, we share.

[🔗 All Repos](https://github.com/[org-name]) · [💬 Discussions](../../discussions)
