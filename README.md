# Jarvis MLX - Hybrid Architecture

**An all-in-one productivity solution running offline on macOS and Android using state-of-the-art technology.**

## 🎯 Overview

Jarvis MLX is a cross-platform application that brings powerful AI capabilities to your devices while maintaining complete offline functionality. Built with a hybrid architecture that separates platform-agnostic ML operations from platform-specific implementations.

## ✨ Features

### Core Capabilities
- 🎤 Speech-to-Text (STT)
- 🧠 Large Language Models (LLM)
- 🔊 Text-to-Speech (TTS)

## Project layout (high-level)

- core/ - platform-agnostic ML logic
- platforms/ - platform-specific wrappers (macOS, Android, server)
- shared/ - shared utils and datamodels

See ARCHITECTURE.md in the repo for full details.
