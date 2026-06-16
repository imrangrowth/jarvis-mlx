# Text-to-Speech Core Module

Platform-agnostic Text-to-Speech implementation.

## Overview

This module provides a unified interface for TTS operations.

## API

```python
class TTSEngine:
    def __init__(self, model_path: str)
    def synthesize(self, text: str) -> bytes
    def synthesize_file(self, text: str, output_path: str) -> None
    def load_model(self, model_path: str) -> None
```
