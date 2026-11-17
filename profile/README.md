# Mbotics 🤖

Open robotics, ESP32 and home‑automation projects: built at home, documented so anyone can build them too.

Every project has its own repository with the same layout:

```
project/
├── README.md     overview and quick start
├── firmware/     code (Arduino / ESP32)
└── docs/         circuit diagram, code explained, setup guide, project report
```

## Projects

| Project | What it does | Hardware |
|---|---|---|
| [home-smart-control](https://github.com/Mbotic-org/home-smart-control) | Control home lights with Alexa, Google Home or a phone app | ESP32, 3‑channel relay, Sinric Pro |
| [diwali-led-controller](https://github.com/Mbotic-org/diwali-led-controller) | 1000‑pixel LED wall with 98 effects, scrolling text and a web dashboard | ESP32, WS2811 pixels, FastLED |

## Conventions

- Passwords and API keys live in a git‑ignored `secrets.h`; each project ships a `secrets.example.h` template.
- Each project's `docs/` folder has a circuit diagram, a code walkthrough, a setup and troubleshooting guide and a project report.

New projects are added as new repositories here.
