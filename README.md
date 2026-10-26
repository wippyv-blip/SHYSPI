# SHYSPI
### Local Autonomous AI Agent & High-Performance MoE Inference Engine

**Bringing powerful artificial intelligence to consumer hardware.**

SHYSPI is an independent artificial intelligence project focused on local AI agents, autonomous task execution, advanced Windows automation, and high-performance inference for large language models.

The project combines an AI agent environment built in part on **OpenCode** with a custom inference engine designed to improve the performance of large Mixture of Experts (MoE) models on consumer-grade GPUs.

Our mission is simple:

**Make powerful, autonomous AI more accessible, efficient, and independent of expensive cloud infrastructure.**

---

## 🚀 What Is SHYSPI?

SHYSPI is more than a traditional AI chatbot.

It is an evolving artificial intelligence system designed to interact with computers, execute tasks, assist with software development, and run powerful language models locally.

The project focuses on three major areas:

- **Autonomous AI Agents:** AI systems capable of planning and executing multistep tasks.
- **Local AI Infrastructure:** Running compatible language models on personal computers without requiring paid inference APIs.
- **Accelerated AI Inference:** Improving the efficiency of large language models using optimized memory and computation management.

SHYSPI is actively developed and tested on Windows.

---

## ⚡ SHYSPI Engine — Accelerated AI Inference

One of SHYSPI's most important developments is its custom experimental inference engine.

**SHYSPI Engine** was developed to investigate and overcome hardware limitations when running large language models, particularly Mixture of Experts architectures.

Traditional inference systems can face significant performance challenges when model weights exceed available GPU memory.

SHYSPI Engine explores alternative optimization strategies that make better use of available hardware resources.

### Key Research Areas

- Efficient execution of Mixture of Experts models.
- GPU memory optimization.
- Coordination between VRAM and system RAM.
- Dynamic memory management.
- Improved data movement during inference.
- Efficient utilization of consumer GPUs.
- Research into GPU, RAM, and NVMe storage integration.
- Local inference integration with AI agent frameworks.

The engine uses custom optimization techniques developed as part of the SHYSPI project.

**Specific algorithms, internal scheduling strategies, and proprietary optimization methods are not publicly disclosed.**

---

## 📊 Experimental Performance Results

SHYSPI Engine has demonstrated promising performance during internal testing.

### Qwen3.6-35B-A3B-MTP-UD-Q4_K_M— Local Inference

| Component | Configuration |
|---|---|
| Model | Qwen3.6-35B-A3B-MTP-UD-Q4_K_M |
| Architecture | Mixture of Experts (MoE) |
| Quantization | Q4_K_M |
| GPU | NVIDIA GeForce RTX 5070 |
| GPU Memory | 12 GB VRAM |
| System Memory | 32 GB RAM |
| Processor | AMD Ryzen 7 7800X3D |
| Inference Engine | SHYSPI Engine |
| Observed Generation Speed | Approximately 55–60 tokens/sec |

### Performance Highlight

**Up to approximately 63.5 tokens per second with Qwen3.6-35B-A3B-MTP-UD-Q4_K_M on an NVIDIA RTX 5070 12 GB GPU during internal testing.**

These results demonstrate the potential of optimized inference strategies for large MoE models on consumer hardware.

### Benchmark Disclaimer

These performance figures are internal development observations, not independently verified benchmarks.

Results may vary depending on model configuration, context length, workload, GPU memory usage, hardware specifications, and other execution conditions.

The project aims to publish additional reproducible performance information as development progresses.

---

## 🤖 SHYSPI Autonomous AI Agent

SHYSPI also includes an experimental autonomous AI agent system designed to assist users with complex computer tasks.

The agent development incorporates concepts and components from OpenCode alongside custom integrations and tools.

### Developed and Tested Capabilities

**AI-Powered Programming**
- Code generation and modification.
- Assistance with application development.
- File and project management.
- Multistep programming workflows.

