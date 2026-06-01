# Awesome On-Device AI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

>  A curated list of open-source tools, models, and frameworks for running AI locally on consumer hardware, smartphones, and edge devices.

Running AI locally offers massive benefits: **100% privacy**, **zero API costs**, and **offline functionality**. This repository serves as a central hub for developers and power users navigating the fragmented local AI ecosystem.

##  Table of Contents
- [Inference Engines & Runtimes](#-inference-engines--runtimes)
- [GUI & Desktop Wrappers](#-gui--desktop-wrappers)
- [Mobile-Specific Tools](#-mobile-specific-tools)
- [Optimized Models](#-optimized-models)
- [Voice & Audio](#-voice--audio)

---

###  Inference Engines & Runtimes
The core software that allows consumer hardware to read and run AI models.
* [llama.cpp](https://github.com/ggerganov/llama.cpp) - Inference of LLaMA model in pure C/C++. The foundation of modern local AI.
* [Ollama](https://ollama.com/) - Get up and running with large language models locally. (Mac/Linux/Windows).
* [MLC LLM](https://github.com/mlc-ai/mlc-llm) - Universal LLM deployment on diverse hardware backends (including mobile phones).
* [ONNX Runtime](https://onnx.ai/) - Cross-platform, high-performance scoring engine for machine learning models.
* [Whisper.cpp](https://github.com/ggerganov/whisper.cpp) - High-performance inference of OpenAI's Whisper automatic speech recognition (ASR) model.
* [Google AI Edge Gallery](https://github.com/google-ai-edge/ai-edge-gallery) - Experimental open-source Android app to browse, download, and run Hugging Face models locally. Supports TFLite/ONNX with NNAPI acceleration.
* [llmedge](https://github.com/llmedge/llmedge) - Powerful Android library for seamless on-device AI inference. Supports GGUF language models and integrates various AI features directly into mobile apps.
* [Airgap](https://github.com/airgap-ai/airgap) - Open-source React Native framework for offline-first customer support chatbots. Runs Gemma 4 E2B locally via llama.rn with seven industry templates.
* [Off Grid](https://github.com/offgrid-ai/offgrid) - Open-source React Native app for on-device LLM chat, vision models (SmolVLM, LLaVA), and Stable Diffusion image generation on iOS & Android.

###  GUI & Desktop Wrappers
User-friendly interfaces for interacting with local models.
* [LM Studio](https://lmstudio.ai/) - Discover, download, and run local LLMs. (Extremely popular for beginners).
* [Jan.ai](https://jan.ai/) - An open-source ChatGPT alternative that runs 100% offline on your computer.
* [GPT4All](https://gpt4all.io/) - Desktop application that lets you run open-source AI models offline.
* [Pinokio](https://pinokio.computer/) - AI browser that lets you install and run AI applications locally with one click.

###  Mobile-Specific Tools
Running AI directly on iOS and Android.
* [PocketPal AI](https://github.com/pocketpal-ai/pocketpal-ai) - An app that brings LLMs to mobile phones directly.
* [DrawThings](https://apps.apple.com/app/draw-things-ai-generation/id6444050920) - Run Stable Diffusion locally on iOS and macOS.
* [MediaPipe](https://developers.google.com/mediapipe) - Google's cross-platform framework for creating efficient on-device ML pipelines (Android/iOS).
* [PocketPal AI](https://github.com/pocketpal-ai/pocketpal-ai) - Brings LLMs to mobile phones directly with a polished, user-friendly interface. Great for beginners exploring local AI.
* [Flower Intelligence](https://github.com/flowerlabs/flower-intelligence) - Cross-platform inference library for seamless local/remote LLM interaction. Supports TypeScript, JavaScript, and Swift backends.
* [HuggingSnap](https://github.com/huggingface/huggingsnap) - iOS app that runs SmolVLM2 to help users learn about places and objects around them using multimodal understanding.
* [OLMoE.Swift](https://github.com/allenai/olmoe-swift) - Ai2's on-device chatbot powered by the OLMoE model. Runs entirely on-device for complete privacy and offline accessibility—even in Flight Mode.

###  Optimized Models
Models specifically quantized (shrunk) to run on consumer RAM and phone batteries.
* [TheBloke (HuggingFace)](https://huggingface.co/TheBloke) - The most prolific creator of quantized GGUF models for local use.
* [Microsoft Phi-3](https://azure.microsoft.com/en-us/blog/introducing-phi-3/) - Small Language Models (SLMs) designed specifically for edge and mobile devices.
* [Google Gemma](https://ai.google.dev/gemma) - Lightweight, state-of-the-art open models from Google.
* [LFM2.5](https://liquid.ai/lfm) - Liquid AI's ultra-efficient models (350M–1.6B parameters) built specifically for edge deployment with dynamic sparsity.
* [MobileLLM-Flash](https://ai.meta.com/research/publications/mobilellm-flash/) - Meta's 2026 release optimizing sub-3B models for mobile hardware with novel attention mechanisms.
* [Qwen-3.5](https://qwenlm.github.io/) - Alibaba's updated mobile-friendly series (0.8B, 2B) with improved multilingual support and efficient quantization.

###  Voice & Audio
* [Piper](https://github.com/rhasspy/piper) - A fast, local neural text to speech system that runs on a Raspberry Pi.
* [Vosk](https://alphacephei.com/vosk/) - Offline open source speech recognition toolkit, great for mobile apps.
  
---

##  Contributing
Your contributions are always welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

##  License
[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.

##  Related Awesome Lists
* [awesome-mobile-llm](https://github.com/stevelaskaridis/awesome-mobile-llm) - Curated list of LLMs and research papers targeted at mobile/embedded hardware.
* [awesome-mobile-ai](https://github.com/umitkacar/awesome-mobile-ai) - Mobile AI deployment resources: iOS CoreML, Android TFLite, ONNX, TensorRT, and more.
