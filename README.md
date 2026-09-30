<div align="center">
### *Your complete AI coding workspace—portable across Windows, Linux, and macOS.*

Run the official DeepSeek Harness from one self-contained folder on an internal disk, USB drive, or external SSD. Your runtimes stay isolated by operating system while chats, settings, skills, plugins, and credentials travel with you.

[![Latest release](https://img.shields.io/github/v/release/techjarves/Deepseek-Harness-Portable?display_name=tag&style=flat-square&color=2563eb)](https://github.com/techjarves/Deepseek-Harness-Portable/releases/latest)
[![Platforms](https://img.shields.io/badge/platforms-Windows%20%7C%20Linux%20%7C%20macOS-0f172a?style=flat-square)](#supported-platforms)
[![Architecture](https://img.shields.io/badge/CPU-x64%20%7C%20arm64-64748b?style=flat-square)](#supported-platforms)
[![Cross-platform tests](https://img.shields.io/github/actions/workflow/status/techjarves/Deepseek-Harness-Portable/test.yml?branch=main&style=flat-square&label=tests)](https://github.com/techjarves/Deepseek-Harness-Portable/actions/workflows/test.yml)
[![Watch demo](https://img.shields.io/badge/Watch-Demo-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://youtu.be/nyTJ-1sqkVU)

[**Download latest release**](https://github.com/techjarves/Deepseek-Harness-Portable/releases/latest/download/deepseek-harness-portable.zip) · [**Watch walkthrough**](https://youtu.be/nyTJ-1sqkVU) · [**Quick start**](#quick-start) · [**How portability works**](#how-portability-works) · [**Troubleshooting**](#troubleshooting)

</div>

---

<div align="center">

## Video walkthrough

<a href="https://youtu.be/nyTJ-1sqkVU">
  <img src="https://img.youtube.com/vi/nyTJ-1sqkVU/maxresdefault.jpg" alt="Watch the DeepSeek Harness Portable walkthrough on YouTube" width="100%">
</a>

**[▶ Watch the complete walkthrough on YouTube](https://youtu.be/nyTJ-1sqkVU)**

</div>

---

## Why this project?

DeepSeek Harness normally depends on a local Node.js environment and stores host-specific paths. This project wraps the official Harness distribution with a portable bootstrap that keeps installation, updates, runtime dependencies, and cross-platform session migration inside one folder.

| | Capability | What it means |
| --- | --- | --- |
| 🚀 | **One-command startup** | Run the launcher for your operating system to open the local web interface. |
| 💾 | **One movable folder** | Use an internal drive, USB drive, external SSD, or an exFAT volume. |
| 🧩 | **No global runtime required** | Portable Node.js, pnpm, native packages, and caches remain inside the folder. |
| 🖥️ | **Lazy platform setup** | Only the runtime for the operating system currently in use is downloaded. |
| 💬 | **Cross-platform chats** | Workspace paths and compressed session headers are migrated when the folder changes operating systems. |
| 🔄 | **Tested automatic updates** | Updates are installed only after the release passes the supported-platform test matrix. |
| 🧹 | **Recoverable reset** | Remove mutable application data while preserving models and reinstall essentials. |

## Supported platforms

| Operating system | Architecture | Baseline | Launcher |
| --- | --- | --- | --- |
| Windows 10/11 | x64 | 64-bit desktop Windows | `windows.bat` |
| Linux | x64 | glibc; Ubuntu 22.04 compatible | `linux.sh` |
| macOS | Apple Silicon | arm64 | `mac.sh` |

> [!NOTE]
> Windows ARM64, Linux ARM64, Intel macOS, and musl-based Linux distributions are not supported in version 1.
