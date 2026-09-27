# 🐾 ZapCat — Custom GUI for Zapret

**ZapCat** is a modern, user-friendly graphical interface (GUI) for the **Zapret** DPI bypass utility. Built with HTML, CSS, JavaScript, and powered by a Python backend via `pywebview`, ZapCat brings a sleek winter-themed UI and an interactive mascot to make managing DPI strategies simple and enjoyable.

---

### ✨ Features

- 🐱 **Interactive Mascot:** Animated black cat mascot that reacts to connection states, blinks, and changes emotions.
- ⚡ **One-Click Control:** Easily start, stop, and toggle DPI bypass directly from the main screen.
- 🔍 **Automated Strategy Finder:** Built-in testing tool to help you scan and discover the most effective strategy for your ISP.
- ⚙️ **Flexible Configuration:** Quickly tweak game filters (TCP/UDP), IPSet parameters, domain lists (`list-general-user.txt`), and exclusion rules.
- 🛠️ **Maintenance Tools:** Access diagnostic logging, Discord cache cleaning, IPSet/hosts updates, and service management options in one place.
- ❄️ **Atmospheric UI:** Dark glassmorphism winter design with customizable snow falling effect and dual-language support (English & Russian).

---

### 🚀 Quick Start & Installation

1. Download the latest `ZapCat-v1.0-Portable.zip` from the **[Releases](../../releases)** section.
2. Extract the archive to any convenient folder on your computer.
3. **Important:** Right-click `ZapCat.exe` and select **"Run as administrator"** to allow proper Windows service configuration.

---

### ⚠️ Troubleshooting: Fixing Connection / Service Issues

If the DPI bypass is not working properly, failing to start, or stuck in a loading state, follow these quick reset steps using the built-in UI:

1. Open **ZapCat**.
2. Navigate to the **Tools** tab (`Инструменты`).
3. Click **Update Services** (`Обновить службы`).
4. Click **Uninstall Services** (`Удалить службы`) at the bottom of the tools list.
5. Click **Install Service** (`Установить службу`) to perform a clean reinstall.

> **Why does this happen?**  
> Windows may hold onto cached or conflicting service entries from previous Zapret or GoodbyeDPI installations. Reinstalling the service through the Tools menu clears these stale system entries and registers a fresh instance.
