# 🦇 Desktop Batman Pet: High-Performance Event-Driven Workspace Agent

[![Python Version](https://img.shields.io/badge/Python-3.14%2B-blue.svg)](https://www.python.org/)
[![UI Framework](https://img.shields.io/badge/GUI-Tkinter-orange.svg)](https://docs.python.org/3/library/tkinter.html)
[![Deployment](https://img.shields.io/badge/Compiler-PyInstaller-red.svg)](https://pyinstaller.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

An optimized, borderless desktop agent executing real-time Win32 window manipulations, precise chroma-key transparency masking, and asynchronous frame-sequential animation pipelines. Built entirely on the Python Standard Library to ensure an incredibly low runtime footprint.

---

## 🛠️ Tech Stack Architecture

This project prioritizes a **zero-dependency runtime architecture**, bypassing bloated modern frameworks (like Electron or heavy game engines) in favor of lightweight, system-native components:

| Layer / Component | Technology | Architectural Role & Implementation |
| :--- | :--- | :--- |
| **Core Runtime** | **Python 3.14+** | Powers the core scripting logic, cross-platform string manipulation, and system lifecycle hooks. |
| **GUI & Window Engine**| **Tkinter / Tcl** | Leverages native C-bindings wrapper to handle window-decoration stripping, topmost Z-indexing, and asynchronous event loops. |
| **Asset Processing** | **Tkinter.PhotoImage**| Manages lightweight structural image matrices directly in RAM, caching multi-frame PNG sprite sheets for instant access. |
| **Chrono-Scheduling** | **Tcl/Tk `after()` API** | Replaces blocking execution structures (`time.sleep`) with a non-blocking asynchronous event dispatcher pipeline. |
| **Algebraic Mechanics** | **Python `random` / Math** | Drives pseudo-random distribution metrics for life-like animation loops and real-time screen vector translations. |
| **Compilation Pipeline**| **PyInstaller 6.x** | Bundles interpretation assets, compiled byte-code, and system binaries into a standalone, unattached process payload (`--onefile`, `--noconsole`). |

---

## 💡 Executive Summary (For Clients)
Looking to add personality, engagement, or custom micro-notification agents to a software ecosystem? This project proves that custom branding assets can live directly on a user's desktop natively—**without the bloat of Electron or heavy third-party runtimes.** By bypassing traditional operating system borders, this architecture provides a clean blueprint for building lightweight background utilities, interactive brand mascots, or real-time corporate health and task alerts directly into employee workflows.

---

## ⚙️ Deep Technical Implementation (For Devs)

Instead of spawning resource-intensive multi-threaded processes, this system manages concurrent tasks using asynchronous callback queues attached natively to the `Tcl/Tk` event loop engine.

### 🎥 Non-Blocking Sprite Animation Pipeline
* **State Engine:** Character states transition fluidly via a dedicated recursion loop. Frame buffers (`batman1.png` to `batman4.png`) load natively into isolated image objects.
* **Frame Interpolation:** To eliminate CPU blocking, frame progression drops traditional `time.sleep()` loops in favor of asynchronous scheduler hooks (`root.after(80, ...)`). This ensures the interface remains completely interactive during fast-paced 80ms blink animations.
* **Deterministic Randomization:** Interval deltas between animations are computed at runtime using a pseudo-random distribution algorithm (`random.randint(2000, 6000)`), successfully mimicking organic behavioral patterns.

### 🪟 Win32 Core Layering & Chromatic Chroma-Keying
* **System Decoration Stripping:** Implements `overrideredirect(True)` to cleanly strip Windows border wrappers, caption bars, window menus, and taskbar handles—exposing raw graphical pixels directly to the monitor matrix.
* **Canvas Masking:** Assigns a specific system hex background (`#abcdef`) mapped directly to the Win32 transparency color-key attribute (`-transparentcolor`). The OS desktop manager dynamically drops rendering for matching pixel bounds, resulting in borderless, free-floating alpha-channel silhouettes.
* **Z-Index Layer Locking:** Applies a rigid hardware topmost flag (`-topmost`), locking the agent consistently over the OS workspace compositor layer.

### 📐 Pointer Vector Translation (Drag-and-Drop Handler)
* **On-Click (`<Button-1>`):** Caches local coordinate structural layout offsets $(x, y)$ the millisecond the mouse clicks the widget surface.
* **On-Motion (`<B1-Motion>`):** Computes differential position vectors ($\Delta x, \Delta y$) dynamically. The agent routes these high-frequency calculation streams directly into window translation queries (`root.geometry`), ensuring seamless, lag-free sliding physics over multi-monitor configurations.

### ⛓️ Finite State Machine Notification Queuing
* **Onboarding Optimization:** Features a progressive time-delay barrier (30,000ms execution gates) during early lifecycle cycles to maintain rapid, high-impact user engagement.
* **Idle State Throttling:** Programmatically downgrades to a macro background clock (120,000ms execution gates) once the agent passes baseline onboarding milestones. This prevents unnecessary loop cycles and maximizes system power efficiency.
* **Memory-Safe Recycling:** Loops array indexes using explicit index pointer resetting, completely preventing out-of-bounds pointer exceptions or memory accumulation leaks.

---

## 🎯 Professional Competencies Demonstrated (For Employers)

This project showcases clean development principles, cross-platform compilation insight, and rigorous optimization, including:
1. **Zero-Dependency Architecture:** Leverages deep native framework features rather than relying on massive external npm or pip libraries, preserving extreme code agility.
2. **Resource-Mindful Engineering:** Implements strict event-driven programming hooks instead of costly CPU spin-locks, achieving a near-zero background footprint.
3. **Optimized Binary Bundling:** Leverages low-level compiler arguments (`--noconsole`, `--onefile`) to eliminate attached shell processes and ship consumer-ready standalone executable payloads.

---

## 📦 Run & Local Compilation Guide

### Standard User Installation
1. Download the repo as a **ZIP** archive and extract it.
2. Verify that `yourbatman.exe` is in the identical folder directory as the 4 image assets (`batman1-4.png`).
3. Launch **`yourbatman.exe`** to deploy the agent. Left-click and drag to move; right-click to gracefully terminate.

### Source Control Execution
```bash
# Clone repository code
git clone [https://github.com/YOUR-USERNAME/desktop-batman-pet.git](https://github.com/YOUR-USERNAME/desktop-batman-pet.git)
cd desktop-batman-pet

# Execute standard local runtime interpreter
python yourbatman.py

# Build optimized production-ready Win32 standalone binary
"C:\Path\To\Scripts\pyinstaller.exe" --noconsole --onefile yourbatman.py