# Core Module - Platform-Agnostic ML Engine

This directory will contain the platform-agnostic ML engine that powers Jarvis across all platforms.

- llm/ - LLM interface and loaders
- stt/ - STT interface (whisper wrappers)
- tts/ - TTS interface (MeloTTS wrappers)

Purpose: consolidate ML logic so it can be exposed by a server bridge for Android and reused by macOS.
