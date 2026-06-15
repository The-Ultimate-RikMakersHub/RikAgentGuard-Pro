# 🛡️ RikAgentGuard-Pro

Developed by **RikMakersHub**, **RikAgentGuard-Pro** is a lightweight, zero-dependency safety core and execution brake matrix designed to protect developers and makers from runaway autonomous AI coding agents.

## 🚀 Live Demo
🔗 **Try it here:** [https://github.io](https://github.io)

## ❌ The Problem
Modern autonomous AI coding agents (like Cursor Agent, Devin, and CLI operators) can easily hallucinate and get trapped in infinite recursive debugging loops. This causes rapid local workspace corruption and massive OpenAI/Anthropic API billing surprises within minutes.

## ⚡ The Solution
RikAgentGuard-Pro provides a deterministic execution tracking matrix running entirely in the browser. It monitors real-time agent telemetry log patterns, profiles operational loops inside a rolling time window, tracks token billing burn, and engages an automated emergency safety brake when thresholds are breached.

## ✨ Key Features
* **Deterministic Loop Profiler**: Automatically groups and counts identical or overlapping terminal scripts.
* **FinOps Cost Calculator**: Estimates API billing overhead in real time based on token activity streams.
* **Automatic Safety Brake Core**: Instantly kills or detaches the simulation loop when an anomaly index spikes.
* **Pure Client-Tier Architecture**: Built with pure, lightweight vanilla web components—no heavy backend or environment setup required.
* **GitHub Pages Ready**: Optimized for instant cloud deployment using static asset pipelines.

## 🛠️ Quick Start
1. Clone this repository under your local workstation environment.
2. Open `index.html` directly inside any standard modern web browser.
3. Click **"Launch Autonomous Agent Simulation"** to observe the underlying signature loop guard algorithm engagement in real time.
