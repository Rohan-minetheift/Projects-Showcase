# Projects

A short tour of the apps and builds I work on.

| Project | Category | Platform |
|---|---|---|
| [HIMGAURAV](#himgaurav) | Disaster information | Android · Web |
| [Align](#align) | Productivity | Android |
| [Agricore](#agricore) | IoT · Agriculture | Android + ESP32 |
| [Praxis](#praxis) | Digital wellbeing | Android |
| [Fluid Routine Planner](#fluid-routine-planner) | Productivity · Privacy | Android |

---

## HIMGAURAV

**Community reporting and Himalayan landslide research**

An English/Hindi community experience with local context, guided reporting and private receipts, paired with restricted review and research workflows. A shared foundation supports web and Android experiences.

**Design emphasis:** understandable information, source/freshness labels and human review.  
**Boundary:** a research prototype, not an official warning service or independently validated landslide predictor.

[View reviewed app screenshots, project story and dated verification results →](https://github.com/Rohan-minetheift/HIMGAURAV-Showcase)

---

## Align

**A consistency engine for everyday habits**

Align keeps daily routines in one place. It tracks streaks and runs focus/Pomodoro sessions. It also has a water goal, eye-care reminders and a brain dump with history. Data is stored on the device and can be exported to CSV or sent to Google Sheets.

`Flutter` `Riverpod` `Hive` · Android 7.0+

---

## Agricore

**Farm automation you set up on screen**

Agricore turns a phone into the control panel for an ESP32 sensor network. You drag sensors onto pins of a virtual board, and the app checks the wiring for duplicate or invalid GPIO pins and generates the configuration. It then connects to a master gateway over WebSocket to stream live readings from field nodes.

- Live node health: battery drain, board temperature and weak-signal alerts that suggest where to add a repeater node
- Master and node firmware setup guide, with node pairing by MAC address
- Simulation mode for trying it out without hardware

`Flutter` `ESP32` `WebSocket` · Android 7.0+

---

## Praxis

**A launcher that puts a pause between you and the scroll**

Praxis replaces the home screen with a calmer, minimal launcher. Its friction engine steps in when a distracting app is opened and adds a short delay and a breathing screen first, so opening it becomes a deliberate choice. It also includes a task scheduler and a screen-time analytics view.

`Kotlin` `Jetpack Compose` `Accessibility Service` · Android 8.0+

---

## Fluid Routine Planner

**Plan the day and keep private notes locked**

A routine planner with an encrypted vault for private entries. The vault is protected by fingerprint or device credential and stored with SQLCipher encryption. A floating overlay keeps the current routine visible over other apps.

`Kotlin` `Jetpack Compose` `SQLCipher` `Biometric` · Android 8.0+

---

## Also building

| Area | Project |
|---|---|
| Radar | Equivalent-time UWB timed-array radar simulator with polarity-coded sampling |
| Edge AI | Structured pruning of radar neural networks for mmWave sensors |
| Networking | Delay-tolerant mesh network for areas with no connectivity, built on ESP32 |
| RF | Microwave sensors and power-amplifier design studies |

---

<sub>Source code and configuration are private. See the [public-materials policy](SECURITY.md).</sub>
