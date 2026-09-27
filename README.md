# Awesome-Edge-AI-Platform

## Top Edge AI Platforms Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Edge Model Deployment, Inference Runtimes, Edge Orchestration & On-Device ML*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Edge AI**. These tools help developers and enterprises deploy, manage, and run machine learning models on edge devices — from microcontrollers and embedded systems to edge servers and IoT gateways.



**Examples** include NVIDIA Fleet Command, Edge Impulse, ClearBlade, ZEDEDA, KubeEdge, Balena, Avassa, FogHorn, Adlink Edge, and Lenovo Open Cloud Automation (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom inference pipelines, and transparent edge orchestration — ideal for teams that need full control over their edge AI infrastructure without per-device SaaS fees or vendor lock-in.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents



- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[NVIDIA Fleet Command](https://www.nvidia.com/)**  

  Edge AI management platform for deploying and managing AI applications across distributed NVIDIA Jetson and GPU-equipped edge devices. Provides OTA updates, fleet monitoring, and remote management .



- **[Edge Impulse](https://edgeimpulse.com/)**  

  Leading edge AI development platform with AutoML for sensor-based ML on microcontrollers. The open-source **Piccolo AI** is the community edition of SensiML Analytics Studio, providing AutoML for time-series sensor data on low-power MCUs. Features ML Engine, Embedded ML SDK, and web UI. AGPLv3 licensed. Open-source version available for individual developers, researchers, and enthusiasts .



- **[ClearBlade](https://clearblade.com/)**  

  Enterprise IoT and edge computing platform. Provides edge orchestration, device management, and AI inference at the edge with cloud connectivity.



- **[ZEDEDA](https://zededa.com/)**  

  Edge virtualization and orchestration platform. Provides centralized management of edge applications and devices with security and lifecycle management.



- **[Balena](https://www.balena.io/)**  

  IoT fleet management platform built on balenaOS (Linux-based, container-ready OS). Manages Docker containers on embedded devices with OTA updates, VPN access, and fleet monitoring. balenaOS is built on Yocto and runs on 90+ device types with software containers. Community Edition free, paid plans for larger fleets .



- **[Avassa](https://avassa.io/)**  

  Edge application orchestration platform for containerized workloads at the edge. Provides application lifecycle management, monitoring, and secure connectivity.



- **[FogHorn](https://foghorn.io/)**  

  Edge AI platform for industrial IoT. Provides real-time analytics and ML inference at the edge for manufacturing, oil & gas, and utilities.



- **[Adlink Edge](https://www.adlinktech.com/)**  

  Edge computing platforms and software for AI inference at the edge. Provides hardware and software solutions for industrial AI applications.



- **[Lenovo Open Cloud Automation](https://www.lenovo.com/)**  

  Edge-to-cloud automation platform. Provides infrastructure management, orchestration, and AI deployment across edge locations.



## Open-Source GitHub Projects



### Edge AI Orchestration & Runtime



- **[KubeEdge](https://github.com/kubeedge/kubeedge)**  

  CNCF graduated Kubernetes-native edge computing framework. Extends native containerized application orchestration capabilities to edge nodes while providing cloud-edge synergy. Uses digital-twin state modeling to represent physical hardware devices as virtual objects, with MQTT-based messaging for communication with heterogeneous devices. A key distinction is node autonomy — edge nodes can operate independently when disconnected from the cloud. Go-based, CNCF hosted .



- **[Baetyl](https://github.com/baetyl/baetyl)**  

  Extends cloud computing, data, and services seamlessly to edge devices. Built-in support for 30+ industrial protocols and AI inference through MLflow integration. Docker-compatible orchestration with edge-native design. Part of LF Edge .



- **[EVE-OS](https://github.com/lf-edge/eve)**  

  Edge Virtualization Engine from LF Edge. A flexible foundation for IoT edge deployments with a choice of orchestration. Provides a secure, open edge OS for running containers and VMs on edge devices .



- **[Open Horizon](https://github.com/open-horizon/anax)**  

  LF Edge project for containerized application deployment and lifecycle management. Provides ML model synchronization to devices and Kubernetes clusters. Manages edge nodes and services at scale .



- **[Akri](https://github.com/project-akri/akri)**  

  A Kubernetes Resource Interface for the Edge. Exposes edge devices (cameras, sensors, USB, etc.) as Kubernetes resources. Makes it easy to use devices as if they were native Kubernetes resources. Rust-based .



### Edge AI Inference Frameworks



- **[TensorFlow Lite Micro](https://github.com/tensorflow/tflite-micro)**  

  TensorFlow Lite for Microcontrollers. The standard for running ML models on microcontrollers and embedded devices with limited memory. Optimized for Arm Cortex-M processors with CMSIS-NN acceleration. Powers Google's KWS model running in under 20ms on Cortex-M4 at 80MHz .



- **[ONNX Runtime](https://github.com/microsoft/onnxruntime)**  

  Cross-platform inference engine for ONNX models. Supports edge deployment with optimizations for mobile and embedded devices. High-performance inference across CPUs, GPUs, and NPUs .



- **[MNN](https://github.com/alibaba/MNN)**  

  Alibaba's blazing-fast, lightweight deep learning inference engine. Optimized for on-device LLMs and Edge AI with Vulkan support and Winograd algorithm. 16.1k stars .



- **[ncnn](https://github.com/Tencent/ncnn)**  

  High-performance neural network inference framework optimized for mobile platforms. Efficient AI deployment on edge devices with Vulkan and iOS support. 23.8k stars, 4.5k forks .



- **[llama.cpp](https://github.com/ggml-org/llama.cpp)**  

  Official inference framework for running LLMs locally. 65K stars, enables fast CPU/GPU inference with significant speed and energy efficiency gains. NVIDIA 35% speed boost in 2026 .



- **[MLC LLM](https://github.com/mlc-ai/mlc-llm)**  

  Universal LLM deployment engine with OpenAI-compatible API. Cross-platform support for edge devices. Part of the MLC ecosystem .



- **[ExecuTorch](https://github.com/pytorch/executorch)**  

  PyTorch's on-device inference runtime for mobile and edge. Powers Meta's apps. Optimized for mobile deployment with hardware acceleration .



- **[MediaPipe](https://github.com/google-ai-edge/mediapipe)**  

  Cross-platform framework for building customizable on-device ML pipelines for live and streaming media. Google's solution for edge vision and audio processing .



- **[OpenVINO](https://github.com/openvinotoolkit/openvino)**  

  Intel's toolkit for optimizing and deploying AI inference. Optimized for edge devices with Intel CPUs, GPUs, and VPUs .



### Edge AI Development Tools



- **[Piccolo AI (SensiML)](https://github.com/sensiml/piccolo)**  

  Open-source AutoML solution for Edge AI model development. The open-source version of SensiML Analytics Studio. Features ML Engine for AutoML model building, Embedded ML SDK for inference and DSP, web UI, and Python client. Optimized for time-series sensor data classification on MCUs. AGPLv3 licensed. Requires 12GB+ Docker memory for local deployment .



- **[Zant](https://github.com/ZantFoundation/Z-Ant)**  

  Open-source Zig SDK for neural network deployment on microcontrollers. Focused on deployment rather than network creation — outputs static, highly optimized libraries. Supports quantization, pruning, SIMD, and GPU offloading. Targets ARM Cortex-M, RISC-V, and x86. Memory pooling and static allocation for constrained targets. WIP with MNIST support on Raspberry Pi Pico 2 .



- **[EdgeBrain](https://github.com/rudra496/EdgeBrain)**  

  Lightweight edge AI inference engine with sub-100ms latency. Run ML models locally with no cloud or API keys. FastAPI backend, PostgreSQL, Redis, MQTT (Mosquitto). Docker Compose deployment. MIT licensed .



- **[bitnet.cpp](https://github.com/microsoft/BitNet)**  

  Official inference framework for 1-bit LLMs. Fast and lossless CPU/GPU inference with significant speed and energy efficiency gains. 40.3k stars .



### Edge AI Hardware & Platforms



- **ESP32 AI** — Runs a 28.9-million-parameter language model fully offline on an ESP32-S3. MIT licensed .

- **Hailo Apps** — Runnable vision, VLM, LLM, and speech applications for Hailo accelerators on Raspberry Pi 5 and other platforms. MIT licensed .

- **PicoLM** — Runs quantized billion-parameter GGUF models through a zero-dependency C engine on low-memory RISC-V and Raspberry Pi devices. MIT licensed .



### Additional Strong Open-Source Options



- **Lightweight Kubernetes**: **K3s** (single binary, resource-constrained edge), **K0s** (zero-friction, x86/ARM/RISC-V), **MicroK8s** (lightweight Kubernetes) .

- **Edge Orchestration**: **OpenYurt** (CNCF, extends native Kubernetes to edge), **SuperEdge** (edge-native container management), **Octopus** (lightweight device management for Kubernetes) .

- **Edge OS**: **BalenaOS** (Docker on embedded devices), **Pantavisor Linux** (containerized embedded Linux), **Kairos** (immutable Linux meta-distribution) .

- **TinyML Frameworks**: **uTensor** (TinyML AI inference library, 1,921 stars), **EloquentTinyML** (Arduino TensorFlow Lite interface), **TensorFlow Lite Micro for Espressif** (623 stars) .



**Frameworks for building custom systems**: Combine **KubeEdge** or **Baetyl** for edge orchestration, **TensorFlow Lite Micro** or **ONNX Runtime** for inference, **Piccolo AI** for AutoML on sensor data, and **llama.cpp** or **MLC LLM** for on-device LLM deployment. Add **BalenaOS** for device fleet management and **Akri** for Kubernetes-native device integration.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Edge AI platforms handle sensitive device and inference data; ensure proper security hardening for distributed deployments.

- Self-hosted open-source solutions require proper device management, OTA update infrastructure, and fleet monitoring capabilities.



---



**Made for edge AI developers, embedded engineers, IoT architects, and ML deployment teams.**

Let's make edge AI more open, efficient, and accessible.
