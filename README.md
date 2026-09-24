# Personal Learning Agent — Local-First AI Desktop Companion for Windows

**An experimental personal AI assistant for Windows that brings local language models, research memory, file organization, workflow learning, and a floating desktop companion together.**

[Report a bug](https://github.com/10GODS/PersonalLearningAgent-Windows/issues/new) · [Suggest a feature](https://github.com/10GODS/PersonalLearningAgent-Windows/issues/new) · [Contribute](CONTRIBUTING.md) · [Support development](SPONSORS.md)

![Concept illustration of the Personal Learning Agent architecture](assets/architecture.svg)

> **Development status:** Experimental Windows prototype. The repository currently publishes project documentation and community materials, **not the application source code or an installable Windows release**. The existing Python prototype and local model downloads are not hosted here. Features below describe the project's prototype scope or development goals; functionality, reliability, and CPU/GPU performance have **not been independently validated on all Windows hardware**. The illustration is conceptual, not an application screenshot.

## Why build a personal learning agent?

Most chatbots respond to one conversation at a time. Personal Learning Agent explores a different workflow: helping a person organize their own local work, retrieve relevant project history, review changes, and turn repeated tasks into reusable skills. The aim is an assistant that becomes more context-aware through *reviewable memory and feedback*, rather than silently retraining model weights or recording everything a user does.

This project is especially interested in workflows involving **research papers, GIS and remote sensing, Python experiments, document preparation, and everyday Windows file management**.

## Project capabilities and planned improvements

| Area | Prototype scope or development goal |
| --- | --- |
| Local AI | Quantized GGUF models through a separately installed llama.cpp runtime; CPU operation and optional compatible GPU backends |
| Persistent memory | Save project context, indexed documents, task feedback, and experiment notes on the user's computer |
| Floating desktop companion | A small assistant with chat and notification surfaces, with selectable visual styles |
| File intelligence | Index eligible user files; propose organization changes and preview potentially disruptive operations |
| Research assistance | Use local documents and optional web/academic search to prepare grounded suggestions |
| Skills and experiments | Draft reusable workflow descriptions, record experiments, and track previous outcomes |
| Desktop automation | User-approved Teach + Replay workflows; **not** unrestricted autonomous control |
| Privacy controls | Reviewable observation scope, permission controls, and local storage by default |

**Important limitations:** A file scan is not full comprehension of every file. Screen learning is event-based and permission-limited, not nonstop recording of all applications. Generated suggestions can be wrong. Automatic desktop actions need verification, backups, and user approval. Downloaded third-party models and inference engines have their own terms and hardware requirements.

## Get involved — no coding required

You can help test and shape the project even though the private development source is not currently published.

- **Windows beta testers:** Open an issue with your Windows version, CPU/GPU, RAM, the step that failed, expected behavior, and a redacted error report. Never upload private screenshots, passwords, browser histories, or research data.
- **Researchers and students:** Describe a real document, experiment, citation, GIS, or notebook workflow where a personal agent could save time.
- **Designers and accessibility contributors:** Suggest companion styles, keyboard navigation, screen-reader behavior, and clear safety/permission prompts.
- **Developers:** Propose features or request collaboration through an issue. Direct code contributions need a separately shared, appropriately licensed source tree.

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidance. Small, clearly scoped issues are welcome.

## Follow development and help the project grow

If this is relevant to you, **Star** the repository, **Watch** it for updates, share it with someone working on local AI or Windows automation, and describe the feature you would most like to test in an issue. Honest feedback and reproducible bug reports are more valuable than automated stars or promotional spam.

See [Project overview and roadmap](PROJECT_OVERVIEW.md) for use cases, planned work, and frequently asked questions.

## Support development

Maintaining a local-first Windows agent means testing different CPUs, Intel/NVIDIA/AMD graphics, accessibility, document formats, and privacy protections. Voluntary support can help fund that work. See [SPONSORS.md](SPONSORS.md) for ways to support development; **payments are not enabled merely by listing a sponsorship link**.

[Learn about GitHub Sponsors](https://github.com/sponsors) · [GitHub Sponsors profile, if activated](https://github.com/sponsors/10GODS)

## Privacy, licensing, and distribution

This repository intentionally does **not** contain personal memories, screenshots, credentials, AI model weights, downloaded inference binaries, or the private development source. Never attach these materials to public issues.

**Source availability:** The source code is not currently distributed through this public repository. A public repository is not automatically open-source software; no repository-level software license has been announced. We welcome feedback, documentation suggestions, design ideas, and collaboration discussions without implying permission to modify or redistribute unpublished code. Third-party packages and models retain their respective licenses.
