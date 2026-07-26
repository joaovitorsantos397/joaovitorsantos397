# Hi, I'm João Vitor 👋

🎓 Computer Engineering Student at the University of Campinas (Unicamp)

## About Me

I'm a Computer Engineering student at Unicamp passionate about building software that solves real-world problems. I'm particularly interested in Artificial Intelligence, Mobile Development, Internet of Things (IoT), and Software Engineering.

Currently developing personal software projects end-to-end — from product thinking and architecture decisions to implementation — while also doing undergraduate research in IoT architectures for scientific instrumentation.

## Current Projects

🥗 **[AI Diet Manager](https://github.com/joaovitorsantos397/AI-Diet-Manager)**

A conversational AI nutrition coach, not just a calorie tracker: five distinct coach personalities, meal logging via text, photo, or audio (with Gemini vision and transcription), and evolution tracking (calories, protein, weight, adherence streaks). The system prompt is deliberately engineered around a common failure mode in AI diet apps — hallucinated or double-counted totals — by grounding every response in numbers computed by the app itself, not reconstructed from conversation memory.

🍛 **[Bandejão Tracker](https://github.com/joaovitorsantos397/Bandejao-Tracker)**

Fetches Unicamp's university restaurant (RU) daily menu — which has no public API — and serves it as clean JSON. Built after discovering the real menu lives in an internal system embedded as an iframe, not the page meant for humans to read. Integrates with AI Diet Manager so the coach can ground a bandejão meal estimate in the actual dishes served that day instead of guessing generically.

## Research

🔬 **Undergraduate Research (Iniciação Científica)** — IoT Orchestration for Scientific Instrumentation

Some of the seven laboratory peripherals already have individual control tools (e.g. LabVIEW, Visual Basic), but no unified interface exists to orchestrate all of them together — and those legacy tools are hard to maintain and poorly suited to modern networked architectures. The plan: a microservices architecture with a central Core API (users, logs) and per-device Instrument Adapters behind a hardware abstraction layer, so adding a new instrument means writing one adapter, not touching the core. A Python backend (pyVISA, pySerial) exposes a real-time web interface — a REST API for direct commands, an MQTT pub/sub broker for continuous monitoring — built on FastAPI, with a hybrid PostgreSQL + InfluxDB store for config data and high-frequency sensor time series, secured with JWT and SSH/RSA.

Currently in the early stages: peripheral connections, driver installation, and communication validation with the control terminal — the necessary groundwork before this architecture gets built.

## Technologies

### Languages
- Python
- C++
- TypeScript / JavaScript

### Stack
- React, Vite, Node.js/Express
- Git & GitHub
- Linux

### Currently Learning
- iOS Development with Swift
- Mobile Development
- Software Architecture at scale

## Goals

- Build high-quality, well-documented software
- Learn iOS Development with Swift
- Keep applying AI in practical, user-facing products
- Contribute to innovative technology projects

📫 Feel free to connect with me on LinkedIn!
