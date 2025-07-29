# Rojo + Wally Project Template for Roblox Studio Projects

This project is based on [Rojo](https://github.com/rojo-rbx/rojo) v7.5.1, a tool that allows you to sync your local file system with Roblox Studio, and [Wally](https://wally.run), a package manager for the Roblox Lua ecosystem.

## 📦 What's Included?

- Organized project structure with reusable modules.
- Dependency management via Wally.
- Real-time syncing with Roblox Studio using Rojo.
- Ideal for frameworks like [Knit](https://github.com/Sleitnick/Knit) or [Cmdr](https://github.com/evaera/Cmdr).

---

## 🚀 Getting Started

### 1. Requirements

Make sure you have the following installed:

- [Rokit](https://github.com/rojo-rbx/rokit) (`rokit --version` to verify)
- [Rojo](https://github.com/rojo-rbx/rojo) (`rojo --version` to verify)
- [Wally](https://wally.run/install) (`wally --version` to verify)
- Roblox Studio

---

### 2. Build the Game File

This command generates a `.rbxlx` place file from your `default.project.json`:

```bash
rojo build -o "build.rbxlx"
```