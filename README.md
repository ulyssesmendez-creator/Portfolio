# Ulysses Mendez — Interactive Desktop Portfolio

An interactive Windows 95 inspired portfolio built using pure HTML, CSS, and Vanilla JavaScript.

Instead of a traditional scrolling website, this project recreates parts of the Windows 95 desktop operating system experience in the browser. Users interact with draggable windows, a start menu, and application style project views.

Live Demo: https://ulyssesmendez-creator.github.io/Portfolio/

---

## Concept

The site simulates a retro desktop environment where each project opens in its own draggable window.

The interface includes:

- Draggable window system
- Dynamic z index window stacking
- Start menu with external links
- Project popups
- Real time clock
- OS style layout and styling

All built without frameworks.

---

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- DOM manipulation
- Event handling
- Dynamic z index management

---

## System Architecture

The project is structured around:

- A desktop layer (main screen)
- Window components (popups)
- State driven open/close behavior
- Custom drag logic
- Controlled boundary constraints for window movement

Each window manages:

- Visibility
- Position
- Z index priority
- Close interaction
- Drag interaction
