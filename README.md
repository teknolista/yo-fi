<p align="center">
  <img src="yo-fi.png" alt="Yo-Fi logo" width="128">
</p>

<h1 align="center">Yo-Fi</h1>

<p align="center"><strong>Community Wi-Fi sharing</strong></p>

Yo-Fi is a multiplatform project for community Wi-Fi sharing. Development starts with the native Android app. The promotional landing page will be developed after the app is complete.

## Subprojects

| Project | Development tools | Status |
| --- | --- | --- |
| [Android app](android/README.md) | Android Studio, Kotlin, Jetpack Compose, Gradle | Initial workspace |
| [Landing page](www/README.md) | HTML, CSS, Node.js tooling | Initial workspace for later development |

Each subproject keeps its source and build configuration in its own directory. The Android app will offer language selection, including English, Brazilian Portuguese, and Spanish.

## Development

- [PentaPRO](pentapro/) holds the five-pillar specification and native change records.
- [Development strategy](docs/DEVELOPMENT-STRATEGY.md) describes how the Android pilot will be specified, implemented, and verified.
- [Pilot log](docs/DEVELOPMENT-LOG.md) records the setup baseline and development evidence.
- [Product discovery notes](docs/Yo-Fi_ideia.md) capture the original concept in Portuguese. The first Android journey and its acceptance criteria are pending discovery.
- [Repository instructions](AGENTS.md) cover shared conventions, including English for repository content and localized app text.

## Data Privacy

- **No personal data** is collected
- **No cookies** are used for tracking
- Test results are stored **only in your browser's localStorage**
- **No server-side** storage of individual responses
- Users can clear all data by clearing browser storage

## License

This project is licensed under the **GPL v3.0 License**.

See [LICENSE](LICENSE) for more details.

---

<p align="center"><small>
Copyleft © 2026 <a href="https://x.com/teknolista">Raul Bras</a> 🇧🇷 Published under the GPL v3.0 license. <br>
Made in Brazil, in the Land of Oz (SP) , with 🌭 🍕 and AI 🤖.
</small></p>

## PentaPRO specification

The [repository-root PentaPRO structure](pentapro/README.md) contains the five pillars, supporting assets, and native change records. Its [status record](pentapro/process/index.md) identifies confirmed project context, pending decisions, and the next discovery step.


## AI development workflow

This repository uses project-local PentaPRO skills and factory agent profiles with the native PentaPRO workflow. See [agent instructions](AGENTS.md) for the project workflow. The [continuous improvement protocol](docs/agents/continuous-improvement.md) describes PDSA and the [lessons record](docs/agents/lessons-learned.md); substantial factory runs use the [execution-record guide](docs/agents/runs/README.md). Lessons are recorded in English.
