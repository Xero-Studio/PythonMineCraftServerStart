# Minecraft 服务器启动工具 / Minecraft Server Launcher
本程序fork自原仓库，在原仓库更新
![Python](https://img.shields.io/badge/python-3.7%2B-blue)
![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey)

Python编写的Minecraft服务器管理工具，简化服务器配置、启动和管理过程  
A Python-based Minecraft server management tool that simplifies server configuration, startup, and management

## 主要功能 / Key Features

- 🚀 **一键启动服务器** - 自动配置并启动Minecraft服务器  
  **One-click startup** - Automatically configures and launches the Minecraft server
- ⚙️ **交互式配置向导** - 引导用户完成服务器设置  
  **Interactive configuration wizard** - Guides users through server setup
- 🔧 **配置文件管理** - 自动生成server.properties文件  
  **Config file management** - Automatically generates server.properties
- ✅ **自动同意EULA** - 自动处理eula.txt文件  
  **Auto-accept EULA** - Automatically handles eula.txt
- 🛠️ **错误诊断** - 实时检测并提示常见启动错误  
  **Error diagnostics** - Real-time detection of common startup errors
- 📂 **目录管理** - 快速打开服务器目录  
  **Directory management** - Quick access to server directory
- ℹ️ **帮助系统** - 提供Java安装指南和故障排除  
  **Help system** - Provides Java installation guides and troubleshooting

## 使用前提 / Prerequisites

1. **Python 3.7+** - [下载Python](https://www.python.org/downloads/)
2. **Java 17+** - Minecraft服务器必需 / Required for Minecraft server
3. **Minecraft服务器JAR文件** - [官方下载](https://www.minecraft.net/download/server)

## 快速开始 / Quick Start

1. 下载脚本文件 `PythonMinecraftServerStart.py`  
   Download the script file `PythonMinecraftServerStart.py`
2. 下载Minecraft服务器JAR文件并重命名为 `server.jar`  
   Download Minecraft server JAR and rename to `server.jar`
3. 将 `server.jar` 放在脚本同一目录下  
   Place `server.jar` in the same directory as the script
4. 运行脚本 / Run the script:
   ```bash
   python PythonMinecraftServerStart.py
