# Text for the CurseForge project page (copy and paste)

**Summary (one line):** Starter node locations (mining and herbalism, Classic) for the Trailsmith addon. Data from GatherMate2.

---

# GatherTrailData

GatherTrailData is the **starter database** for [Trailsmith](https://www.curseforge.com/wow/addons/trailsmith). It contains known locations of mining nodes and herb nodes for WoW Classic, so Trailsmith can show the arrow, the minimap icons and the world map icons from the first minute, without you having to gather every node first.

## How it works

- It is a **load-on-demand data addon with no code**: it only defines the node tables.
- Trailsmith reads those tables for the zone you are in and converts the positions to game coordinates. It then shows them as icons (green ring = your skill is enough, red = too low).
- When you gather one of these spots, Trailsmith marks it as **confirmed**.
- The data shows where a node **can** spawn. It does not tell whether a node is up right now; the game tracking (*Find Minerals* / *Find Herbs*) does.

## Install

Put the `GatherTrailData` folder next to `Trailsmith` in `Interface/AddOns`, or install both from CurseForge. Without this addon Trailsmith still works, but it only shows the spots you gather or learn yourself.

## Credits and license

The node data comes from **GatherMate2_Data** by kagaro, Xinhuan and Nevcairiel (Classic copy by Thurdi), mined from Wowhead, and is used **unmodified**. It is distributed under the **GNU GPL v2 or later**, so this package is GPL-2.0-or-later. All credit for the data goes to those authors. Trailsmith itself is MIT and is a separate project.

## Project setup notes (for the author, not for the page)

Set the license to GPL-2.0 and credit GatherMate2 in the description (already included above).
