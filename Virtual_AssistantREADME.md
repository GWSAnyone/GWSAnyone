# 🎤 Virtual AI Companion - Local Voice Assistant

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org/)
[![CUDA](https://img.shields.io/badge/CUDA-12.4+-76B900?style=flat-square&logo=nvidia&logoColor=white)](https://developer.nvidia.com/cuda-zone)
[![Windows](https://img.shields.io/badge/Windows-10/11-0078d4?style=flat-square&logo=windows&logoColor=white)](https://microsoft.com/windows/)
[![Status](https://img.shields.io/badge/Status-Devoloping-yellow?style=flat-square)](https://github.com/GWSAnyone/Virtual_Assistant)

> **Real-time local AI assistant with voice interface, GPU acceleration and sub-6 second response time**

## 🏗️ Technical Architecture

- **🧠 Local LLM inference** - Llama 3.1 8B or other with GPU layers optimization
- **🎤 Real-time STT** - Faster-Whisper with CUDA acceleration
- **🔊 Edge TTS synthesis** - Cloud-based voice generation with local caching
- **⚡ Async processing** - Non-blocking audio pipeline with concurrent operations
- **💾 Intelligent caching** - Multi-level cache system for repeated queries
- **🎨 Modern GUI** - Flet-based interface with real-time chat and controls

## 🚀 Quick Start

```bash
# Clone and setup
git clone https://github.com/GWSAnyone/Virtual_Assistant.git
cd Virtual_Assistant

# Install dependencies
cd backend && pip install -r requirements.txt
cd ../frontend && pip install -r requirements.txt

# Run GUI version
cd frontend && python flet_app.py
# Or CLI version
cd backend && python simple_system.py
```

> **⚠️ Prerequisites:** Python 3.10+, NVIDIA GPU (RTX 3080+ recommended), 16GB+ RAM

## ⚡ Key Features

### 🧠 **AI Processing**
- **Local LLM** - Llama 3.1 8B with 32 GPU layers for optimal performance
- **Voice recognition** - Faster-Whisper Base model with CUDA acceleration
- **Speech synthesis** - Edge TTS with Russian/English voice support
- **Context memory** - Persistent conversation history and character profiles

### 📊 **Performance Optimization**
- **Sub-6 second latency** - Full voice-to-voice processing cycle
- **GPU memory management** - Efficient VRAM usage for RTX 3080 (10GB)
- **Async architecture** - Parallel processing of STT, LLM, and TTS
- **Smart caching** - Reduced repeated processing overhead

### 🎨 **User Interface**
- **Modern GUI** - Flet-based web interface with real-time chat
- **Voice controls** - Hands-free interaction with push-to-talk
- **Character system** - Customizable AI personality and behavior
- **Settings panel** - Real-time configuration without restarts

## 🔧 Technology Stack

### Core Technologies
```python
# Main dependencies
llama-cpp-python    # Local LLM inference with CUDA
faster-whisper     # GPU-accelerated speech recognition  
edge-tts          # Cloud speech synthesis
flet              # Modern web-based GUI framework
```

### System Integration
- **Python 3.10+** - Async/await patterns for concurrent processing
- **CUDA 12.4+** - GPU acceleration for LLM and STT models
- **Flet Framework** - Cross-platform GUI with web technologies
- **JSON Configuration** - Flexible settings and character profiles

## 🏗️ Project Architecture

```
Virtual_Assistant/
├── backend/                        # Core application logic
│   ├── simple_system.py            # CLI interface
│   ├── modules/                    # Component modules
│   │   ├── llm/                    # LLM inference components
│   │   ├── stt/                    # Speech-to-Text processing
│   │   └── tts/                    # Text-to-Speech synthesis
│   └── config/                     # Configuration management
├── frontend/                       # GUI interface
│   ├── flet_app.py                 # Main application
│   └── gui_settings.json           # GUI configuration
├── data/characters/                # Character data
│   ├── character_memory.json       # Conversation history
│   └── character_profile.json      # Character profiles
├── models/                         # AI model files
├── temp/                           # Temporary files
└── logs/                           # Application logs
```

## 📈 Performance Metrics

| Component | Latency | Optimization | Hardware |
|-----------|---------|--------------|----------|
| **STT Processing** | 0.3-0.8s | CUDA acceleration | RTX 3080 |
| **LLM Inference** | 2-4s | 32 GPU layers | 10GB VRAM |
| **TTS Synthesis** | 0.5-1s | Edge cloud + cache | Network |
| **Full Cycle** | **3-6s** | **Parallel pipeline** | **Total** |

## 🔄 Development Status

**Current Version:** 3.0 - MVP Ready  
**Next Release:** 3D Character, Enhanced GUI

### Recent Improvements
- ✅ **Latency optimization** - 40% faster response times
- ✅ **Memory management** - Stable long-running sessions
- ✅ **GUI redesign** - Modern Flet-based interface
- ✅ **Character system** - Persistent personality profiles

### Planned Features
- 🔄 **3D Character backend** - Visual avatar integration
- 🔄 **Enhanced GUI** - Advanced voice visualization
- 🔄 **Model switching** - Runtime LLM selection
- 🔄 **Cloud sync** - Character profile synchronization

## 🎯 For Developers

This project demonstrates expertise in:
- **AI/ML Integration** - Local model deployment and optimization
- **Performance engineering** - GPU memory management and latency reduction
- **Async programming** - Concurrent audio processing pipelines
- **GUI development** - Modern interface with real-time interactions
- **System optimization** - Hardware-specific performance tuning

## 📞 Contact & Access

> **Private Repository:** Full source code available upon request for technical review

- **Repository** - [Virtual_Assistant (Private)](https://github.com/GWSAnyone/Virtual_Assistant)
- **Demo** - Live voice assistant demonstration available
- **Technical Details** - Architecture discussion and code review

---

<div align="center">
  <i>Local AI companion with enterprise-grade performance</i>
</div> 