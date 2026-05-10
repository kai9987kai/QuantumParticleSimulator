# Quantum Nexus Simulation — Advanced Research Lab

An advanced browser-based quantum-inspired particle simulation and visual research lab.  
This project turns a simple particle field into an interactive “Quantum Nexus” playground with entanglement links, superposition pulses, 4D projection effects, measurement collapse, trails, diagnostics, presets, export tools, and live simulation metrics.

> **Note:** This is an artistic and educational quantum-inspired simulation, not a physically exact quantum mechanics solver. It is designed for visual exploration, experimentation, learning, and creative coding.

---

## ✨ Features

### Core Simulation

- Interactive quantum-inspired particle system
- Hundreds to thousands of animated particles
- Particle position, velocity, phase, spin, charge, mass, coherence, and energy values
- Dynamic wave-function-style orbit points around each particle
- Quantum/classical state toggle
- Superposition pulse that redistributes and re-randomizes the system
- Measurement/collapse mode that simulates probabilistic spin collapse
- Entanglement pairing between particles
- Entanglement force links and live pair counter
- Click-generated quantum fields
- Drag-based attractor interaction
- Shift-click repulsive field support

---

## 🧬 Quantum-Inspired Systems

The simulation includes several abstracted quantum-style mechanics:

### Superposition

The **Superposition** button spreads particles into a new phase configuration, refreshes their wave-function points, raises coherence, and creates a more energetic visual state.

### Entanglement

Particles can pair with each other based on the current entanglement strength. Entangled particles influence each other’s motion, phase, spin, and coherence. Their connection is visualized using glowing curved links.

### Measurement Collapse

The **Measure / Collapse** button performs a probabilistic measurement across the particle field. Particles collapse into spin-up or spin-down states, coherence is reduced, and the UI reports the resulting measurement distribution.

### 4D Projection

The **4D Projection** mode adds a dimensional lens effect using phase, theta, and perspective warping. This creates a galaxy-like projection where particles appear to rotate through a higher-dimensional visual space.

---

## 🎛️ Controls

### Main UI Controls

| Control | Description |
|---|---|
| **Toggle State** | Switches between quantum-active and more classical/decohered behavior |
| **Measure / Collapse** | Performs a probabilistic measurement across the system |
| **Entanglement Strength** | Controls how often particles become entangled and how strongly they interact |
| **Superposition** | Reinitializes the system into a high-coherence superposition-like state |
| **4D Projection** | Enables or disables perspective/warp-based 4D visual projection |
| **Lens Warp** | Controls the strength of the 4D projection distortion |
| **Toggle Trails** | Shows or hides particle history trails |
| **Trail Length** | Adjusts how long particle trails remain visible |
| **Particle Speed** | Controls base movement speed |
| **Field Gravity** | Adjusts how strongly click-generated quantum fields affect particles |
| **Add Particles** | Adds more particles into the current simulation |
| **Target Count** | Resets the simulation to the selected particle count |
| **Color Mode** | Changes how particles are colored |
| **Glow** | Adjusts particle glow intensity |
| **Pause / Resume** | Freezes or resumes the simulation |
| **Reset** | Rebuilds the simulation with the current settings |
| **PNG** | Exports a snapshot of the canvas |
| **Record** | Records the simulation as a `.webm` video where supported |
| **Help** | Opens the keyboard shortcut and project info panel |

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
|---|---|
| `Space` | Pause / resume |
| `Q` | Toggle quantum state |
| `S` | Activate superposition |
| `M` | Measure / collapse |
| `4` | Toggle 4D projection |
| `T` | Toggle trails |
| `R` | Reset simulation |
| `H` or `?` | Toggle help panel |

---

## 🖱️ Mouse / Pointer Controls

| Action | Result |
|---|---|
| Click canvas | Creates an attractor quantum field |
| Shift + click | Creates a repulsive quantum field |
| Drag on canvas | Pulls particles toward the pointer |
| Move pointer | Updates the live interaction point |

---

## 🌈 Render Modes

The simulation includes several color modes:

| Mode | Description |
|---|---|
| **Phase Spectrum** | Colors particles based on phase and index |
| **Spin / Charge** | Colors particles based on spin and charge properties |
| **Energy Heat** | Colors particles based on kinetic energy |
| **Entangled Pairs** | Highlights entangled particles differently from unpaired particles |

---

## 🧪 Presets

The project includes built-in simulation presets:

| Preset | Description |
|---|---|
| **Balanced Nexus** | Default balanced particle field |
| **Calm Decoherence** | Slower, smoother, lower-energy simulation |
| **Entanglement Storm** | High entanglement, high energy, dense visual activity |
| **Quantum Tunnel** | Strong warp, gravity, and energy-based coloring |
| **4D Galaxy** | Large particle count with 4D projection enabled |

---

## 📊 Live Diagnostics

The interface includes a real-time HUD with:

- **Coherence**
- **Energy**
- **Entropy**
- **Active quantum fields**
- **FPS**
- **Entanglement pair count**
- **Reality stability estimate**
- **Particle count**
- **Render quality mode**

A Bloch-style phase diagnostic panel is also included to show an abstract average state vector for the current particle system.

---

## 📸 Export Tools

### PNG Snapshot

Click **PNG** to export the current canvas frame as an image.

### WEBM Recording

Click **Record** to start recording the canvas. Click it again to stop and export a `.webm` video.

Recording support depends on the browser’s `MediaRecorder` and `canvas.captureStream()` support.

---

## 🚀 Getting Started

### 1. Download the Project

Save the HTML file as:

```text
index.html
