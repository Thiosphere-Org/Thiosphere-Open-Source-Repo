# Thiosphere - Modular Open Source Shelters

[![CERN Open Hardware License v2](https://img.shields.io/badge/License-CERN%20OHL%20v2%20Strongly%20Reciprocal-blue.svg)](LICENSE.md)
[![Open Source Hardware](https://img.shields.io/badge/Open%20Source-Hardware-green.svg)](https://www.oshwa.org/)
[![Documentation](https://img.shields.io/badge/Documentation-Complete-brightgreen.svg)](docs/)

[🇺🇸 English](README.md) | [🇩🇪 Deutsch](README.de.md) | [🇪🇸 Español](README.es.md) | [🇫🇷 Français](README.fr.md) | [🇸🇪 Svenska](README.sv.md) | [🇫🇮 Suomi](README.fi.md)

---

# Modular Open Source Shelters

We have formatted our world for cars, yet have little else to make use of all that space we have given over to these machines. A Thiosphere™ is created to fill that void with a purpose and beauty that defines its bold and efficient design. It is Open Source Hardware that anyone can build and modify to their own needs.

## Introduction

One thiosphere is made from the fewest number of parts possible, yet resulting in a strong, light and roomy, modular shelter that only takes up 1/2 of a parking spot. It is flat packable and can be assembled with common tools. It is modular so you can create an endless number of structures, from a simple shelter to a complex office. It is both functional and beautiful, and designed to be a second place for life to flourish - whatever, and wherever those requirements are.

![Thiosphere Basics](_media/football.png)
![Thiosphere Basics](_media/basics.png)
![Thiosphere Flattened View](_media/flatten.png)

### Open Source Hardware License

Understanding Our Open Hardware License
The CERN Open Hardware License (Version 2 - Strongly Reciprocal) ensures that:

- All designs and modifications must be shared openly
- Commercial use is permitted with proper attribution
- Modified versions must be shared under the same license
- Original creators must be credited
- Documentation must be provided for all changes

![Thiosphere Scale](_media/module.png)
![Thiosphere Scale](_media/scale.png)

## The Advantages

- **Built Strong**: Spherical geometry = maximum strength, minimum material
- **Stays Cool**: Natural convection keeps the environment stable inside
- **Fits Right In**: Designed for existing parking spaces - no modifications needed
- **Easy to Build**: Simple geometry means you can make it locally with basic tools

## What's a Thios?

> The number two in Greek is written as "δύο" and pronounced with a soft "th" sound (thío), rather than the hard "d" one might expect. This "thio" prefix perfectly describes the dual-sphere design of the Thiosphere™, a second place for life.

## Quick Start

### 📋 Prerequisites

- Basic woodworking skills
- Access to standard tools (see Construction Guide)
- Understanding of the CERN Open Hardware License

### 🛠️ Getting Started

1. **Review Documentation**: Start with the [Design Document](thiosphere-design-document.md)
2. **Check Materials**: Review the [Bill of Materials](Bill_of_Materials_v.0.1.csv)
3. **Understand License**: Read the [CERN Open Hardware License](LICENSE.md)
4. **Start Building**: Follow the Construction Guide below

## Construction Guide

> **Where these numbers come from.** Every figure below is measured from the final Onshape
> model *Thiosphere for prints* at `#maxWidth` = 93.700 in (verified 2026-09-12). Where the older
> [Design Document](thiosphere-design-document.md) or
> [Bill of Materials v0.1](Bill_of_Materials_v.0.1.csv) disagree, this guide is correct.

### At a Glance

| | |
|---|---|
| Outer diameter | **93.700 in** (7 ft 9.7 in) |
| Edge length, outer shell | **18.906 in** |
| Edge length, inner shell | **16.701 in** |
| Wall thickness | **5.0 in** — ¼ skin + 1½ rail + 1½ cleat + 1½ rail + ¼ skin |
| Clear height above the finished floor, at the ridge | **79.829 in** |
| Floor deck | 12-sided, 88.543 × 91.773 in |
| Modules | **23** |

The shape is a truncated icosahedron (32 faces: 20 hexagons, 12 pentagons). It rests on an
edge, not a face.

### The 23 Modules

Only the 22 faces at or above the lower hexagon ring are panels. The 10 faces below are not
built: types B, C and E extend downward to the deck and take their place.

| Type | Module | Count | How it is made |
|---|---|---:|---|
| A | Plain hexagon | 8 | Regular hexagon |
| B | Door | 4 | Hexagon, two vertical sides extended to the deck |
| C | Side wall | 2 | Hexagon, two slanted sides extended to the deck |
| D | Plain pentagon | 4 | Regular pentagon |
| E | Corner kite | 4 | Pentagon, two sides extended until they meet |
| FL | Floor deck | 1 | 12-sided, two sheets of ¾ in plywood |
| | **Total** | **23** | |

### What You'll Need

**Materials:**
- **36** × 2×4 studs, 96 in long — each one is ripped down the centre (includes 8.5% for kerf and end-drop)
- **16** × 4×8 sheets of ¼ in plywood — outer and inner skins, with 35% for nesting
- **2** × 4×8 sheets of ¾ in plywood — floor deck
- Screws, bolts, and casters, a trailer or a levelling plinth — quantities are being re-derived for the current model and are not listed until they are verified

**Tools:**
- Table saw with a tilting blade (the bevel is cut during the rip)
- Compound miter saw
- Drill/driver
- Measuring tape and pencil
- Safety gear (glasses, hearing protection)

### Step-by-Step Build

#### 1. Sort Your Stock, Then Rip

**There are two bevels, not one.**

| Rail sits between | Bevel |
|---|---:|
| Hexagon ↔ hexagon | **20.905°** |
| Hexagon ↔ pentagon | **18.689°** |

- Every 2×4 is ripped down the centre with the blade tilted to the bevel. One pass makes the bevel and two rails.
- With a ⅛ in kerf, each half is 1.6875 in wide.
- The bevel is set at the rip, and you cannot re-rip a half. **Decide which bevel each stud's rails need before you rip it.**
- A hexagon module needs **both** bevels: its edges alternate between hexagon and pentagon neighbours. A pentagon module uses 18.689° on all five edges.

> ⚠️ **Do not use one averaged bevel of about 19.8°.** It opens a gap of about 5⁄64 in at
> every joint, and the gaps add up at every corner where three rails meet.

#### 2. Cut Rails to Length

**Miters:** 30° at hexagon corners, 36° at pentagon corners, 36° at the kite point.

**Lengths** (long point to long point):

| Rail | Outer shell | Inner shell |
|---|---:|---:|
| Plain edges — types A and D, and the edges of B, C and E that are not extended | 18.906 in | 16.701 in |
| B · door, vertical side | 49.497 in | 49.056 in |
| B · door, deck sill | 32.747 in | 31.218 in |
| C · side wall, slanted side | 49.497 in | 49.497 in |
| C · side wall, deck sill | 68.403 in | 67.521 in |
| E · corner kite, extended side | 49.497 in | 43.724 in |

**Do not make the inner shell by scaling the outer shell.** The extended sides end on the
deck, and the deck does not move, so they shrink less than the plain edges or not at all.
That is why the inner shell has six rail lengths and the outer shell has four.

**Total rail stock:** outer shell 112 rails (240.3 ft), inner shell 112 rails (218.3 ft),
cleats 224 pieces (63.2 ft) — **521.8 linear ft**.

**Batch your cuts by bevel across all modules**, not module by module.

#### 3. Build the Module Frames

1. Build each module frame flat
2. Join the rails at the miters and check each angle
3. Use GRK screws to secure joints
4. Join the outer and inner rails with the cleat layer. This sets the 5.0 in wall
5. Dry-fit neighbouring modules before you fix them

#### 4. Assemble on the Deck

1. Build the floor deck first. It is the plane where every extended side ends
2. Stand the lower modules (B, C, E) on the deck, then work upward
3. Use temporary supports to hold modules in place
4. Work in sections to keep it solid

**Corner ports:** at each of the four inner corners there is a triangular gap at floor level,
4.671 in tall × 3.394 in wide. It is a utility port into the wall cavity (it takes 3 in duct
or a bundled service drop). Close it with a removable cover. Do not fill it.

#### 5. Add the Panels

**Outer skin — laps shed water:**
- The panel whose centre is higher laps over the lower one. **Install from the bottom up.**
- Each lap is 1.5 in, the same as the rail thickness, so it sits fully on the rail of the panel below and you can screw into it.
- **Cut a capillary break on the underside of every lapping edge:** a ⅛ in wide × ⅛ in deep kerf, 0.5 in in from the edge. Without it, water wicks uphill between the sheets, whatever the lap length.
- The eight equatorial faces are vertical. Their vertical seams take a gasket or batten, not a lap.
- The ridge is the one seam with no uphill side. Seal it with a gasket.

**Inner skin:**
- Cut to fit the inner frame

**Install:**
1. Sand edges smooth
2. Apply silicone caulk to frame edges
3. Press panels into place and secure them with screws around the perimeter
4. Wipe off excess caulk

#### 6. Weatherproof It

**Seal all joints:**
- Apply silicone caulk to all exterior joints
- Pay special attention to panel edges
- Let it cure for 24 hours

**Apply finish:**
- Paint or seal all wood surfaces
- Use exterior-grade paint for outside use
- Apply multiple coats for durability

### Pro Tips

- **Batch by bevel**: sort stock and group cuts by bevel, never by module
- **Take your time**: Precision in cutting angles is key
- **Test fit**: Dry assemble sections before final assembly
- **Use jigs**: Create simple jigs to hold pieces at correct angles
- **Work in pairs**: Some assembly steps are easier with help
- **Check measurements**: Verify each piece before cutting

### Resources

- [Compound Miter Saw Calculator](https://jansson.us/jcompound.html) - Essential for calculating precise angles
- [GRK FIN/Trim™ Screws](https://grkfasteners.ca/product/fin-trim-finishing-trim-head-screw/) - Recommended for clean finish
- [McMaster-Carr Hardware](https://www.mcmaster.com/90273A572/) - For additional fasteners and hardware

### Quick Reference

| | Value |
|---|---:|
| Outer diameter | 93.700 in |
| Edge length, outer / inner | 18.906 / 16.701 in |
| Bevel, hexagon ↔ hexagon | 20.905° |
| Bevel, hexagon ↔ pentagon | 18.689° |
| Miter, hexagon / pentagon / kite point | 30° / 36° / 36° |
| Ripped half width (⅛ in kerf) | 1.6875 in |
| Wall thickness | 5.0 in |
| Modules | 23 |
| 96 in 2×4 studs | 36 |
| 4×8 sheets, ¼ in / ¾ in | 16 / 2 |

## 📁 Project Structure

```
Thiosphere-Open-Source-Repo/
├── README.md                    # This file (English)
├── README.de.md                 # German documentation
├── README.es.md                 # Spanish documentation
├── README.fr.md                 # French documentation
├── README.sv.md                 # Swedish documentation
├── README.fi.md                 # Finnish documentation
├── LICENSE.md                   # CERN Open Hardware License v2
├── thiosphere-design-document.md # Complete design documentation
├── Bill_of_Materials_v.0.1.csv  # Materials list
├── src/                         # Source files
│   ├── thiosphere_0.01.step     # CAD model (STEP format)
│   └── thiosphere-fine.stl      # 3D model (STL format)
├── _media/                      # Images and media
└── docs/                        # Additional documentation
```

## 🤝 Contributing

We welcome contributions to the Thiosphere project! Please read our contributing guidelines:

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/amazing-feature`)
3. **Commit your changes** (`git commit -m 'Add some amazing feature'`)
4. **Push to the branch** (`git push origin feature/amazing-feature`)
5. **Open a Pull Request**

### Contribution Guidelines

- Follow the CERN Open Hardware License v2 requirements
- Document all modifications thoroughly
- Include updated Bill of Materials if changes affect materials
- Test your modifications before submitting
- Provide clear documentation for any new features

## 📄 License

This project is licensed under the **CERN Open Hardware License Version 2 - Strongly Reciprocal**. See the [LICENSE.md](LICENSE.md) file for details.

## 🔗 Links

- **Website**: [https://thiosphere.org](https://thiosphere.org)
- **Design Document**: [thiosphere-design-document.md](thiosphere-design-document.md)
- **Bill of Materials**: [Bill_of_Materials_v.0.1.csv](Bill_of_Materials_v.0.1.csv)
- **CAD Models**: [src/](src/)

## 🙏 Acknowledgments

- CERN for the Open Hardware License
- The open source hardware community
- All contributors and builders who have helped develop the Thiosphere

---

**Thiospheres - Domus Opus Est** (the work of shelter never ends).

*"We have formatted our world for cars, yet have little else to make use of all that space we have given over to these machines."*

---

*This project is created and sponsored by [thios.co](https://thios.co)*
