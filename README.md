<div align="center">
  <img width="680" alt="DRH - Dual Units banner" src="docs/media/Logo.png" />
</div>

<br>

<div align="center">

# DRH - Dual Units

### Support · Documentation · Feedback · Available on BlendKit

Dual-unit transform values and scene measurement tools.

![Status](https://img.shields.io/badge/status-Released-22C55E?style=for-the-badge)
![Version](https://img.shields.io/badge/version-1.1.0-00B7FF?style=for-the-badge)
![Blender](https://img.shields.io/badge/blender-4.2%2B-0B1F4D?style=for-the-badge)
![Platforms](https://img.shields.io/badge/platforms-Windows%20%7C%20macOS%20%7C%20Linux-EAF2FF?style=for-the-badge&labelColor=0B1F4D&color=EAF2FF)

<br>

DRH Blender Tools: support, documentation, and release information.

[![DRH Add-ons Hub](https://img.shields.io/badge/DRH%20Add--ons%20Hub-Visit%20Hub-1E5BFF?style=for-the-badge&labelColor=0B1F4D)](https://github.com/pacosalasv/DRH_Addons_Hub)
[![Available on BlendKit](https://img.shields.io/badge/BlendKit-FREE%20Download-0B1F4D?style=for-the-badge)](https://www.blendkit.com/asset-gallery-detail/6fdca217-16ce-4771-bd1f-3aba38f48858/)

</div>

---

<div align="center">

DRH - Dual Units helps Blender users review Location, Rotation, Scale, and Dimensions with active scene units and alternate units visible side by side.

This repository is the central public hub for support, documentation, issue tracking, compatibility feedback, and release feedback for DRH - Dual Units.

</div>

---

## Overview

DRH - Dual Units is a Blender workflow utility designed to make unit review, alternate measurement display, and transform checking faster inside the 3D View N Panel.

It is intended for modelers, makers, 3D printing users, product visualization artists, architecture-adjacent users, asset creators, technical artists, and Blender users who need to move between real-world unit systems or verify object dimensions during production.

Instead of repeatedly changing scene unit settings manually or relying on mental conversions, DRH - Dual Units provides a familiar transform-style panel where scene units and alternate units can be reviewed side by side.

---

## Media preview

### Screenshots

<div align="center">

| Transform Panel Alternate Units | Object Labels and Placement |
|---|---|
| <img height="420" alt="Transform Panel with Alternate Units" src="docs/media/ScreenShot_01.png" /> | <img height="420" alt="Object Labels and Placement" src="docs/media/ScreenShot_02.png" /> |

</div>

<details>
  <summary><strong>More Screenshots...</strong></summary>

<div align="center">

| Units and Panel Settings |
|---|
| <img height="420" alt="Units and Panel Settings" src="docs/media/ScreenShot_03.png" /> |

</div>

</details>

---

## What DRH - Dual Units does

DRH - Dual Units adds a dedicated Blender sidebar workflow for scene units, alternate unit display, transform review, and object display labeling.

It is designed to emulate Blender’s familiar Transform panel while adding the dual-unit visibility Blender does not provide by default.

Use it to:

| Details |
|---|
| View scene units and alternate units side by side |
| Review Location, Rotation, Scale, and Dimensions without manual conversion |
| Switch between practical scene unit presets |
| Show alternate dimensions, location, and rotation values |
| Format alternate values with precision, brackets, and split-unit display |
| Swap scene and alternate unit workflows when supported |
| Lock and edit transform values from a familiar transform-style interface |
| Show or hide rotation mode and scale controls in the panel |
| Apply object display settings to selected objects |
| Display object names outside object bounds with configurable anchor, position, size, color, and offset |
| Reset scene and add-on settings to defaults |
| Keep measurement and viewport review tools available from the 3D View UI |

---

## Capabilities

| Details |
|---|
| Familiar transform-style N Panel layout |
| Scene unit and alternate unit values shown side by side |
| Location, Rotation, Scale, and Dimensions review without manual conversion |
| Scene unit presets for metric, imperial, product, architecture, site, carpentry, and 3D printing workflows |
| Alternate length units for meters, centimeters, millimeters, kilometers, inches, feet, yards, and miles |
| Alternate rotation-unit support |
| Precision controls from 0 to 6 decimal places |
| Optional split-unit formatting for supported alternate unit families |
| Bracket style options for alternate values |
| Transform lock and edit workflow |
| Object display tools for selected objects |
| External object-name overlay controls |
| Name anchor, placement, size, color, and offset settings |
| Apply-to-selected workflow for object display settings |
| Settings popup and reset-to-defaults workflow |
| Scene and object property registration for persistent settings |
| Local Blender add-on workflow with no external service requirement |

---

<details>
  <summary>Feature reference</summary>

## Feature reference

### Unit switching and presets
| Details |
|---|
| Scene unit preset workflow |
| Alternate unit workflow |
| Preset: Custom |
| Preset: General Metric |
| Preset: Product Metric |
| Preset: Arch Imperial |
| Preset: Site Imperial |
| Preset: Architecture mm |
| Preset: Carpentry |
| Preset: 3D Printing |
| Swap Scene / Alternate Units operator |
| Reset all defaults operator |

### Supported alternate length units
| Details |
|---|
| Meters |
| Centimeters |
| Millimeters |
| Kilometers |
| Inches |
| Feet |
| Yards |
| Miles |

### Preset behavior
| Details |
|---|
| General Metric: metric meters, degrees, alternate inches |
| Product Metric: metric millimeters, degrees, alternate inches |
| Architecture mm: metric millimeters, degrees, alternate inches |
| 3D Printing: metric millimeters, degrees, alternate inches |
| Arch Imperial: imperial inches, degrees, alternate millimeters |
| Site Imperial: imperial feet, degrees, alternate meters |
| Carpentry: imperial inches with separate units enabled, alternate millimeters |

### Measurement display
| Details |
|---|
| Show alternate dimensions |
| Show alternate location values |
| Show alternate rotation values |
| Show rotation mode controls |
| Show scale controls |
| Alternate precision controls |
| Alternate split-unit display |
| Bracket style options |
| Alternate rotation-unit selection |

### Transform workflow
| Details |
|---|
| Familiar transform-style panel layout |
| Location review |
| Rotation review |
| Scale review |
| Dimensions review |
| Lock and edit transform values |
| Converted alternate values beside original transform values |
| Faster scale checking across metric and imperial workflows |

### Object display tools
| Details |
|---|
| Active object display-type controls |
| Apply selected object display settings |
| Show object name outside object bounds |
| Name anchor controls |
| Name placement controls |
| Name size controls |
| Name color controls |
| Name offset controls |
| Viewport overlay redraw/update handling |

### Batch and UI workflow
| Details |
|---|
| Apply selected display and label settings to selected objects |
| Settings popup |
| Reset all defaults |
| Main transform panel |
| Properties subpanel |
| Scene-level settings stored on the scene |
| Object-level label settings stored on each object |
| Local viewport draw handler for custom object-name overlays |

</details>

---

## Intended users

DRH - Dual Units is designed for:

| Details |
|---|
| Blender modelers |
| 3D printing users |
| Makers |
| Product visualization artists |
| Asset creators |
| Technical artists |
| Architecture-adjacent Blender users |
| Users working with real-world scale |
| Users working between metric and imperial references |
| Users who need fast unit switching |
| Users who want clearer measurement, labeling, and scale-review workflows |
| Users preparing models for clients, collaborators, manufacturing references, or technical asset review |

---

## Status

| Item | Details |
|---|---|
| Status | 🟢 Released |
| Current version | 1.1.0 |
| Minimum Blender version | 4.2.0 |
| Blender location | N Panel > DRH - Dual Units |
| Platforms | Windows, macOS, Linux |
| Release type | Free public release |
| Official distribution | BlendKit only |
| Free download on BlendKit | [DRH - Dual Units & Measurements](https://www.blendkit.com/asset-gallery-detail/6fdca217-16ce-4771-bd1f-3aba38f48858/) |
| Support repository | [DRH - Dual Units Support](https://github.com/pacosalasv/DRH_Dual_Units-Support) |

DRH - Dual Units is free for everyone. Official releases and installable packages are distributed exclusively through BlendKit. This GitHub repository is the public support and documentation hub; it does not host official release packages. Use it for compatibility feedback, bug reports, documentation, and workflow suggestions across supported Blender versions.

---

## Technical notes

This add-on is source based, with:

- No obfuscation
- No binary-only content
- No external services
- No account requirements

Local system access may be used only for normal Blender workflows such as saving files, loading assets, exporting data, or using project resources when applicable.

The add-on is intended to work locally inside Blender.

---

## Availability

DRH - Dual Units is free for everyone.

Official download and release distribution:

- [BlendKit - Free Download](https://www.blendkit.com/asset-gallery-detail/6fdca217-16ce-4771-bd1f-3aba38f48858/)

Official installable releases are distributed exclusively through BlendKit. This GitHub repository is intentionally kept as a support, documentation, feedback, and issue-tracking hub rather than a release-download mirror.

This GitHub repository remains the central public location for:

| Details |
|---|
| Support |
| Documentation |
| Issue tracking |
| Compatibility reports |
| Public feedback |
| Release notes |

---

## Documentation

- [User Manual](docs/manual/user-manual.pdf)
- [Changelog](CHANGELOG.md)

---


## Support

Use [GitHub Discussions](https://github.com/pacosalasv/DRH_Dual_Units-Support/discussions) for setup questions, workflow guidance, and general feedback. Use [GitHub Issues](https://github.com/pacosalasv/DRH_Dual_Units-Support/issues/new/choose) for reproducible bugs, regressions, compatibility problems, and focused feature requests.

Do not post credentials, payment information, license keys, confidential production files, private client material, or sensitive local paths.

Detailed guidance is available in [SUPPORT.md](SUPPORT.md).

## Support DRH development

Development support is optional. Contributions through [Ko-fi](https://ko-fi.com/pacosalasv) help cover maintenance, Blender compatibility work, documentation, and testing.

## License

This repository is distributed under GPL-3.0-or-later.

---

<div align="center">
