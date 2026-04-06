<p align="center">
  <img src="prism-dodeca.png" alt="PrismAI" width="140" height="140">
</p>

<h1 align="center">PrismAI</h1>

<p align="center">
  Local-first AI workspace with constitutional governance, multi-lens council deliberation, and mixed-provider routing.<br />
  Built on <a href="https://github.com/Mintplex-Labs/anything-llm">AnythingLLM</a>.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-0.3.1-blue" alt="Version 0.3.1">
  <img src="https://img.shields.io/badge/platform-macOS-lightgrey" alt="macOS">
  <img src="https://img.shields.io/badge/license-MIT-green" alt="MIT License">
</p>

---

## Download

| Platform | Architecture | Download | Status |
|---|---|---|---|
| macOS | Apple Silicon (M1/M2/M3/M4) | [PrismAI-0.3.1-macos-arm64.dmg](https://github.com/Transformation-Agency/prismai-releases/releases/download/v0.3.1/PrismAI-0.3.1-macos-arm64.dmg) | Signed |
| macOS | Intel | [PrismAI-0.3.1-macos-x86_64.dmg](https://github.com/Transformation-Agency/prismai-releases/releases/download/v0.3.1/PrismAI-0.3.1-macos-x86_64.dmg) | Unsigned |

> **Intel Mac users:** Because the Intel build is currently unsigned, macOS will block it. To open: right-click the app → **Open** → click **Open** on the warning. You only need to do this once.

## What is PrismAI?

PrismAI is a desktop AI workspace that runs entirely on your machine. Chat with your documents, use AI agents, and deliberate across multiple AI perspectives — all governed by constitutional principles that keep outputs aligned with your values.

### Key Features

- **Council Deliberation** — Query multiple AI lenses simultaneously and get synthesized, multi-perspective responses
- **Constitutional Governance** — 9-stage action validator ensures AI outputs align with your governance rules
- **200+ Built-in Lenses** — Specialized AI perspectives across 20+ constellations
- **Mixed-Provider Routing** — Use OpenAI, Anthropic, Grok, Ollama, and others in the same council
- **Custom Lens Creator** — Build your own lenses with LLM-assisted formatting
- **RAG Pipeline** — Chat with PDFs, Word docs, code, web pages, and more
- **Agent Framework** — Custom skills, tool calling, and MCP support
- **25+ LLM Providers** — OpenAI, Anthropic, Google Gemini, Ollama, LM Studio, DeepSeek, Groq, and more
- **Local-First** — Your data stays on your machine. No cloud dependency required.

## Installation

1. Download the DMG for your Mac from the table above
2. Open the DMG and drag **PrismAI** to your Applications folder
3. Launch PrismAI from Applications
4. Follow the setup assistant to configure your AI providers

## System Requirements

- macOS 12 (Monterey) or later
- 8 GB RAM minimum (16 GB recommended)
- 2 GB disk space for the app + space for your documents

## Verify Downloads

Each release includes a `SHA256SUMS.txt` file. Verify your download:

```bash
shasum -a 256 -c SHA256SUMS.txt
```

## Feedback and Issues

Found a bug or have a feature request? [Open an issue](https://github.com/Transformation-Agency/prismai-releases/issues).

## License

MIT License. Built on [AnythingLLM](https://github.com/Mintplex-Labs/anything-llm) by [Mintplex Labs](https://mintplexlabs.com).
