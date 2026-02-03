# Clash Sing

English | [中文简体](README_CN.md)

A high-performance cross-platform proxy client developed with Flutter and powered by the [sing-box](https://github.com/SagerNet/sing-box) kernel, featuring support for Clash configuration formats.

[![Release](https://img.shields.io/github/v/release/clash-sing/clash_sing)](https://github.com/clash-sing/clash_sing/releases)
[![License](https://img.shields.io/github/license/clash-sing/clash_sing)](LICENSE)

## 🌟 Features

- **High-Performance Kernel**: Powered by `sing-box` for extreme performance and stability.
- **In-House Core Plugin**: Utilizes the self-developed [flutter_sing_box](https://github.com/clash-sing/flutter_sing_box) plugin for efficient communication between Flutter and the sing-box kernel.
- **Configuration Compatibility**: Supports direct import and conversion of Clash configurations.
- **Modern UI**: Developed with Flutter, providing a fluid, beautiful, and responsive user interface.
- **State Management**: Uses Riverpod 3.0 for reactive state management.
- **Fast Persistence**: Based on MMKV for millisecond-level data access.

## 📱 Platform Support

The project is currently under active development. Platform support progress is as follows:

| Platform | Status | Remarks |
| :--- | :--- | :--- |
| **Android** | ✅ Supported | Provides universal and per-architecture (arm64/v7a/x64) builds |
| **Windows** | ☐️ In Development | Planned support |
| **macOS** | ☐️ In Development | Planned support |
| **iOS** | ☐️ Planned | Pending adaptation |
| **Linux** | ☐️ Planned | Pending adaptation |

## 🚀 Download & Installation

You can visit the [Releases page](https://github.com/clash-sing/clash_sing_app/releases) to download the latest installation packages.

- **Android**:
    - `universal`: Includes all architectures, larger size, suitable for all phones.
    - `arm64-v8a`: Recommended version, suitable for most modern 64-bit Android phones.
    - `armeabi-v7a`: Suitable for older 32-bit Android devices.
    - `x86_64`: Suitable for Android emulators or certain tablets.

## 🛠️ Architecture Overview

- **Core**: Integrates the [flutter_sing_box](https://github.com/clash-sing/flutter_sing_box) plugin for kernel communication.
- **Logic**: Uses `Riverpod` for business logic and state subscriptions.
- **Data**: Uses `MMKV` to store user settings and configuration files.
- **Theme**: Full Material 3 theme support, including dark mode and dynamic color adaptation.

## 🤝 Contributing

Feedback via Issues or contributions through Pull Requests are welcome.

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

**Disclaimer**: This tool is for learning and research purposes only. Please use it in compliance with local laws and regulations.
