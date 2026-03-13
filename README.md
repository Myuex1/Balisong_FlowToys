# Balisong Flowtoys

A smart flow toy with embedded electronics, custom PCB, and persistence-of-vision LED effects. Hardware, firmware, and mechanical design from scratch.

**[balisongflowtoys.com](https://balisongflowtoys.com)** · **[@balisong.flowtoys](https://instagram.com/balisong.flowtoys)**

---

## What It Is

A butterfly knife trainer built for flow arts, with 68 individually addressable LEDs embedded in a custom PCB along the handle. Spin it fast enough and the LEDs paint patterns in the air. The hardware tracks orientation in real time and the firmware responds accordingly.

This started as a personal project and turned into a product. There is a tiered line in development with calculated margins of $65 to $200 per unit depending on feature set. Market demand was validated through surveys with the target audience before any money was spent on fabrication.

---

## Hardware

The handle contains a custom PCB designed in KiCad and fabricated through JLCPCB. It carries an ESP32, a gyroscopic sensor, and 68 individually addressable LEDs arranged for maximum persistence-of-vision coverage. The board was designed around refresh rates that support POV effects at spin speeds above 5 RPS.

The enclosure is printed in PA6-CF, seealed in cyanoacrylate and thin polyurethane using a Bambu P1S. Getting the geometry right for a snap-fit assembly took significant iteration around the PCB slot tolerances.

---

## Status

First PCB revision in hand. Second revision in progress. Mechanical redesign and firmware to follow.

---

## Notes

This repository contains project documentation and design notes. Firmware and PCB files are not public.

---
