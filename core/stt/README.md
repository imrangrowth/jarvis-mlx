# Speech-to-Text Core Module

Platform-agnostic Speech-to-Text implementation.

## Overview

This module provides a unified interface for STT operations.

## API

```python
class STTEngine:
    def __init__(self, model_path: str)
    def transcribe(self, audio_path: str) -> str
    def transcribe_stream(self, audio_stream: bytes) -> Iterator[str]
    def load_model(self, model_path: str) -> None
```
