<a href="https://shayanbianconi.com/">
  <picture>
    <source media="(max-width: 600px)" srcset="./assets/portfolio/profile-header-mobile.svg">
    <img src="./assets/portfolio/profile-header.svg" width="100%" alt="Shayan Bianconi — AI Product Engineer. Making AI work in the real world.">
  </picture>
</a>

**AI Product Engineer · Los Angeles**<br>
[Portfolio ↗](https://shayanbianconi.com/) · [Email](mailto:shayanx45@gmail.com) · [LinkedIn](https://www.linkedin.com/in/shayan-bianconi/) · [Repositories](https://github.com/Elevatormusic?tab=repositories)

I turn models and technical constraints into useful products. My work spans local inference, creative tools, audio software, and physical simulation.

## Selected work

### 01 / [Modly × Hunyuan3D](https://github.com/Elevatormusic/modly-hunyuan3d-2-1-shape-extension)

**More room to create.** An image-to-3D workflow with textured assets, mesh cleanup, and export. I integrated Tencent's Hunyuan3D into Modly and staged components between CPU and GPU to reduce idle GPU weights.

One recorded RTX 3090 texture-stage benchmark used **20.4 → 13.0 GB of reserved GPU memory**, a **36% reduction**, with runtime changing from **111 → 116 seconds**. [Measurement record](https://github.com/Elevatormusic/modly-hunyuan3d-2-1-shape-extension/blob/main/capacity.py#L12-L21).

`Python` `PyTorch` `CUDA`

### 02 / [EARS Bridge](https://github.com/Elevatormusic/ears-bridge)

**Two microphones. One clear workflow.** A desktop bridge between miniDSP EARS and Dirac Live. Per-ear calibration, automatic selection, and drift correction let two independent audio systems work together without mixing the measurements.

**Public alpha.** Windows hardware-tested; macOS device validation remains pending. [Website and demo ↗](https://elevatormusic.github.io/ears-bridge/)

`C++` `JUCE` `DSP` `CMake`

### 03 / [Local AI Systems](https://github.com/Elevatormusic/GLM-5.3-Flash-NVFP4-DFlash2-2x-DGX-Spark)

**From model weights to everyday tools.** Local inference on two NVIDIA DGX Spark systems, connected to coding assistants through shared APIs. I adapt community deployment recipes, resolve compatibility gaps, and build health checks, startup automation, and recovery tooling.

The linked repository is a **deployment recipe fork**. My work is integration and qualification, built on upstream models and runtimes.

`vLLM` `Docker` `Linux` `Python` `Model APIs`

## Research & developer tools

**[WaveGrating](https://shayanbianconi.com/#wavegrating)** — A wave-optical renderer research project that connects numerical simulation with Blender scene authoring. **Research in progress:** material accuracy and general scene rendering remain open.

**[Hermes Classic Gold](https://github.com/Elevatormusic/hermes-classic-gold-pack)** — Model controls, session costs, and hardware telemetry in one desktop extension, with persistent settings and update-aware installation.

**[Apple HIG for Agents](https://github.com/Elevatormusic/apple-hig)** — Platform-specific design and accessibility guidance for interface development and review. [Examples and live demo ↗](https://elevatormusic.github.io/apple-hig/)

## How I work

Understand the constraint. Build the useful path. Measure the tradeoff.

I work across product design, implementation, and deployment. I use Codex, Claude Code, and Hermes, define requirements, review generated code, and validate changes with automated tests and hardware measurements. Installers, health checks, recovery paths, and documentation are part of the product.

My wider engineering background includes audio measurement, CAD, custom hardware, and physical simulation. I distinguish a prototype, a tested workflow, and a released product.

**Core tools:** Python · TypeScript · JavaScript · C++ · PyTorch · CUDA · vLLM · Docker · Linux · Electron · JUCE

---

Interested in AI product engineering, applied AI, and developer tools roles.<br>
**[Explore the portfolio ↗](https://shayanbianconi.com/)** · **[Get in touch](mailto:shayanx45@gmail.com)**

<sub>Performance figures describe the stated hardware and workload. They are not universal benchmarks.</sub>
