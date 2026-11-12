# Hi, I'm Dane 👋

I build **[Mokxi](https://mokxi.com)**, an electronics workbench that runs in your browser: a breadboard, real parts, wires and microcontroller boards next to a code editor. Press Run, and the circuit and the firmware run together in real time, with nothing simulated or compiled on a server.

**[Try it at mokxi.com →](https://mokxi.com)**

You can find all my cool projects at my personal website, **[danedolph.com](https://danedolph.com)**.

## What's under the hood

Mokxi is built from scratch, end to end: no other simulator's code is inside it.

- **Own CPU cores in Rust, compiled to WebAssembly:** AVR (Arduino Uno, Nano, Mega, Leonardo, ATtiny85), ARM Cortex-M (Raspberry Pi Pico, STM32, Arduino Uno R4), RISC-V (ESP32-C3, ESP32-C6) and Xtensa (ESP32, ESP32-S3, ESP8266).
- **A circuit simulator:** an event-driven digital kernel, plus an analog solver (modified nodal analysis, Newton-Raphson) for diodes, transistors, MOSFETs and op-amps, checked against ngspice.
- **A C++ compiler in the browser:** clang built to WebAssembly, so Arduino sketches build on the visitor's own machine. MicroPython and CircuitPython boards run too.
- **Simulated WiFi:** six boards can fetch pages, serve them and publish over MQTT through a simulated network.
- **The platform:** accounts, saved projects, live collaboration (Durable Objects), classrooms with auto-marked assignments, lessons, and Stripe subscriptions, all on Cloudflare Workers and D1.

## Stack

`Rust` · `WebAssembly` · `TypeScript` · `Vite` · `Cloudflare Workers` · `D1` · `Durable Objects` · `R2` · `Stripe` · `Playwright` · `Vitest` · `GitHub Actions`

## Numbers

- Launched September 2026, with paying customers and thousands of makers, students and teachers.
- 25+ simulated chips and boards, 800+ guide and project pages.
- Shipped by a solo founder working with AI coding agents. I run the merges, deploys and support myself.

## Get in touch

- 🐝 [danedolph.com](https://danedolph.com), all my projects
- 🌐 [mokxi.com](https://mokxi.com)
- 📫 Through the Contact page on mokxi.com
