# Changelog

All notable changes to **Musee** will be documented in this file.

## [1.0.0] - Initial Production Release

### ✨ Features
- **Modern Fluent / Acrylic Aesthetic**: Tailored for Windows 10 and Windows 11 with seamless dynamic theme tinting extracted from album artwork.
- **Studio-Grade DSP Audio Processor**:
  - Andy Simper Cytomic Linear Trapezoidal State Variable Filters (SVF) with zero-click coefficient smoothing.
  - 5 Tuned Audio Presets: **Normal**, **Bass Boost** (with psychoacoustic sub-bass punch harmonic exciter), **Muffled** (24dB/oct acoustic absorption curve), **Electronic**, **Rock**, and **Vocal Booster**.
  - Dynamic Slider Intensity with transparent analog soft-knee saturation that prevents digital clipping.
- **Smart YouTube Music-Style Queue Flow**:
  - Automatically seeds and organizes upcoming songs based on mood, tempo, vibe compatibility, and listening history.
  - Zero repetitive loops with acoustic diversity weighting.
- **Personal Listening Habits & Analytics Hub**:
  - Collapsible minimalistic profile hub located on the Home screen.
  - Total playtime metrics, completed track counts, top artists, top songs, time-of-day listening breakdown, and musical vibe distribution.
- **Native Windows Desktop Integration**:
  - Global hardware Windows Media Keys (`Play`/`Pause`, `Next`, `Previous`) supported from background or while gaming.
  - Custom immersive Windows Title Bar styling with high-resolution app icon.
  - Start Menu, Desktop shortcuts, and native Windows installer (`.msi`).
- **High-Performance Architecture**:
  - $O(1)$ playtime accumulation, Padé $[3/2]$ rational fast approximations, and state collection isolation preventing unnecessary recompositions.
  - Extremely light on laptop battery and CPU resources.
