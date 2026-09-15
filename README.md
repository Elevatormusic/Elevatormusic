<p align="center">
  <img
    src="./assets/atlas/shaya-atlas-studio-loop.gif"
    alt="SHAYA Field Atlas studio with a researcher, technical displays, botanical shelves, and a sunlit garden arch"
    width="100%"
  />
</p>

# Shayan Bianconi

**AI Product Engineer · Los Angeles, CA**

[Email](mailto:shayanx45@gmail.com) · [LinkedIn](https://www.linkedin.com/in/shayanbianconi/) · [Repositories](https://github.com/Elevatormusic?tab=repositories)

I build software that makes emerging AI useful, from the infrastructure that runs models to the interfaces people use.

Most of my projects start with a practical limitation: a model that will not deploy, a creative workflow that needs too much GPU memory, or two tools that should work together but do not. I work across product design, implementation, and deployment to solve the problem and make the result usable by someone other than me.

## Selected public projects

### [Local LLM Deployment Recipes](https://github.com/Elevatormusic/GLM-5.3-Flash-NVFP4-DFlash2-2x-DGX-Spark)

I adapt community deployment recipes and patch runtime compatibility gaps to make early-release models available in coding assistants. My development setup includes a two-node NVIDIA DGX Spark cluster and an RTX 3090 workstation.

Deployed **GLM-5.3-Flash within 2 days of release** and **Qwen3.8-Flash-Next within 3 days**. In my DeepSeek workload, API gateway optimization raised **aggregate concurrent throughput from 199–217 to 275 tokens/s**. Supporting work includes shared model APIs, startup automation, health checks, recovery tooling, and qualification tests.

*Python · vLLM · Docker · LiteLLM · Linux · OpenAI/Anthropic-compatible APIs*

### [Modly Hunyuan3D Extension](https://github.com/Elevatormusic/modly-hunyuan3d-2-1-shape-extension)

An image-to-3D workflow that brings Tencent's Hunyuan3D into Modly, with textured asset generation, mesh cleanup, and export for game and design workflows.

Reduced measured GPU memory usage from **20.4 GB to 13.0 GB — approximately 36% — at about 5% additional runtime**, bringing textured generation within a 16 GB GPU memory budget. Packaged a ready-to-use workflow and prebuilt Windows components, with 300 automated tests supporting repeatable generation.

*Python · PyTorch · CUDA* · [Input/output examples](https://github.com/Elevatormusic/modly-hunyuan3d-2-1-shape-extension#readme)

### [EARS Bridge](https://github.com/Elevatormusic/ears-bridge)

A desktop application that lets headphone enthusiasts use a two-microphone miniDSP EARS measurement device with Dirac Live, which expects a single microphone input. It handles per-ear calibration and routing, with feedback that helps users spot unreliable measurements.

Fixed clock drift that caused rejected measurements and built **570+ automated tests** across installation, measurement, and export workflows. Published Windows and macOS installers.

**Public alpha. Windows 11 tested; macOS hardware validation remains pending.**

*C++17 · JUCE · CMake · GitHub Actions* · [Website and demo](https://elevatormusic.github.io/ears-bridge/)

### [Hermes Classic Gold](https://github.com/Elevatormusic/hermes-classic-gold-pack)

A desktop extension that puts model settings, session costs, and hardware telemetry in one interface, without requiring changes to the underlying Hermes application.

Built the interface and Python backend, with update-safe installation, rollback, and removal. Added **206 automated tests** covering security and compatibility, and submitted upstream improvements for local-model management and routing.

*TypeScript · Electron · Python · GitHub Actions*

### [apple-hig](https://github.com/Elevatormusic/apple-hig)

A Claude Code plugin that brings platform-specific design and accessibility guidance into interface development and code review. It loads relevant guidance for the task rather than treating every interface as the same platform.

Published before-and-after examples and a live interface demo so the design changes can be inspected, not just described.

*UX systems · Accessibility · Prompt engineering · Claude Code* · [Examples and live demo](https://elevatormusic.github.io/apple-hig/)

## Internal tools and research

### Multi-agent code review

Built and used a review workflow that coordinates agents across pull requests, with repository context, structured tasks, and automated checks before accepting fixes. In one development session, **13 parallel agents resolved approximately 200 code findings across 7 pull requests**.

The workflow is in use in my own development. **Agent Review Orchestrator**, the separate application intended to package it, is currently at scaffold stage.

### acoustic-adapt

A private room-correction prototype built around measured acoustic data and a live-tested audio engine. Listener-following behavior currently uses simulated presence; real-room tracking remains research.

My earlier engineering work includes a custom industrial 3D printer, microphone-array design, CAD, and physical simulation.

## How I work

I use Codex, Claude Code, and Hermes throughout development. I define requirements and constraints, review generated code, and validate changes with automated tests and hardware measurements.

I build supporting infrastructure alongside the product: installers, deployment recipes, health checks, recovery paths, and documentation. I make the distinction between a prototype, a tested workflow, and a released product explicit.

## Technical toolkit

**Languages:** Python, TypeScript, JavaScript, C++17  
**AI and infrastructure:** PyTorch, CUDA, vLLM, TensorRT-LLM, Docker, Linux, LiteLLM  
**Applications and delivery:** Node.js, Electron, JUCE, CMake, REST APIs, GitHub API, GitHub Actions, Git  
**AI development:** LLM integration, multi-agent orchestration, prompt engineering, Model Context Protocol, inference optimization

## Contact

I'm interested in AI product engineering, applied AI, and developer tools roles where I can take ownership from prototype through release.

**[shayanx45@gmail.com](mailto:shayanx45@gmail.com)** · [LinkedIn](https://www.linkedin.com/in/shayanbianconi/)

<sub>Performance figures describe measurements from my development setups, not universal hardware benchmarks. Results depend on workload, hardware, and configuration.</sub>

