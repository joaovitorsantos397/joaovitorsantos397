# Hi, I'm João Vitor 👋

🎓 Computer Engineering student at the University of Campinas (Unicamp)

## About Me

I'm a Computer Engineering student at Unicamp interested in backend, data, IoT and applied AI. I like building software that solves real problems, and I care about how a system behaves when it is actually running, not only in theory.

I build my own projects end to end, from product decisions to implementation, and I do undergraduate research (PIBIC) in a physics lab at Unicamp.

I'm looking for a summer internship (December 2026 to February 2027) in backend and applied AI.

## Current Projects

🥗 **[AI Diet Manager](https://github.com/joaovitorsantos397/AI-Diet-Manager)**

A conversational AI nutrition coach, not just a calorie tracker: five coach personalities, meal logging by text, and progress tracking (calories, protein, weight, adherence streaks). The model triggers typed function calls (log or remove a meal), declared with a schema on the server, instead of writing numbers as free text, so the app computes the totals. The project has 24 unit tests (Vitest) and CI on GitHub Actions.

🍛 **[Bandejão Tracker](https://github.com/joaovitorsantos397/Bandejao-Tracker)**

Fetches Unicamp's university restaurant daily menu, which has no public API, and serves it as clean JSON. I built it after finding that the real menu lives in an internal system embedded as an iframe, not in the page meant for people to read. Next step: feed the menu into AI Diet Manager so the coach can estimate a meal from the dishes actually served that day.

## Research

🔬 **Undergraduate Research (PIBIC) at LaRMNuQ, IFGW/Unicamp**

LaRMNuQ is the Nuclear Magnetic and Quadrupolar Resonance Laboratory. The project is a centralized Python interface to control and monitor the instruments of an NMR system, with local and remote access. Several instruments already have their own control tools, but nothing unifies them.

So far I have established direct communication with a cryogenic temperature controller, a helium level monitor and a magnet controller over USB serial, and I wrote a prototype logger (pySerial) that reads temperature and level and saves them to CSV with timestamps. Next, I'm integrating the oscilloscope over the network with VISA/pyVISA and moving toward an API with independent modules for each instrument.

## Technologies

### Languages
- Python
- TypeScript / JavaScript

### Stack
- React, Vite, Node.js / Express (REST APIs)
- Vitest, GitHub Actions
- pySerial (instrument communication over serial)
- Git and GitHub

### Currently Learning
- Data structures and algorithms (coursework)
- pyVISA and API design for the lab project

## Goals

- Build backend and data systems that hold up in production
- Keep applying AI in practical, user-facing products
- Do a summer internship in backend or applied AI

📫 Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/joaovitorsantos397).
