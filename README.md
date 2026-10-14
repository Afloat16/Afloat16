<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Afloat16/Afloat16/91901fa33a12a0c3c5ee6942db0630441ae0ffa1/assets/banner-dark.svg">
  <img src="https://raw.githubusercontent.com/Afloat16/Afloat16/91901fa33a12a0c3c5ee6942db0630441ae0ffa1/assets/banner-light.svg" alt="Afloat16 — robotics, large language models, and 3D reconstruction" width="100%">
</picture>

<div align="center">

**My research focuses on robotics, large language models, and 3D reconstruction.**

I build reproducible tools and contribute focused fixes to the libraries behind them.

Python · TypeScript · Reproducible experiments · Upstream engineering

[Explore my projects](https://github.com/Afloat16/research-to-fix/blob/main/docs/PROJECTS.md) · [Merged contributions](#selected-merged-contributions) · [简体中文](README.zh-CN.md)

</div>

## Projects I build

| Robotics | Large language models | 3D reconstruction |
|---|---|---|
| **[Bag Timeline Audit](https://github.com/Afloat16/bag-timeline-audit)**<br>Read-only ROS 2 SQLite/MCAP timestamp diagnostics. | **[LLM Handshake](https://github.com/Afloat16/llm-handshake)**<br>Bounded OpenAI-compatible endpoint probes and report comparisons. | **[ReconTrail](https://github.com/Afloat16/recontrail)**<br>CPU photogrammetry, sparse geometry and offline reports. |
| **[TF Route Audit](https://github.com/Afloat16/tf-route-audit)**<br>Exported TF and native URDF topology/time-window checks. | **[SSE Toolcall Audit](https://github.com/Afloat16/sse-toolcall-audit)** and **[Tooltrace Audit](https://github.com/Afloat16/tooltrace-audit)**<br>Saved stream and tool-execution diagnostics. | **[Pose Convention Bridge](https://github.com/Afloat16/pose-convention-bridge)** and **[COLMAP Model Audit](https://github.com/Afloat16/colmap-model-audit)**<br>Explicit pose conversion and text-model preflight. |

Research and engineering workflow: [Research to Fix](https://github.com/Afloat16/research-to-fix) · [Debate Direction](https://github.com/Afloat16/debate-direction) · [StewardCheck](https://github.com/Afloat16/ai-dev-steward/tree/main/tools/stewardcheck) · [Agent Action Notifier](https://github.com/Afloat16/agent-action-notifier) · [Jev MCP](https://github.com/Afloat16/jev-mcp).

**How I work:** isolate the symptom, understand the boundary, write a regression, and make the result inspectable. The [six domain utilities](https://github.com/Afloat16/research-to-fix/blob/main/docs/DEMAND_REVIEW.md#validation-for-this-release) have **67 local tests and 36 passing OS/Python CI combinations** at the recorded release. These are experimental diagnostics and conversion tools; each repository documents its limits.

## Selected merged contributions

Public upstream work: **41 merged PRs across 17 repositories**, checked on **14 October 2026**. The examples below are code fixes with accompanying regression coverage.

| Upstream project | What I contributed | Evidence |
|---|---|---|
| [DeepFace](https://github.com/serengil/deepface) · 23,549 ★ | Clip face boxes before array slicing; add crop-bound regressions. | [#1655](https://github.com/serengil/deepface/pull/1655) · merged |
| [Sentence Transformers](https://github.com/huggingface/sentence-transformers) · 19,171 ★ | Preserve ranking-loss gradients with weighted log-sigmoid. | [#4116](https://github.com/huggingface/sentence-transformers/pull/4116) · merged |
| [Kornia](https://github.com/kornia/kornia) · 11,424 ★ | Normalize small-root quartics to restore numerical threshold behavior. | [#5474](https://github.com/kornia/kornia/pull/5474) · merged |
| [Denoising Diffusion](https://github.com/lucidrains/denoising-diffusion-pytorch) · 10,706 ★ | Route external and self-conditioning consistently in 1D diffusion. | [#373](https://github.com/lucidrains/denoising-diffusion-pytorch/pull/373) · merged |
| [Atomic Agents](https://github.com/Eigenwise/atomic-agents) · 6,283 ★ | Keep prior chat history intact when loading fails. | [#292](https://github.com/Eigenwise/atomic-agents/pull/292) · merged |
| [Robotics Toolbox](https://github.com/petercorke/robotics-toolbox-python) · 3,536 ★ | Preserve Unicycle angular turn-rate units and limit semantics. | [#719](https://github.com/petercorke/robotics-toolbox-python/pull/719) · merged |
| [RSL-RL](https://github.com/leggedrobotics/rsl_rl) · 3,065 ★ | Resume the RND exploration schedule from PPO checkpoints. | [#240](https://github.com/leggedrobotics/rsl_rl/pull/240) · merged |
| [PyPose](https://github.com/pypose/pypose) · 1,614 ★ | Keep Cauchy objective values accurate for small residuals. | [#416](https://github.com/pypose/pypose/pull/416) · merged |

Stars belong to the upstream projects and are a dated snapshot. PR links show the exact changes, reviews and validation limits. [Contribution details](docs/CONTRIBUTIONS.md).

## Maintainer-approved robotics work

The repository owner approved the current PR revisions. Both are **awaiting merge** and are separate from the merged contributions above.

| Contribution | Change | Review milestone |
|---|---|---|
| [Robotics Toolbox #735](https://github.com/petercorke/robotics-toolbox-python/pull/735) | Use circular heading moments in particle filters. | [Owner approval](https://github.com/petercorke/robotics-toolbox-python/pull/735#pullrequestreview-5515511147) · awaiting merge |
| [Robotics Toolbox #736](https://github.com/petercorke/robotics-toolbox-python/pull/736) | Normalize quintic trajectory time to preserve boundary constraints. | [Owner approval](https://github.com/petercorke/robotics-toolbox-python/pull/736#pullrequestreview-5515624165) · awaiting merge |


---

[Project guide](https://github.com/Afloat16/research-to-fix/blob/main/docs/PROJECTS.md) · [Demand research](https://github.com/Afloat16/research-to-fix/blob/main/docs/DEMAND_REVIEW.md) · [Contribution record](docs/CONTRIBUTIONS.md)

