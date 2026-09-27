# Kornel by Redtek

> Autonomous local-edge AI engine built with C++/Qt 6.11 and real-time RVC neural voice synthesis, optimized for bare-metal execution on legacy GPU hardware.

---

## ⚡ Performance Benchmarks
- **Target Hardware:** NVIDIA GTX 950 (2GB VRAM legacy setup via CUDA)
- **Framework:** C++ / Qt 6.11.1 (MinGW 64-bit) + FFmpeg 7.1.3
- **RVC Synthesis Latency:** **~630ms – 900ms** (Sub-second local rendering)
- **Audio Output:** Local 48kHz / 16-bit PCM WAV stream pipeline
- **Network Overhead:** Zero cloud voice/execution API dependencies

---

## 🔒 Intellectual Property Notice
> Source code logic remains proprietary under **Redtek** and is held in a private development repository. This repository serves as the official technical showcase, execution benchmark trace, and public binary distribution point for the Lablab.ai hackathon submission.

---

## ⚙️ Workflow & Configuration

### 1. Terminal Session Binding
Initialize the Gemini session handle via command prompt prior to UI execution:
```cmd
KornelCore.exe --session-init
