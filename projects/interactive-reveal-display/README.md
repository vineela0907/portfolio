# Interactive Reveal Display

A walk-up screen for events. A camera above the display detects a person walking past, and a glass or particle layer dissolves on their side of the screen to reveal the product beneath. No touching needed.

## How it works
1. A webcam watches the area in front of the screen.
2. The app learns the empty background, then detects movement.
3. A canvas particle layer clears where the visitor stands, revealing the pack shot.
4. When they leave, the layer settles back.

## Features
- Separate screens for each product range, in landscape and portrait
- Keys for background learning (B), tuning panel (D), fullscreen (F) and mirroring
- Automatic particle reduction to keep the frame rate smooth
- Self-healing for long events: camera reconnect, error reload, refresh every 6 hours
- One-click Windows launchers that open the screen in Chrome kiosk mode
- Event checklist for set-up

## Tech
Single-file HTML, CSS and JavaScript, canvas, webcam via getUserMedia, PowerShell and batch launchers.

## My role
Concept, development and event deployment.

*Screenshots / screen recording: to be added with neutral artwork.*
