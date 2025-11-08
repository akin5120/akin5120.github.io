---
layout: case-study
title: "ViTAL VR Bioadaptive Hockey Training"
subtitle: "A VR sports simulation that adapts to physiological data in real time"
slug: "vital-vr-bioadaptive-hockey"
permalink: /projects/vital-vr-bioadaptive-hockey/
date: 2025-10-07
cover_image: "/assets/projects/vital/cover.jpg"
role: "UX Designer & Developer"
tools: ["Unity", "ViTAL SDK", "C#", "Polar H10", "EmotiBit", "MongoDB", "Streamlit", "Blender"]
duration: "2024–2025"
team: "BioAdaptive Interface / Immersive Design Lab, Wilfrid Laurier University"
tags: ["VR", "Biofeedback", "Physiological Computing", "Adaptive Systems", "Sports Tech", "UX Research"]
demo_url: "REPLACE_WITH_DEMO_OR_VIDEO_LINK"
repo_url: "REPLACE_WITH_REPO_IF_PUBLIC"
gallery:
  - src: "/assets/projects/vital/shot-1.jpg"
    alt: "Penalty shot scene in VR"
    caption: "Penalty shot scenario with dynamic goalie speed."
  - src: "/assets/projects/vital/shot-2.jpg"
    alt: "Adaptive crowd lighting"
    caption: "Lighting and ambience adapt to arousal."
  - src: "/assets/projects/vital/shot-3.jpg"
    alt: "ViTAL dashboard"
    caption: "Post-session visualization of HR and events."
seo:
  description: "VR hockey training that adapts to heart rate and arousal using ViTAL SDK and wearables."
  image: "/assets/projects/vital/cover.jpg"
  keywords: ["VR", "biofeedback", "adaptive training", "physiological computing", "Unity", "sports tech"]
---

## Overview
Designing a **bioadaptive hockey training** experience where the environment responds to a player’s physiological signals in real time. The prototype connects **Polar H10** and **EmotiBit** sensors to a Unity simulation via the **ViTAL SDK / LSL**, adapting lighting, crowd ambience, and goalie behavior to support focus and resilience.

## Problem
Traditional training tracks movement, not inner state (stress, arousal, fatigue).
**How might we** use real-time physiology to **shape task difficulty and feedback** so players stay in the optimal training zone?

## Process

### Setup & Sensor Integration

* Integrated **Polar H10** and **EmotiBit** via **LSL**, configured ViTAL SDK streams.
* Built data logging to **MongoDB** with **Streamlit** views for replay & analysis.

### Interaction & Gameplay Design

* **Penalty shot** mini-game with grabbing, timed rounds, scoring UI, and feedback.
* Unity UI for **start**, **timer**, **score**, and **game over** states.

### Adaptive Components

* **Light intensity** scales with arousal.
* **Goalie speed** increases as calmness rises.
* **Puck spawn rate** adapts to sustained focus/fatigue trends.
* All adaptation occurs **in real time** via normalized signal channels.

### Testing & Iteration

* Demoed with youth players/coaches; refined onboarding and UI clarity.
* Reduced SDK coupling by building a **clean LSL MVP** for stability and extensibility.

## Solution
A VR training loop that **mirrors a player’s inner state**, making difficulty and ambience responsive—not static.

## Impact

* First lab demo of **real-time biofeedback in VR sports**.
* Sparked interest from local organizations for mental-performance training.
* Informed the **ViTAL dashboard** roadmap (session review, signal correlation).

## Reflection
Designing **transparent adaptation** is key—players should feel the system responding *with* them. Next steps: multi-scenario sports pack and comparative studies on performance and adherence.

## Links

* Demo: {{ page.demo_url | default: "#" }}
* Repo: {{ page.repo_url | default: "#" }}


