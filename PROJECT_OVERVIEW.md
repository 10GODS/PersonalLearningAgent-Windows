# Project overview, discoverability, and community roadmap

## The project in one minute

**Personal Learning Agent** is an experimental Windows desktop AI companion for people who want local-first assistance with research, everyday files, and repeatable computer workflows. Its design combines a floating interface, local AI models, persistent memory, file indexing, reviewed skill discovery, and controlled desktop actions.

Unlike a cloud-only chat service, the project explores a model where the user's knowledge and project history remain on their PC. **It is not a product that has demonstrated unrestricted autonomous understanding of every screen or application.**

### Who might find it useful?

- **Researchers and students:** remembering experiment settings, organizing papers and notes, planning manuscript revisions, and checking repeated workflows.
- **Windows power users:** finding files, preparing folder-organization plans, and reusing approved desktop routines.
- **Local AI enthusiasts:** exploring quantized GGUF inference, CPU fallback, optional supported GPUs, and privacy-conscious application design.
- **Accessibility and UI designers:** building a visible, controllable companion with clear explanations and permission prompts.

## Contribute to the project

The public repository currently hosts documentation and community discussions. The private application source and installable builds are not yet distributed here. You can still contribute by opening issues with reproducible Windows test scenarios, proposing an accessible design, translating or improving public documentation, or submitting safe feature ideas. Discuss direct source-code collaboration with the maintainer first.

Suggested starter contributions:
1. Propose a privacy-safe test plan for Windows 10/11 on 8 GB RAM and Intel integrated graphics.
2. Design a clear screenshot/visual prototype for the floating companion, including a visible pause button.
3. Provide a redacted example of a document, file-management, or research workflow that an assistant could help with.
4. Improve the plain-language setup and troubleshooting documentation once a public executable is available.

Use [GitHub Issues](https://github.com/10GODS/PersonalLearningAgent-Windows/issues) to suggest a contribution.

## Development priorities

- **Trustworthy distribution:** signed or verifiably checksummed builds, reproducible installation instructions, and an honest feature matrix.
- **Memory continuity:** preserving learning records during updates with recovery and backup.
- **Useful local workflows:** safe file-management previews, reproducible skill definitions, and project-aware suggestions.
- **Accessibility:** keyboard navigation, readable speech bubbles, notification controls, and optional voice output.
- **Hardware testing:** measured performance and fallbacks on CPU-only systems and compatible graphics backends.

These are priorities and proposals, not delivery promises.

## Help people discover the project

Share an authentic, short demonstration that shows an action and its outcome. Good topics include a before/after file-organization preview, a reproducible document workflow, or a permission-controlled floating companion. Clearly label animations and concept art as illustrations, and do not represent simulated screens as measured results.

For meaningful feedback, include your hardware, Windows version, exact workflow, what happened, and whether the result could be reproduced. Never post private files or credentials.

## FAQ

**Is it a fully trained personal robot?** No. It uses local-model inference and persistent memory; automatically generated skills need verification.

**Does it constantly read everything on my screen?** No. The architecture is intended to make observation controllable, event-based, and limited to eligible activities.

**Can I download the Windows installer from this repository?** Not yet. This repository is currently for project information and community coordination.

**Can I contribute without programming?** Yes. Reproducible testing plans, accessibility suggestions, workflow descriptions, artwork, and documentation corrections are useful.

**Can I support the project financially?** Read [SPONSORS.md](SPONSORS.md). Any donation is optional; payment options must first be activated by the maintainer.

**Is the project open source?** No open-source license or full public source release has been announced here. Community participation and source availability are separate decisions.