**Windows Automation**
- Interaction with supported desktop applications.
- Keyboard and mouse automation.
- File system operations.
- Process management.
- Task execution through local tools.

**Computer Interaction**
- Browser automation.
- Optical character recognition (OCR).
- User interface interaction.
- Tool execution and feedback handling.

**Agent Architecture**
- Task planning.
- Multistep execution.
- Error detection and recovery.
- Execution logs.
- Local model integration.

Availability and reliability of individual capabilities depend on the SHYSPI version, model configuration, permissions, and operating environment.

---

## 🧠 Why SHYSPI Matters

Modern artificial intelligence models are becoming increasingly powerful, but their computational requirements can limit local accessibility.

Many large language models require substantial GPU memory or expensive cloud infrastructure.

SHYSPI investigates how software-level optimization can help bridge that gap.

The long-term vision is to enable more users to benefit from capable AI systems while retaining greater control over their computing environment.

### Our Development Goals

1. **Performance:** Improve inference speed and hardware utilization.
2. **Accessibility:** Make advanced local AI more practical on consumer computers.
3. **Autonomy:** Build AI agents capable of executing useful tasks.
4. **Privacy:** Support local execution without mandatory cloud inference.
5. **Innovation:** Explore new methods for efficient large-model execution.

---

## 🛠 Technologies and Foundations

SHYSPI combines original development with existing open-source technologies.

### OpenCode

OpenCode has been used as a foundation for parts of SHYSPI's AI agent development and workflow.

Official project:

https://github.com/anomalyco/opencode

SHYSPI extends its agent-oriented environment through custom integrations and development work.

### Qwen Language Models

Qwen language models are used in inference research, compatibility testing, and experimental deployments.

Official models:

https://huggingface.co/Qwen

### NVIDIA CUDA

NVIDIA GPU computing technologies are used within the project's development and testing environment.

SHYSPI is an independent project and is not officially affiliated with OpenCode, Qwen, or NVIDIA.

All included third-party components remain subject to their respective licenses and copyright requirements.

---

## 💻 SHYSPI for Windows

SHYSPI is being developed primarily for Windows computers.

Public builds, when available, will be distributed through the GitHub Releases section.

**[Download SHYSPI — Releases](https://github.com/wippyv-blip/SHYSPI/releases)**

Installation instructions, supported hardware, model requirements, and included components will be documented for each release.

A compatible local language model may be required, depending on the build.

The SHYSPI inference engine and AI agent are separate technical components and may have different compatibility requirements.

---

## 🔬 Ongoing Research

Development and experimentation continue in several areas:

- Higher-quality quantization support.
- Improved MoE inference performance.
- Efficient execution of larger models.
- Memory management across GPU, RAM, and NVMe storage.
- Better autonomous agent reliability.
- Broader local model compatibility.
- Improvements to installation and deployment.

Research objectives are not guarantees of future performance or product availability.

---

## 🔒 Source Code and Proprietary Technology

Certain components of SHYSPI, including internal inference optimizations, are proprietary.

This public repository serves as a home for project information, documentation, announcements, and authorized software distributions.

Publishing a compiled application or installer does not imply public release of proprietary source code.

Third-party open-source licenses and redistribution obligations continue to apply to any included components.

---

## 📌 Project Status

**Status: Active Experimental Development**

SHYSPI is an independent, evolving AI research and software development project.

Features, compatibility, performance, and availability may change between releases.

The project is focused on continuous experimentation, testing, optimization, and improvements.

---

## 🌎 Project Vision

We believe advanced artificial intelligence should not be limited exclusively to massive data centers or expensive server hardware.

SHYSPI explores how intelligent agents and optimized inference systems can bring more powerful AI capabilities directly to personal computers.

**The future of AI should be powerful, accessible, and capable of running locally.**

---

### SHYSPI
**Local AI. Autonomous Agents. Accelerated Intelligence.**

Independent AI Development Project

GitHub: https://github.com/wippyv-blip/SHYSPI

*Built with experimentation, engineering, and a passion for local artificial intelligence.*
