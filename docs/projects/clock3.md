---
title: Clock 3
summary: An enclosed, CoreXY 3D printer.
authors: Jon Harper
date: 2022-06-16
---

![Clock 3 Benchy](assets/clock3_benchy.jpg){ data-title="Clock 3 and an ABS Benchy" data-description="A Benchy printed in ABS plastic during Winter, 2021. This milestone demonstrated working kinematics, insulation, and air filtration"}

Clock 3 is a prototype enclosed, CoreXY 3D printer. It is now used to generate new ideas for [The Clockmaker Project](clockmaker.md).

Some work on Clock 3 is still ongoing. The CoreXY system is now modeled after the Mercury One belt path; this enables the use of the [E34M1](e34m1.md) toolhead.

## Goals

Clock 3 achieved several [development goals](https://jon-harper.github.io/clock-3/about/goals/):

- It is easily sourced.
- It is easy to service.
- The design proves the concept is viable.

## Status

Model corruption halted immediate further work, but directly led to the development of [OmniBox][omnibox] and [The Clockmaker Project][clockmaker].

![all printed parts on a table](../img/clock3/all_parts.jpg){ width="640px" data-title="Over 100 Unique Printed Parts" data-description="Nearly all of these parts were designed between September of 2021 and May of 2022" }

## Features

### Project Features

- Over 100 unique printed part designs;
- Integrated HEPA and activated charcoal filtration;
- Python-scripted Bill of Materials generation; and
- Extensive wiring documentation.

### Printer Features

- CoreXY kinematics;
- Large print volume (300mm x 300mm x 350mm);
- Double-paned and air-gapped front window;
- Polyisocyanurate (PIR) foam-insulated panels;
- Top service hatch and floor service hatches; and
- Externally-mounted stepper motors.

### Other Features

- Step-by-step assembly guide;
- Fully documented assembly;
- Daily changelog; and
- git-based Klipper configuration.

## Links

<div markdown class="jh-grid-container jh-grid-2">
<div markdown class="jh-card">
<div markdown class="jh-grid-container jh-link-grid">
[Clock 3 Project Page](https://jon-harper.github.io/clock-3)

[GitHub Repository](https://github.com/jon-harper/clock-3)
</div>
</div>
</div>

Additional tools from this project:

- [:material-git: clock-face](https://github.com/jon-harper/clock-face): a modified Klipper display to show enclosure temperature
- [:material-git: clock3-klipper](https://github.com/jon-harper/clock3-klipper): Klipper configuration delegation via git
- [:material-git: Clock3Scripts](https://github.com/jon-harper/Clock3Scripts): Fusion 360 Python plugin for automatical bill of materials generation

## Gallery

[cards lightbox=true cols=2(docs/assets/clock3_gallery.yml)]

[omnibox]: omnibox.md
[clockmaker]: clockmaker.md