# MGL — Magnificent Language
### A Visual + Code-Based Data Processing Platform

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-1.0.0-green.svg)](CHANGELOG.md)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

## What is MGL?

**MGL (Magnificent Language)** is an open-source, web-based data processing platform that lets you write, visualize, and execute data pipelines in your browser — no setup required.

It combines a **custom scripting language**, a **visual pipeline builder**, a **real-time execution engine**, and an **interactive data inspector**.

## Quick Start

```bash
git clone https://github.com/test-user/mgl-test-ping
cd mgl-test-ping
npm install
npm run dev
```

## Features

- 🖊️ MGL Scripting Language (SQL-inspired DSL)
- 🔀 Visual Pipeline Builder (drag-and-drop)
- ⚡ Real-Time Execution (browser-side)
- 📊 Live Pipeline DAG with timing
- 🔍 Data Inspector (schema, stats, table)
- 🗂️ Multi-File Projects with auto-save
- 🐛 Debug Mode (step-through execution)
- 📈 Performance Panel
- 🔌 Plugin System

## Example

```mgl
data = read("users.csv")
adults = data.filter(age > 18)
adults.sort(name).write("adults.csv")
```

## License

[MIT](LICENSE) © 2024 MGL Contributors
