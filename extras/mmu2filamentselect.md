---
layout: plugin

id: mmu2filamentselect
title: OctoPrint-Mmu2filamentselect
description: Select filament when printing with Prusa MMU2 in single mode.
author: Florian Schütte
license: AGPLv3

date: 2019-10-04

homepage: https://github.com/derPicknicker1/OctoPrint-Mmu2filamentselect
source: https://github.com/derPicknicker1/OctoPrint-Mmu2filamentselect
archive: https://github.com/derPicknicker1/OctoPrint-Mmu2filamentselect/archive/master.zip

follow_dependency_links: false

tags:
- prusa
- mmu2
- gcode
- prusa mmu2
- filament
- notification

screenshots:
- url: /assets/img/mmu2filamentselect/dialog.png
  alt: Picture of the filament selection dialog.
  caption: Dialog which is shown when filament has to be selected.
- url: url of another screenshot, /assets/img/...
  alt: /assets/img/mmu2filamentselect/settings2.png
  caption: The dialog timeout can be set by the user


featuredimage: /assets/img/mmu2filamentselect/octoprusa.png

---

This plugin shows a dialog to select the filament when a print on a Prusa printer with MMU2 is startet in single mode.

The dialog is shown, when the plugin detects a 'Tx' command in the gcode.

So you don't have to go to your printer and select the filament to be used. It can now be done from within Octoprint.

A timeout can be set in the settings (default 30 seconds), after which the dialog is closed. When this happens you have to select the filament on the printer as usual.
